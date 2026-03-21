![gsoc](https://raw.githubusercontent.com/rajmahadev422/GSoC-Proposal/e2e78bb9389d1049f41b1482897f37b66f3eddae/public/GSoC-logo.svg)

# <p align="center"> 🚀 GSoC Proposal</p>

![opencv](https://github.com/rajmahadev422/GSoC-Proposal/blob/main/public/opencv_logo.png?raw=true)

## Custom Markdown-to-HTML Documentation Engine

| | |
| --- | --- |
| **Organization** | OpenCV |
| **Possible Mentor** | Shiqi Yu |
| **Difficulty** | Medium |
| **Duration** | 175 hours |

---

## Personal Information
 
### Student Details

* **Name** : Mahadev Kumar
* **GitHub** : [rajmahadev422](https://github.com/rajmahadev422)
* **Email** : [Mahadev Raj](rajmahadev422@gmail.com) , [24je0035](24je0035@iitism.ac.in)
* **LinkedIn** : [Mahadev Kumar](https://www.linkedin.com/in/mahadev-kumar-15b2ba320)
* **Portfolio** : [Portfolio Link](https://portfolio-tau-three-ozpwygtbtt.vercel.app/)
* **Resume** : [Resume Link](https://drive.google.com/file/d/13vmP6K7SM7ObNtUgFnWEbi2vFCqwTJGj/view?usp=drivesdk)
* **TimeZone** : New Delhi (+5:30GMT)
* **Address** : Sitamarhi, Bihar, India, Pin-843323

### University Details

* **University** : Indian Institute of Technology (ISM) Dhanbad
* **Degree** : Batchelor of Technology
* **Branch** : Civil Engineering
* **Current Year** : 2nd
* **Expected Graduation** : 2028

### Personal Background

* I am a second-year undergraduate student at IIT (ISM) Dhanbad, pursuing Batchelor of Technology in Civil Engineering, with a strong focus on full-stack development.
* I am proficient in JavaScript (Reactjs, Nodejs), C++, and Python, with working knowledge of Java and experience using Git/GitHub.
* I have built a custom Markdown-to-HTML documentation engine featuring parsing, custom syntax ( `:::code`, `:::include` ), and dynamic UI components.
* My interests lie in system design and developer tools, and I enjoy building scalable, interactive solutions from scratch.

---

## 📄 Abstract

This project proposes the development of a lightweight, browser-based documentation engine that converts Markdown into an interactive HTML interface in real time. Built using HTML, CSS, and JavaScript, the system eliminates the need for backend services or build tools. It introduces custom syntax such as multi-language code tabs (`:::code`) and dynamic file inclusion (`:::include`) with line-level extraction. The goal is to create a simple, extensible, and efficient documentation system while demonstrating the internal working of modern documentation frameworks.

---

## 🧠 Background

Modern documentation platforms provide rich features but often require complex setups and build processes. This project focuses on building a lightweight alternative that runs entirely in the browser while still supporting advanced features like dynamic navigation, code rendering, and content inclusion.

---

## 💡 Motivation

My motivation comes from a strong interest in building developer tools and understanding systems at a deeper level. Existing documentation tools are powerful but complex. This project allows me to build a simple yet powerful system while exploring parsing, rendering, and UI design.

---

## 📘 Project Description

This project focuses on **building a browser-based documentation engine** that transforms Markdown into an interactive HTML interface. It includes a custom parsing pipeline (tokenizer → parser → renderer) and supports extended syntax for enhanced functionality such as **code tabs** and **file inclusion**. Additional features include *dynamic navigation*, *search*, and a *Table of Contents*.

---

## 💡 Proposed Solution

The system follows a modular pipeline:

> Markdown → Tokenizer → Parser → AST → Renderer → UI

Key components:

* Real-time Markdown rendering
* Custom syntax (`:::code`, `:::include`)
* Dynamic sidebar with search
* Hash-based routing
* Table of Contents generation
* Fully responsive UI

---

## 🔑 Main Work Components

* Build Markdown tokenizer, parser, and renderer
* Implement custom syntax features
* Develop routing and navigation system
* Add search and responsive UI
* Implement TOC and smooth navigation
* Optimize performance and handle edge cases

---

## 🎯 Deliverables & Milestones

### Phase 1: Core Engine (Weeks 1–2)

* Markdown rendering pipeline
* Syntax highlighting integration

### Phase 2: Custom Syntax (Weeks 3–4)

* `:::code` implementation
* Multi-language UI

### Phase 3: File Include System (Weeks 5–6)

* `:::include` with line slicing
* File caching

### Phase 4: Navigation & Routing (Week 7)

* Hash-based routing
* Dynamic sidebar

### Phase 5: Search & Responsiveness (Week 8)

* Sidebar search
* Mobile UI

### Phase 6: TOC & UX Enhancements (Week 9)

* TOC generation
* Smooth scrolling

### Phase 7: Optimization (Weeks 10–11)

* Performance improvements
* Bug fixes

### Phase 8: Final Delivery (Week 12)

* Documentation
* Deployment and final submission

---

## 📈 Benefits to the Organization

* Lightweight and **dependency-free** documentation system
* Improved contributor experience using **simple Markdown**
* Easy to extend and maintain
* Reduces complexity compared to existing tools
* Provides educational value for understanding documentation systems
* Not wait for make doxygen
* Single html file handles all document routing
* No need of backend
* Client-side rendering, No load of users

---

## ⚠️ Risk Analysis & Mitigation

* **Parsing Complexity:** Use robust parsing logic and test edge cases
* **Performance Issues:** Implement caching and optimize rendering
* **Browser Compatibility:** Use standard APIs and cross-browser testing
* **UI Complexity:** Build modular components and test responsiveness
* **Time Constraints:** Follow structured timeline with priorities

---

## ⭐ Why Me

[Live Link](https://rajmahadev422.github.io/GSoC-Proposal/)
[github-link](https://github.com/rajmahadev422/GSoC-Proposal.git)

* I have already built a similar **Markdown-to-HTML documentation engine**, giving me practical experience with parsing, rendering, and UI challenges.
* My background in full-stack development and proficiency in JavaScript, C++, and Python enables me to implement this project efficiently.
* I am highly motivated to build scalable systems from scratch and deliver a well-structured, extensible solution.

[md file](docs/tutorial/threshold_in_range.md)
[page](https://rajmahadev422.github.io/GSoC-Proposal/#/tutorial/threshold_in_range.md)

![img](https://github.com/rajmahadev422/GSoC-Proposal/blob/main/public/image.png?raw=true)
![img1](https://github.com/rajmahadev422/GSoC-Proposal/blob/main/public/img1.png?raw=true)
![img2](https://github.com/rajmahadev422/GSoC-Proposal/blob/main/public/img2.png?raw=true)

---

## 🚀 Future Improvements

* Full-text search
* Line highlighting
* Theme customization
* Plugin system

---

## 📄 Conclusion

This project delivers a **simple yet powerful** documentation engine that improves usability while maintaining flexibility and performance. It provides a strong foundation for future enhancements and contributes to better documentation workflows.
