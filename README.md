## Accessibility testing of web page www.netguru.com
## 1. [DevTools Audit Report](https://mlozowska.github.io/accessibility-testing/)
- with use of the **Lighthouse audit tool** that runs a series of tests and provides a score and specific feedback regarding **accessibility** (also performance, SEO, best practices) 
- run in incognito window to avoid page's load performance issues due to Chrome extensions, option - Desktop
## 2. Tool: platform.elevin.cloud

![image](https://user-images.githubusercontent.com/60215258/123259635-fc9a2000-d4f4-11eb-8e76-9815e9add817.png)

![Screenshot_1](https://user-images.githubusercontent.com/60215258/123257773-e4290600-d4f2-11eb-869d-a97ef518fe94.png)

## 3. WAVE web accessibility evaluation tool

- 15 isses were found that are worth fixing in order to improve page accessibility 
- *e.g. document language is not identified - the lang attribute and a valid ISO-639-1 two letter language code to be added (here: html lang="en")*


![image1](https://user-images.githubusercontent.com/60215258/123296997-704d2480-d517-11eb-9244-2b36bf15ced0.png)

- Below  there are images showing the remaining deficiencies worth checking

![image2](https://user-images.githubusercontent.com/60215258/123297162-9bd00f00-d517-11eb-828f-eac5f5c88e31.png)
![image3](https://user-images.githubusercontent.com/60215258/123297536-f0738a00-d517-11eb-83db-ea7b7a584842.png)
![image4](https://user-images.githubusercontent.com/60215258/123298630-fd44ad80-d518-11eb-85cc-31164663ce0c.png)
---

To find out more (the code with listed issues/how to fix it/why it matters/what it means/ the algorithms/ standards & guidelines): 
- download the extension: Wave Evaluation Tool (for [Chrome](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) & Firefox) 
- run the extention on https://www.netguru.com/
## 4. Manual accessibility testing  
Main Page: 
-  Page Title: Web page has a descriptive title
- Site is keyboard accessible - wherever possible, content can be operated through a keyboard 
- 11 out of 12 images contain no ALT attribute (when using the img element, specify a short text alternative with the alt attribute)
- Unnecessary duplication occur -  adjacent links for same resource found:
Line 7, column 17, a element, HREF = "javascript:void(0);"
Line 10, column 17, a element, HREF = "javascript:void(0);"
- no information conveyed by prerecorded audio-only and prerecorded video-only content available to all users


