
# Lab 04: CSS

## Introduction:
Students have learned advanced concepts of HTML and CSS which can be applied to design professional web pages. In this lab, student will practically design a web page using advanced HTML and CSS concepts. 

## Lab Objectives:
The objective of this lab is to help students in designing layout of a web page using divisions and CSS.  Students will apply different HTML tags and styling concepts they have learned in the lectures to design the layout of a web page.

## Tools:
Dreamweaver, notepad, browser.
## Helping Material:
* Lecture slides.
* W3Schools: https://www.w3schools.com/html/default.asp 
* Plenty of DIV examples: http://www.mobilefish.com/tutorials/css/css_quickguide_div_examples_containers.html 

 


### Lab Task 1:
 
In your previous lab, you have designed a website using tables which is similar to BBC’s website. Tables can be used to define the structure of a website; however, they are less flexible and difficult to handle complex structures. The layout of the BBC’s website can be designed using divisions (DIVs). A screenshot of the website is shown below:


#### Your Task:
Design a web page which has similar layout as shown in the above screenshots. Your layout must be based on DIVs (no tables). You are encouraged to use either internal CSS (using <style> tag) or external CSS (creating a file with .css extension and linking it in the <head> section using <link> tag). An example CSS file is uploaded along with this assignment. You are also encouraged to use different HTML tags and CSS styles you learned so far to beautify the solution. 
Hints
1.	Feel free to browse BBC’s website and look into its page source to see how the layout is designed.
2.	You can change the color scheme as per your choice. 
3.	BBC’s website has a menu (More) and a search bar. You can skip both in your layout.
4.	You are encouraged to use most of the HTML tags and CSS styles you have learned so far or even new tags, which you can learn from W3Schools.
5.	Make good use of HTML colors, fonts, font-family, font-sizes and other styles for the look and feel of the web page.
6.	Make sure to test your website with different resolutions by changing the resolution of your screen.

#### CODE:
```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
     <link rel="stylesheet" href="style.css">
    <title>BBC Home</title>
  </head>
  <body>
    <div class="container">
      <div class="nav-bar">
        <div class="left-side">
          <div class="link">
              <a href="">  <img class="bbc"  src="./b.gif" alt=""> </a>
          </div>
          <div class="link">
            <a href="">  <img class="sign"  src="./sign1.png" alt=""> </a>
          </div>
          <div class="link">
            <a href="">Home</a>
          </div>
          <div class="link">
            <a href="">News</a>
          </div>
          <div class="link">
            <a href="">Sport</a>
          </div>
          <div class="link">
            <a href="">Reel</a>
          </div>
          <div class="link">
            <a href="">Worklife</a>
          </div>
          </div>
        </div>
      </div>
    </div>
<div class="image-first">
  <img  src="./adv.png" alt="">
</div>
<div class="int">
  <div class="wb">
    <b><h3>  Welcome to BBC.com</h3></b>
  </div>
<div class="dat">
  <h3 id="dt">Saturday,20 March</h3>
</div>
</div>
<br>
<br><br>
<div class="five-images">
  <div class="image-first">
<img  src="./va.png" alt="">
  </div>
<div class="sec-img">
  <div class="sc">
    <img src="./c.png" alt="">
  </div>
<div class="sc">
  <img src="./d.png" alt="">
</div>
</div>
<div class="thr-img">
  <div class="tr" style="border-bottom:2px solid white;padding-right:2px">
    <img class=thrid src="./e.png" alt="">
  </div>
  <div class="th">
    <img src="./f.png" alt="">
  </div>
</div>
</div>
<div class="News">
  <h2><mark>|</mark> News</h2>
</div>

  <div class="ne">
    <div class="g-img">
      <a href="#"><img src="./i.png" alt=""></a>
    </div>
    <div class="h-img">
      <a href="#"><img src="./h.png" alt=""></a>
    </div>
    <div class="i-img">
        <a href="#"><img src="./q.png" alt=""></a>
    </div>

  </div>
  <div class="Sports">
    <h2><mark>|</mark> Sports</h2>
  </div>
<div class="sp">
  <div class="j-img">
    <a href="#"><img src="./j.png" alt=""></a>
  </div>
  <div class="k-img">
    <a href="#"><img src="./k.png" alt=""></a>
  </div>
  <div class="l-img">
    <a href="#"><img src="./l.png" alt=""></a>
  </div>
</div>
<br><br>
<div class="weather">
  <img src="./m.png" alt="">
</div>
<br><br>
<div class="Asia News">
  <h2><mark>|</mark>Asia News</h2>
</div>
<div class="an">
<div class="n-img">
  <a href="#"><img src="./n.png" alt=""></a>
</div>
<div class="o-img">
  <a href="#"><img src="./p.png" alt=""></a>
</div>
<div class="p-img">
  <a href="#"><img src="./i.png" alt=""></a>
</div>
<div class="q-img">
  <a href="#"><img src="./q.png" alt=""></a>
</div>
</div>

<div class="picks">
  <div class="Editors-Pick">
    <h2><mark>|</mark>Editor's Pick</h2>
    </div>
  <div class="images">
    <div class="r-y">
      <img src="./r.png" alt="">
      <div class="t-v">
        <div class="t-img">
          <img src="./v.png" alt="">
        </div>
        <div class="u-img">
          <img src="./u.png" alt="">
        </div>
        <div class="v-img">
          <img src="./i.png" alt="">
        </div>
      </div>
      <div class="t-v">
        <div class="t-img">
          <img src="./w.png" alt="">
        </div>
        <div class="u-img">
          <img src="./x.png" alt="">
        </div>
        <div class="v-img">
          <img src="./w.png" alt="">
        </div>
      </div>
    </div>
    <div class="y-img">
      <img src="./s.png" alt="">
    </div>
  </div>
</div>
<div class="video">
  <div class="Editors-Pick">
    <h2><mark>|</mark>Feature video</h2>
  </div>
  <div class="video">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1"></iframe>
  </div>
</div>
<div class="image-first">
  <img  src="./last.png" alt="">
</div>

  </body>
</html>

```
![alt text](https://i.ibb.co/MgxvHjk/33.png)
