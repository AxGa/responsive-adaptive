# Responsive-Adaptive
A guide about the debate Responsive vs Adaptive web-design 

![Image of Content is like Water](https://cdn-images-1.medium.com/max/2000/1*kd07zXQBI3s0uPm4msF21w.jpeg)

<br></br>
## Definitions
There are three main techniques for implementing a website that can handle view screens of all types and sizes.

1. **Responsive web design:** Serves the same HTML code on the same URL regardless of the users’ device (desktop, tablet, mobile, non-visual browser), but can render the display differently (i.e., “respond”) based on the screen size. Responsive design is Google’s recommended design pattern.

2. **Adaptive web design:** Uses the same URL regardless of device, but generates a different version of HTML for different device types based on what the server knows about the user’s browser.

3. **Separate URLs:** Serves different code to each device, and on separate URLs. This configuration tries to detect the users’ device, then redirects to the appropriate page using HTTP redirects along with the Vary HTTP header.

<br></br>
## Pros & Cons


1. **Responsive web design**

Pros :thumbsup:                                                               | Cons :thumbsdown:
------------------------------------------------------------------------------|-----------------------------------------------------------------------------
Is Google’s recommended design pattern                                        | More coding and testing in order to ensure that the site fits each and every screen that access it
Requires less engineering time to maintain multiple pages for the same content| More loading time as everything from the desktop version is downloaded, even if it’s not used in the mobile version


<br></br>
2. **Adaptive web design**

Pros :thumbsup:                                                                  | Cons :thumbsdown:
---------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------
Is faster as the browser downloads the assets needed for the specific screen size| You need to create many html templates for each device that's very time consuming for both development and maintanance 
You can create a completely different user journey for different devices         | For adaptive web design you need to detect user-agents (sometimes called user-agent “sniffing”) which is generally an error-prone technique


<br></br>
3. **Separate URLs**

Pros :thumbsup:                                                                    | Cons :thumbsdown:
-----------------------------------------------------------------------------------|-----------------------------------------------------
Better user experience, the website being specifically optimized for mobile devices| Higher costs in terms of implementation, maintenance
Faster page load times-frames                                                      | More challenges with user redirecting and cross-linking between the two platforms

<br></br>
## Basic responsive elements explained in GIFs
![ResponsiveVsAdaptive](https://s3.eu-central-1.amazonaws.com/displaycase.akylleez/infogr8/responsive-gifs/3038367-inline-i-1-9-gifs-that-explain-responsive-design-brilliantly-01responsive-vs-adaptive-copy+(1).gif)
###### 1. Responsive designs fluidly expand, whereas adaptive designs hitch as you expand a browser or viewport.

<br></br>
![RelativeStaticUnits](https://s3.eu-central-1.amazonaws.com/displaycase.akylleez/infogr8/responsive-gifs/3038367-inline-i-2-9-gifs-that-explain-responsive-design-brilliantly-02relative-units-vs-static-units-1-copy.gif)
###### 2. Use relative units, like percent of the screen, instead of static units like pixels.

<br></br>
![Breakpoints](https://s3.eu-central-1.amazonaws.com/displaycase.akylleez/infogr8/responsive-gifs/3038367-inline-i-3-9-gifs-that-explain-responsive-design-brilliantly-03with-breakpoints-vs-without-breakpoints-1-co.gif)
###### 3. Breakpoints allow the layout to change at predefined points, i.e. having three columns on a desktop, but only one column on a mobile device.

<br></br>
![Nesting](https://s3.eu-central-1.amazonaws.com/displaycase.akylleez/infogr8/responsive-gifs/3038367-inline-i-5-9-gifs-that-explain-responsive-design-brilliantly-05nested-vs-not-nested-1-copy.gif)
###### 4. Nest elements to larger containers to adapt to a shrinking or expanding screen as one, instead of individually.

<br></br>
![Max Width](https://s3.eu-central-1.amazonaws.com/displaycase.akylleez/infogr8/responsive-gifs/3038367-inline-i-7-9-gifs-that-explain-responsive-design-brilliantly-07max-width-vx-no-max-width-1-copy.gif)
###### 5. Sometimes it’s great that content takes up the whole width of a screen, like on a mobile device, but having the same content stretching to the whole width of your TV screen often makes less sense.
