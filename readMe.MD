# 01_Code_Refactor_NN
BootCamp Homework - 02 Advanced CSS: Portfolio

## The Challenge
Coding professionals across the industry, including data scientists, web developers, and software engineers, need coding portfolios. 
A coding portfolio is as essential to the job search process as a professional resume. 
Many employers expect coding portfolios from candidates and may actively search for them during the hiring process.
Portfolios demonstrate how candidates think and how well they can code. 
Coding portfolios also provide insight into a coder's creativity and attention to detail.
We're going to design a portfolio using our current knowledge of HTML and CSS to  deploy a web application like the one below. 
![](./develop/assets/images/screenshot.png)

## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

## Acceptance Criteria

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
``` 

## The Process
To satisfy our client's needs, we had to:
- Identify a proper semantic structure for the HTML and CSS file
- Provide descriptive comments for each section of the HTML and CSS file
- Modify the HTML and CSS file in a way that would fit a proper semantic structure
- Combine multiple rules into one rule

Specific modifications to the HTML file

```
Changed title to company's name for Page's title
Changed div to header for Page's Header
Changed div to main for Page's Main Content
Changed div to aside for Page's Additional Content
Changed div to footer for Page's Footer
Include alt properties with related description for each image 
Added an id for search-engine-optimization so that the web application would scroll down when users click it
```

Specific modifications to the CSS file

```
Added structural comment for each section of the HTML file
Rearrange some rules to fit a proper semantic structure
Simplified multiple rules into one rule:

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

## The Result
After refractoring the existing code, we were able to provide an accessible, efficient, and stuctured project for our client. 

## Submission
This project was uploaded to GitHub at the following respository link:
[https://github.com/nhanng19/challenge01](https://github.com/nhanng19/challenge01)

Depolyed Web Application Link:
[https://nhanng19.github.io/challenge01/develop/index](https://nhanng19.github.io/challenge01/develop/index)