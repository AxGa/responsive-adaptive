# Responsive-Adaptive
A guide about the debate Responsive vs Adaptive web-design 

![Image of Content is like Water](https://cdn-images-1.medium.com/max/2000/1*kd07zXQBI3s0uPm4msF21w.jpeg)


## Definitions
There are three main techniques for implementing a website that can handle view screens of all types and sizes.

1. **Responsive web design:** Serves the same HTML code on the same URL regardless of the users’ device (desktop, tablet, mobile, non-visual browser), but can render the display differently (i.e., “respond”) based on the screen size. Responsive design is Google’s recommended design pattern.

2. **Adaptive web design:** Uses the same URL regardless of device, but generates a different version of HTML for different device types based on what the server knows about the user’s browser.

3. **Separate URLs:** Serves different code to each device, and on separate URLs. This configuration tries to detect the users’ device, then redirects to the appropriate page using HTTP redirects along with the Vary HTTP header.


## Pros & Cons

1. **Responsive web design**

Pros|Cons
----|----
:thumbsup: Is Google’s recommended design pattern|:thumbsdown: More coding and testing in order to ensure that the site fits each and every screen that access it
:thumbsup: Requires less engineering time to maintain multiple pages for the same content| :thumbsdown: More loading time as everything from the desktop version is downloaded, even if it’s not used in the mobile version


2. **Adaptive web design**

Pros|Cons
----|----
:thumbsup: Is faster as the browser downloads the assets needed for the specific screen size|:thumbsdown: You need to create many html templates for each device that's very time consuming for both development and maintanance 
:thumbsup: You can create a completely different user journey for different devices| :thumbsdown: For adaptive web design you need to detect user-agents (sometimes called user-agent “sniffing”) which is generally an error-prone technique