Thinkful HW Assignment - Pete Thinkful Webpage

Lesson 10

Build your portfolio web page
Overview
Over the course of this module, you've learned new HTML and CSS skills and used those skills in silos. Now you will use them all at once! This is going to be fun—you'll get to create your first of many websites.

In this portfolio project, you will write the HTML and CSS for a basic one-page website. This portfolio will give you the chance to showcase your new technical expertise in HTML and CSS.

This is just the first stepping stone on a long and exciting journey. You're still learning the basics of web development, and you have many more skills to develop. But this project provides an important opportunity for you to practice—and celebrate—what you've learned so far. This project will mark your progress as a web developer.

Project description
You're a web developer at the Thinkful Design Agency.

Pete Thinkful, an artist, has approached your team to help him build a web portfolio to serve as his online business card. The designer on your team provided the following user interface mockup.

Pete Thinkful's user interface mockup.
In this project, you will translate the design above into HTML and CSS code.

Note: For this project, you don't need to worry about the mobile layout. Just focus on the desktop view of the web page.

Setup
You can complete the project using the Replit below:


You should create a fork (that is, your own personal copy) of the starter code above. Creating a fork allows you to make changes to the code and save your progress in Replit as you work.

Existing files
The table below describes the contents of the Replit starter code:

File
Description
images/
A folder containing all the images used for the design. You won't have to edit anything inside this folder.
index.html
The starter HTML file. You will need to add your solution to this file.
style.css
The starter CSS file. You will need to add your solution to this file.
Go ahead and spend some time familiarizing yourself with the provided files.

Tasks
Developers typically create the skeleton of a web page first using HTML before styling the page with CSS. That way, you can focus on one problem at a time—first on establishing the information hierarchy on the page, and then on styling the content in a visually appealing way.

Your first task is to complete the HTML code for Pete's portfolio page. Then you will style the page with CSS. Next, you will use a HTML validator to verify the HTML page for syntax errors. Finally, you will display your work on GitHub.io.

Note: You aren't expected to match the design pixel by pixel, as long as your final product satisfies the requirements detailed below.

Complete the HTML code
The page scaffolding, including the header, footer, and horizontal rule elements, has already been set up for you, so you will need to write HTML to complete only the About, Portfolio, and Contact sections. In your solution, strive to use semantic containers, such as article, section, footer, header, and nav, to structure different parts of the page.

Note: Don't change the order of any content. Rather, display all content in the same order as it appears in the design mock.

Step 1: Write the HTML code for the header
You should use the header and nav semantic containers to create the header and navigation bar, respectively. Each navigation link (About, Portfolio, and Contact) should be an anchor element.

Step 2: Write the HTML code for the About section
If you'd like, you may use the text below:

About
Hi! I'm Pete Thinkful
I'm an artist living in Denver, Colorado.
As an artist, I'm interested in:
- Producing abstract art
- Creating street graffiti art
- Connecting with like-minded artists
Please feel free to take a look at my website and feel free to contact me.

Pete's Background
After graduating college, I became an art teacher and worked with
beginners and professionals. I love art and my works have been
featured in major art galleries across the globe.

If you're looking to hire an artist or if you're an artist looking
for a collaborator for your next project, please reach out! I'm so
excited to work with other artists to create new art.
Other requirements
Pete's image can be found in the images/ folder, titled pete-thinkful.png. You should set the alt text of the image element to Pete Thinkful.

Pressing the About navigation link should take the site visitor to the About section.

In the "Please feel free to take a look at my website and feel free to contact me." text, the "contact me" part should be a link that, when pressed, takes the site visitor to the Contact section of the page.

"Producing abstract art," "Creating street graffiti art," and "Connecting with like-minded artists" should be displayed as a bulleted list.

Step 3: Write the HTML code for the Portfolio section
If you'd like, you may use the text below:

Portfolio

Abstract Red
Vaporware wayfarers heirloom neutra disrupt. Activated charcoal
waistcoat scenester hell of.

Spiral Zany
Sriracha portland taxidermy cronut messenger bag, vegan
distillery. Vaporware kickstarter air plant mumblecore food truck.

Melted Rainbow
Edison bulb single-origin coffee snackwave, actually ennui
locavore shabby chic forage.
Other requirements
All the images can be found in the /images folder. You should set the alt text on each image element to an appropriate value. (Using the project name is fine.)

Pressing the Portfolio navigation link should take the site visitor to the Portfolio section.

Step 4: Write the HTML code for the Contact section
If you'd like, you may use the text below:

Contact
I'd love to hear from you! Please feel free to contact or follow me:
- LinkedIn
- Instagram
- Pinterest
Other requirements
Pressing the Contact navigation link should take the site visitor to the Contact section.

"LinkedIn," "Instagram," and "Pinterest" should be displayed as a numbered list of anchor elements. The href values may be left empty.

Step 5: Complete the CSS code
Now that you have completed the HTML for the page, it's time to style the page, section by section. Some styling has already been added to the CSS file, which you may alter if necessary. You will implement the remainder of the CSS to achieve the design shown in the mock, as detailed below.

The styling requirements for the About section are as follows:

The About, Hi! I'm Pete Thinkful, and Pete's Background headings, as well as Pete's image, should be horizontally centered on the page.

The About heading should use a larger font size than the Hi! I'm Pete Thinkful and Pete's Background subheadings.

Pete's image should be completely round and have a border that is 2px wide with a color of #003049. To achieve this, you may add the necessary CSS rules to the .image-circle class that's already provided for you.

The styling requirements for the Portfolio section are as follows:

The Portfolio heading, project name (such as Abstract Red), and project image should be horizontally centered on the page.

The Portfolio heading should use a larger font size than the project names.

The styling requirements for the Contact section are as follows:

The Contact heading should be horizontally centered on the page.

Other styling requirements:

The background color of the page should be set to #eae2b7.

The contents of the header and the footer should be horizontally centered on the page.

Anchor tags should have a color of #d62828. On hover, they should change their color to #f77f00.

Note: You aren't required to match the spacing in the design mock. You also aren't expected to match the design pixel by pixel, as long as the styling requirements detailed above are satisfied.

Step 6: Validate the HTML
Now, you will use an HTML validator to validate your web page. An HTML validator is a quality-assurance tool that can detect common syntax errors such as extra spaces, open tags, or missing quotation marks. These syntax errors could cause a page to render correctly in one browser but not in another. You can use an HTML validator to automatically verify your HTML page for syntax errors. You can then correct any coding mistakes identified by the validator program.

There are many web-based HTML validator programs available for free. One example is the W3C Markup Validation Service.

The W3C Markup Validation Service home page.
This service offers various ways to validate a document: you can provide the URI where your document is hosted, upload a file, or directly paste the HTML input into the provided text area.

Do this
Validate by direct input
Using the W3C Markup Validation Service, select the Validate by Direct Input tab and insert <div> into the text area, like this:

<div> in the text area.
Then press the Check button to start the validation process. When the validation is complete, you'll be taken to a page that displays a list of syntax errors that the validator program found for the given HTML input. It will look something like this:

List of syntax errors found.
Note that the syntax errors are tagged with either a Warning or Error label. Syntax errors tagged with the Warning label are unlikely to cause issues for your page. In contrast, errors tagged with the Error label are more serious and likely to affect how your page renders in different browsers if they aren't handled properly.

Go ahead and fix all the issues identified by the validator. Paste the following code snippet into the text area and press Check again.

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Document</title>
</head>
<body>
  <div>
  </div>
</body>
</html>
HTML validator displaying the following message: "Document checking completed. No errors or warnings to show."
This time, because the HTML input is valid, the validator returns the following message: "Document checking completed. No errors or warnings to show."

Tip
Before submitting, make sure to validate your HTML file using an HTML validator. Then address any issues identified by the validator to the best of your ability.

Step 7: Display the web page on GitHub.io
Now, you will display your work on GitHub.io so that Pete can view the finished product and provide feedback.

Go ahead and download your Replit project. To download your Replit, navigate to the Files tab, open the drop-down menu in the Files tab, and select the Download as zip option.

The Files drop-down in Replit.
Then create a new repo in GitHub, upload your project files, and commit your work. Finally, present your files as a live web project using GitHub.io.

One final note...
Remember, this is a graded lesson. That means that someone from the Thinkful team will review your work using the rubric provided below. Here are the specifics: 

Grading rubric: The graders will use the questions in the following rubric when grading your work. Unless otherwise indicated, all questions use a yes-no framework, and all answers must be Yes for you to pass. 

Additional feedback: Graders will also use the rubric to provide you with feedback. This feedback does not affect whether you pass or fail; it is there to help you revise your work or improve upon it. 

Keep this information on hand as you work, and good luck! 

Grading rubric
Question 1

Does the student's desktop design meet all of the HTML requirements outlined in the lesson?

Yes
No
Question 2

Does the student’s desktop design meet all of the CSS requirements outlined in the lesson?

Yes
No
Question 3

Is all of the content displayed in the same order as it appears in the design mockup?

Yes
No
Question 4

Did the student submit a GitHub.com repo URL?

Yes
No
Question 5

Did the student submit a GitHub.io website address?

Yes
No
Question 6

Identify and explain at least two things the student did well.

Your grader may leave additional feedback on your submission once it's reviewed.
Question 7

Required: If the student didn't pass, provide guidance on changes they need to make to pass this assessment.

Your grader may leave additional feedback on your submission once it's reviewed.
Question 8

Add any optional changes, ideas, and opportunities for improvement.

Your grader may leave additional feedback on your submission once it's reviewed.
Graded Assignment
Portfolio project: Submit your work
When you're ready, use the box below to submit the following links for the Thinkful team to review.

The GitHub.com repo URL
The GitHub.io website address
If you need a refresher on how to do this, review the GitHub lessons from the Introduction to HTML and CSS fundamentals module.

Note that links submitted via Replit will not be accepted and will require a resubmission of the correct links listed above.

