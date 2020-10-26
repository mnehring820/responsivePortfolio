# responsivePortfolio

## Description 

For this project I am creating a live website to host my portfolio. The site must have a consistent navbar on three separate pages. The site consists of 3 html pages that I have primarily used Bootstrap in order to style. The site will also be responsive to different sized screens meaning it will be accessible on desktops and smartphones. Along with components used from Bootstrap, I also make use of it's column and row structure. 

## Installation

I started this project by first adding a generic navbar from Bootstrap to the body of my index.html file. The nav-bar I selected included links so the placeholders had to be replaced to path to my portfolio and contact pages. I also was able to change the nav-bar to habe links on the right by changing the list class to .ml-auto. To finish my home page I utilized Bootstrap's column and row system in order to create a row with 2 columns, the second comlumn having 2 sub rows. 

The same navbar was copied from my index page to my portfolio page. I then changed the code so the links worked properly and displayed the Portfolio as being the active page. The portfolio page makes use of a row for the title of the page but the rest of the page uses card components from Bootstrap to hold pictures and information for my portfolio. In order to link pictures I saved them to an assets folder within the repository. 

I formatted the contact page the same as the portfolio up through the h1 tag, fixed the links for the navbar, and displayed contact as the active page. I used the form components from bootstrap and personalized the classes and labels for my page. I also made the form for the message larger by adding rows to the textarea. 

To finish up this project I added a CSS page to add background color and make my image responsive. 

## Usage

The website is very simple. The homepage contains a phot, some information, and two links at the top. The links are labelled to take the user to my portfolio page or contact page. If the user goes to the portfolio page there are three cards that each contain a photo and some text. Each of these cards contains an external link that will take them to my projects. On the contact page there are three forms labelled for the user to enter their name, email, and a message. The boxes can all be typed into by the user. There is also a submit button at the bottom of the form. 

## Credits

Resources used to make this project 
* https://getbootstrap.com/docs/4.5/components/alerts/
* https://validator.w3.org/ 
* https://stackoverflow.com/questions/41513463/bootstrap-4-align-navbar-items-to-the-right   

## License

MIT License

Copyright (c) [2020] [Matthew Nehring]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.