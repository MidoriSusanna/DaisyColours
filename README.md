<h1>DaisyColours</h1>
<br>
<p> DaisyColours is a website of an art school providing art courses for adult, kids and families. It offers also a course dedicated to improving your social media presence online as an artist and/or preparing your digital portfolio. The target audience of this website is divided in three sectors:
1. Adults who wish to practice the art in an amateur way
2. Kids inetersted in playing with other kids of the same age through art
3. Families interested in bonding with their kids through art and playing
4. Adult amateurs artist interested in creating a social media presence and kickstarting their small business
<br>
The websiete is dedicated to private costumers (B2C) and the aim is providing information about the school courses in a simple and effective way. 
</p>

<h1>Features </h1>
The website consists in 3 essential pages and the user can easily navigate through them via the navigation bar and the clickable links in the homepage. 
The homepage provides an initial idea of the art school, the core principles of it and a preview of the courses. 
The course page provides useful information about the content of the courses, start dates, time, costs.
The contact us page is a useful tool for the user to get quickly in touch with the school and express interest in a course. The enolment process ideally takes place outside the website and via email correspondence with the school, to privilage direct contact between customers and business and to provide a tailor-made service. Also, to be able to manage course availability issues in a simplier way for a small business.

<h2>Homepage</h2>
<h2>Navigation bar</h2>
<p>Featured on all three pages, the navigation bar includes the Logo, Home page, Courses page and Contact us page and is identical in each page to allow easy navigation. This section will allow the user to easily navigate from page to page without having to revert back to the previous page via the ‘back’ button. By hovering onto the buttons, the colour change to provide the clear idea of interactivity. </p>
<h2>Hero images with slider - Landing page</h2>
<p>The first impression of the customer needs to be the idea of what the school is in essential. The slider allows the user to have a simple visual idea of what the school provides. It comes before the core principles to impress the customer visually and catch their attention.</p>
<h2>Core Principles</h2>
<p>Brief explanation of the core principles of the school, simple section to provide a general idea of what the school does.</p>
<h2>Course Preview</h2>
<p>The Course preview section links the homepage to the course section, giving the possibility to the use of focusing on the specific course they are looking for. By hovering over the image, an overlay is applied to make the title of the course readable. </p>
<h2>Footer</h2>
<p>Featured on all three pages, the footer section includes the clickable social media icons of the school.</p>

<h2>Course Page</h2>
<h2>Sections and summary element</h2>
<p>Each section is related to a specific course. There is a brief description and the possibility of getting to know more information through the details and summary element. This way the information is delivered is a structured way to the user and it is easily accessible due to the division in sections and summaries.</p>

<h2>Contact us</h2>
<h2>Form</h2>
<p>The form is an essential tool to connect with the business. It guides the user to their course of interest and trough the booking process. The form is structures with required input boxes for name, surname and address, to allow the company saving these information for future contacts/campaigns. With the radio buttons it is required to specify the course of interest, to focus the attention on a specific course. The textarea element is the space where the user can add a specific enquiry. The checkboks is to make sure the user is aware of the privacy policy of the company and collection of data, it is therefore a required box to tick.</p>

<h1>Testing</h1>
<p>Some of my initial issues were related to the use of margins and paddings, I was able to solve those issues using them in the correct way and in the right context. Here are some examples of the errors showing while using those properties in an incorrect way or exchanging them:
<image src="./assets/images/margin-padding.png">
<image src="./assets/images/margin-padding3.png">
<image src="./assets/images/margin-padding2.png">
</p>
<p>Another issue was the use of the properties float and clear for the layout of the "Courses" page. I have tried many times to reset the properties but it seemed like this was not the best solution for the page. Those were some of the layout problems I encountered trying to use float and clear property, the text wraps around the pictures and it is very tricky to work with the div elements:
<image src="./assets/images/float property1.png">
<image src="./assets/images/float property2.png">
The flexbox allowed me to treat the image and paragraph section as a different item then the summary section and work out the position between each other. To do this I used the property wrap and display: flex for the container of the two items. 
</p>
<p>Another issue is related to the slider. 
.slider {
    display: flex;
    aspect-ratio: 16/9 !important;
    width: 100%;
    height: 70vh;
    overflow-x: auto;
    scroll-snap-type: mandatory;
    scroll-behavior: smooth;
}
.slider img {
    width: 100%;
    height: auto;
    flex: 1 0 100%;
    scroll-snap-align: start;
    object-fit: cover;
}
The use of aspect-ration: 16/9 doesn't work on Safari. I tried to fix the issue adding these two new properties width: 100%; height: 70vh; <br>
The slider now seems to be less responsive. 
</p>
<h1>Deployment</h1>

<h1>Credits</h1>
<h2>Design and colours</h2>
<p>Colour palette: https://colorhunt.co <br>
Project of wireframe and logo through Adobe Indesign <br>
<image src="./assets/images/wireframe1.png">
<image src="./assets/images/wireframe2.jpg">
<image src="./assets/images/wireframe3.jpg">
Icons: https://fontawesome.com <br>
Fonts: https://fonts.google.com</p>
<h2>Contents</h2>
<p>Text by me and corrected (English mistakes, vocabulary) with DeepL and ChatGPT. <br>
Pictures from those open souce websites: <br>
https://unsplash.com <br>
https://www.pexels.com 
</p>
<h2>Code and Layout</h2>
<p>
Style navigation bar: https://www.youtube.com/watch?v=5Ym3ZkRYfN0 <br>
Slider with only HTML and CSS: https://www.youtube.com/watch?v=McPdzhLRzCg <br>
Overlay: https://www.youtube.com/watch?v=exb2ab72Xhs&t=3s <br>
Use of the flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/ <br>
Use of grids: https://www.w3schools.com/css/css_grid.asp <br>
The student support has been incredibly helpful. <br>
Some references are from the Essential Love Running previous Project. <br>
</p>


