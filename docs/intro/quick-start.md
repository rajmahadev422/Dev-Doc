# Quick Start

## 📋 Core Workflow

1. Regardless of the language, the OpenCV pipeline follows a standard logic:
2. Load the image into a data structure (usually a Mat or NumPy array).
3. Process the data (e.g., color conversion).
4. Display the result using a GUI or Canvas.
5. Release resources (especially critical in C++ and JS).

:::code

```py
import cv2

# Load image
img = cv2.imread('input.jpg')

# Process: Convert to Grayscale
gray_img = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)

# Display
cv2.imshow('Python Window', gray_img)

# Keep window open until a key is pressed
cv2.waitKey(0)
cv2.destroyAllWindows()
```

```cpp
#include <opencv2/opencv.hpp>

int main() {
    // Load image
    cv::Mat img = cv::imread("input.jpg");
    if(img.empty()) return -1;

    // Process: Convert to Grayscale
    cv::Mat gray_img;
    cv::cvtColor(img, gray_img, cv::COLOR_BGR2GRAY);

    // Display
    cv::imshow("C++ Window", gray_img);
    cv::waitKey(0);
    
    return 0;
}
```

```java
import org.opencv.core.*;
import org.opencv.imgcodecs.Imgcodecs;
import org.opencv.imgproc.Imgproc;
import org.opencv.highgui.HighGui;

public class App {
    static { System.loadLibrary(Core.NATIVE_LIBRARY_NAME); }

    public static void main(String[] args) {
        Mat img = Imgcodecs.imread("input.jpg");
        Mat gray = new Mat();

        // Process
        Imgproc.cvtColor(img, gray, Imgproc.COLOR_BGR2GRAY);

        // Display
        HighGui.imshow("Java Window", gray);
        HighGui.waitKey(0);
        System.exit(0);
    }
}
```

```js
// Assuming an HTML <img> with id 'imageSrc' and <canvas> with id 'canvasOutput'
let img = cv.imread('imageSrc');
let gray = new cv.Mat();

// Process
cv.cvtColor(img, gray, cv.COLOR_RGBA2GRAY, 0);

// Display to Canvas
cv.imshow('canvasOutput', gray);

// Cleanup (Crucial in JS to avoid memory leaks)
img.delete(); 
gray.delete();
```

:::

## Second

:::code

```sh
git clone https://github.com/opencv/opencv.git
cd opencv
```

:::

## Summary Table

| Feature | Python | C++ | Java | JavaScript |
| :--- | :--- | :--- | :--- | :--- |
| Primary Object | numpy.ndarray | cv::Mat | Mat | cv.Mat |
| Color Default | BGR | BGR | BGR | RGBA |
| Performance | High | Very High | High | Moderate (Wasm) |
| Complexity | Low | Medium | High | Medium |
