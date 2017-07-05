1. What did you learn yesterday/this week?
  I took a course on an introduction to Ruby and learned that it is very similar to JavaScript and pretty easy to pick up.

2. What excites or interests you about coding?
  I get excited when I find a evasive bug or solve a challenging problem. I actually love it when the code doesn't work as expected, for me, finding the problem is the best part.

3. What is a recent technical challenge you experienced and how did you solve it?
  I was writing some unit tests with Mocha/Chai for some data structures written in ES5, one test was consistently failing even though the code seemed to function properly. After writing in several console.logs I realized that one of the functions had a closure and when the test would run it would lose it's 'this' binding. To solve this, I created a local variable inside the outer function and assigned 'this' to it. Then inside the closure I used the local variable instead of 'this'.

4. What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
  For UI considerations, you need to be careful to use technologies that will look the same across all browsers and screen sizes.
  For security, you need to make sure you don't store any user information on the server and you need to protect your routes from being hacked.
  For performance, be mindful of time complexities when writing functions and methods, if it is a large application it also might be best to put the script tags at the bottom of the html so the users can at least look at the static page while the scripts are loading.
  For SEO - there are several tools and subscriptions you can sign up for, but in general terms, throw a lot of keywords on your static page or in your url, that way when someone searches for them it comes up further in the results.
  For maintainability - write clean code with good comments explaining what each part does
  For technology considerations - make a good educated decision on what technology you are going to use. Don't just use what you know or want to learn. Each technology has it's pros and cons for each application. Do a lot of research before deciding on your stack.

5. Talk about your preferred development environment.
    The environment I am most familiar with is Mac OS, Sublime Text, and Bash. I easily adapt to other environments as needed, each application demands a little different set up.

6. Which version control systems are you familiar with?
    Git

7. Can you describe your workflow when you create a web page?
    1. Think through all the different views and functionality the web page will need. Take notes
    2. Draw up two diagrams using moqups.com or google's draw.io - one for the front end and one for the back
    3. Write up the different routes that will be needed
    4. Decide what the different stages will be and write them down
    5. Divide out tasks using waffle.io
    6. Start out coding the basic skeleton
    7. Finish MVP and add one feature 100% at a time

8. If you have 5 different stylesheets, how would you best integrate them into the site?
    If each stylesheet was for a different functionality, I would probably keep them separate, unless they were small files, then I would combine them.

9. Can you describe the difference between progressive enhancement and graceful degradation?
    Progressive enhancement is where you make small changes to the style and/or performance of your site that users with advanced browsers will be able to enjoy, but won't break the site for users with older browsers.
    Graceful degradation is where you make allowances for users with older browsers to your already functioning site so it doesn't break for them.

10. How would you optimize a website's assets/resources?
    A few different options are to use a CDN instead of installing the node module, use Grunt or a similar technology to reduce the size of your files, minify or uglify all your files, or at least the CSS.

11. How many resources will a browser download from a given domain at a time?
    Depends on the browser, between 2 and 8

  * What are the exceptions?


12. Name 3 ways to decrease page load (perceived or actual load time).
    1. Use CDNs
    2. Minify/uglify/concatenate your files
    3. Load scripts at the bottom of the HTML page

13. If you jumped on a project and they used tabs and you used spaces, what would you do?
    Start using tabs, if most of the code is written one way, and there isn't a very good reason to change, it is better to be consistent

14. Describe how you would create a simple slideshow page.
    Create an array of images and loop through them with a set timeout function

15. If you could master one technology this year, what would it be?
    Java or C++

16. Explain the importance of standards and standards bodies.


17. What is Flash of Unstyled Content? How do you avoid FOUC?
    FOUC is when the webpage loads before the styling does and what the user sees resembles a raw HTML page.
    There are a few options to avoid FOUC:
    First and most important to to always link the stylesheet in the head
    Second, you can hide the content of your web page until the style sheet has loaded
    Third, make sure that all scripts are at the bottom of the HTML page so the user doesn't need to wait until they are loaded


18. Explain what ARIA and screenreaders are, and how to make a website accessible.
    Accessible Rich Internet Applications is a way to make web content and applications available to users with disabilities. A screenreader is a technology that visually challenged people use to read the screen to them. There are widgets and libraries you can install in your application that will make your web page more ARIA friendly.

19. Explain some of the pros and cons for CSS animations versus JavaScript animations.
    Creating animations with CSS is simpler and usually better for simpler animations. It is hard to maintain state with CSS and difficult to control more complex animations.
    Creating animations with JavaScript allows the developer more control over their animations and easier state maintainability. JavaScript animations are more challenging to write.
    CSS animation is declarative - you specify what you want to happen.
    JavaScript animation is imperative - you specify how you want the animation to happen.

20. What does CORS stand for and what issue does it address?
    Cross Origin Resource Sharing - used to avoid the browsers same-origin policy. A same-origin policy prevents requests for resources to domains other than the domain it is on to load. A CORS policy added in your code will allow you to use outside resources in your application.
