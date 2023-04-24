# Final Project

 GIT 215 Final Project

## Assignment Details

For the final, you are to design and develop two pages of a website for a restaurant called *Wok Asian Cuisine*. All of the content has been provided.

---

**Overview**

*The final project is your time to show off what you have **learned in this class**. This assignment instructions are broken into 6 parts:*

1. Home Page Requirements
2. Contact Page Requirements, *including a wireframe*
3. HTML Requirements for both pages
4. CSS Requirements
5. Testing Requirements
6. Submission Requirements

---

### 1. Home Page Requirements

You will find **home-page-option-1** and **home-page-option-2**.

Each option contains a wireframe and images. You are to **choose one option** that you prefer as a starting point for your index.html page. Match the placement of the content to the wireframe, but style it however you'd like. All colors, fonts, sizes, padding, margins, backgrounds, etc. are ultimately up to you! Be creative.

The images have already been cropped for each option. One set of images are square and one set of images are rectangular. All you will have to do is adjust the width and height of the images in your CSS to fit your web page design. To ensure your images don't get skewed, it is recommended that you define a width, and let the browser automatically calculate the height.

    .some-image {
        width: 300px;
        height: auto;
    }

#### CONTENT - index.html

Below is the content you are required to include on your home page (index.html). *Note:* This is not an all-inclusive list of all the HTML tags you will need. You will need to add classes, ids, sections, etc. in order to code and style this content semantically. **No divs except for those used exclusively for styling, like the grid container in module 6. It is not acceptable to use a div because you don't know how else to make an inline element into a block element or because you aren't sure which semantic container to use. If you're stuck, reach out!**

***Header:***<br />
**h1:** Wok Asian Cuisine

***Navigation:***<br />
**nav items:** Home, Our Menu, Order Now, Contact Us *(Use placeholder links # for the pages you aren't coding.)*

***Main:***<br />
**img:** Choose the appropriate images from the appropriate home-option-# folders<br />
**h2:** Modern Fusion Bar & Kitchen<br />
**Our Menu:** Use placeholder link<br />
**h3:** Cater With Us<br />
**paragraph:** We cater weddings, business lunches, dinners, and more. Call us to discuss how we can be a part of your next event.

***Section:***<br />
**image:** Choose the appropriate image from the appropriate home-option-# folders<br />
**h3:** Local Cuisine<br />
**paragraph:** We refuse to compromise on quality. Our fresh ingredients are local and we are committed to serving fresh cuisine.

***Section:***<br />
**image:** Choose the appropriate image from the appropriate home-option-# folders<br />
**h3:** Chef Ly<br />
**paragraph:** With 20 years of experience cooking in the finest restaurants, Chef Ly is committed to serving fresh food and unique experiences.

***Footer:***<br />
Wok Asian Cuisine<br />
Copyright &copy;[year] Wok - All Rights Reserved.<br />
This site is for educational purposes only.

---

### 2. Contact Page Requirements

It's your turn to create a wireframe to show how you are going to organize the content of the Contact Page. Only ***hand drawn wireframes*** are accepted so you can spend more time in your code, and less time learning a design program! Your hand drawn wireframe can be detailed or not detailed (with HTML tags or without HTML tags)--it's your preference.

Snap a picture once you are done and upload it to the assignment link. While the quality of the wireframe and image does not have to be perfect, it ***should be as good as you can make it*** as if you are presenting this to your client!

*Note:* Keep the placement of your header, navigation, and footer consistent with your home page. Just focus on what you want the rest of the contact page to look like.

#### CONTENT - contact.html

Below is the content you are **required** to include on your Contact page (contact.html).

*Note:* This is not an all-inclusive list of all the HTML tags you will need. You will need to add classes, ids, sections, etc. in order to code and style this content semantically.

***Header:***<br />
**h1:** Wok Asian Cuisine

***Navigation:***<br />
**nav items:** Home, Our Menu, Order Now, Contact Us *(use placeholder links for the pages you aren't coding.)*

***Main:***<br />
**h2:** Contact Us<br />
**paragraph:** Do you have dietary concerns? Questions about an upcoming event? Drop us a line, and we'll get back to you soon!<br />
**image:** Choose the appropriate image from the contact page folder.

***Form:***<br />
A contact form is required on your Contact page. Use [https://wp.zybooks.com/form-viewer.php](https://wp.zybooks.com/form-viewer.php) for the action attribute, and POST for the method attribute.

The contact form must include the following fields:
- Name* ***Required***
- Address
- City
- State (dropdown selection list of all 50 states -- You may Google 'html select list of US states' to save you the typing)
- Zip
- Phone* ***Required***
- Email* ***Required***
- Preferred Method of Contact? (must be radio buttons with "Email" and "Phone" as choices)
- Comments (must be a textarea)
- Submit button

***Footer:***<br />
Wok Asian Cuisine<br />
Copyright &copy;[Year] Wok - All Rights Reserved.
This site is for educational purposes only.

---

### 3. HTML Requirements for both pages

**Use this as a checklist to ensure you have the necessary elements in your final website.**

- Use the standard HTML format
- HTML pages named appropriately (index.html, contact.html)
- Include your name in a meta author tag in the head
- Include a favicon and make sure it displays
- Include a description meta tag in the head
- Include appropriate page title in head
- Use semantic HTML5 code. No divs except for those considered acceptable as mentioned above
- Keep the header, navigation, and footer consistent from page to page
- Link the h1 to the **index.html** *(include an anchor tag inside your h1)*
- Link your pages together within the navigation (index.html and contact.html)
- Use placeholder links for the pages we did not code (Menu and Order Now pages)
- Navigation must be coded as an unordered list
- Include hover styles and active page styles for the navigation (index.html and contact.html)
- Link a single external stylesheet to both pages
- Indent your code properly
- Include a form on your Contact page with the post method and using [https://wp.zybooks.com/form-viewer.php](https://wp.zybooks.com/form-viewer.php) for the action, and POST for the method
- Include the following in your form:
    - Name* **Required**
    - Address
    - City
    - State (a dropdown selection list of all 50 US states -- *Hint:* Google HTML select list of states)
    - Zip
    - Phone* **Required**
    - Email* **Required**
    - Preferred Method of Contact? *(radio buttons with "Email" and "Phone" as choices)*
    - Comments (must be a textarea)
    - Submit button
- Images include appropriate/descriptive alt attributes
- No inline or embedded styles in your HTML
- HTML validates

---

### 4. CSS Requirements

This is your chance to style your website however you want to--have fun with it! Use some color, spacing, padding, margins, etc.

Your pages should meet the following minimum style requirements:
- Only 1 stylesheet used
- Use a fixed width of 1280px
- Center the website in the browser window
- The layout of the website matches one of the wireframes
- Style the fonts, including font-family, size, and color. Provide **three** font-family choices
- Style visual cues for links. This should include a visual cue for the current/active page and a viual cue for hover.
- Ensure your site looks professional, meaning it should look like it is a real website. Do this by using good contrast and color palettes.
- Keep the look and feel of your site consistent from page to page
- CSS validates

---

### 5. Testing Requirements

- Validate your HTML and CSS documents
- View your files in one browser of your choice and take a screenshot of the Home Page. Save the screenshot with your last name and the browser name in the file name (i.e. breaux_firefox.jpg)
- View your files in another browser of your choice and take a screenshot of the Home Page. Save the screenshot with your last name and the browser name in the file name (i.e. breaux_chrome.jpg)
- Compare the two, preferably side-to-side in your monitor window. Are there any differences? Comment on whether or not you see any differences, what they are, whether it be color, fonts, rounded corners if used, etc. Save as a PDF named lastname_testing (i.e. breaux_testing.pdf)

---

### 6. Submission Requirements

- Zip your 'lastname_final' folder (which contains your contact page wireframe, HTML, CSS, images, and test files) and upload to Canvas
- If you would like, you may build this project in a repository and publish it to GitHub Pages so that you can add it to your portfolio

> #### 🚩 Warning: *<ins>No late submissions will be accepted!</ins>*

---

## Resources:

- [Background patterns](https://www.toptal.com/designers/subtlepatterns/)
- [Color Pickers](https://color.adobe.com/create/color-wheel)
- [GIT Coding Club Resources Page](https://gitcoding.club/resources/)

---

### Final Project Rubric
| Criteria | Pts |
| -------- | --- |
| General: Used the text and images provided for both the Home and Contact pages. (No partial points) | 5 pts |
| General: Chooses 1 wireframe option for the Home page and uses the text and images provided (no partial points) | 5 pts |
| General: Hand drawn wireframe for the Contact page (only hand drawn is accepted) | 5 pts |
| HTML: Code is semantic. Appropriate tags are used | 10 pts |
| HTML: Header, nav, and footer placement is consistent on both pages. (no partial points) | 6 pts |
| HTML: div id=wrapper used on both pages (no partial points) | 4 pts |
| HTML: h1 links to the index.html on both pages (no partial points) | 5 pts |
| HTML: Nav is coded as an unordered list, nav links are appropriate - index.html, menu.html, order.html, contact.html, and navigation works as expected. | 4 pts |
| HTML: One stylesheet is used and appropriately linked. (no partial points) | 4 pts |
| HTML: Code is properly indented | 5 pts |
| HTML: Divs are used appropriately, if used (no partial points) | 5 pts |
| HTML: Contact page form includes a post method and uses correct action (no partial) | 5 pts |
| HTML: Contact page form includes (1 pt ea. -1 pt for each extra form element that is not part of the provided content.)<br />Name,<br />Address,<br />City,<br />State,<br />Zip,<br />Phone,<br />Email,<br />Preferred Method of Contact,<br />Comments,<br />Reset button,<br />Submit button | 10 pts |
| HTML: Name, phone, and email are marked as required and a visual cue is present on the form. (no partial) | 3 pts |
| CSS: Site is 1400px wide. (no partial) | 3 pts |
| CSS: Site is centered in the viewport window. (no partial) | 3 pts |
| CSS: Fonts are styled with 3 font options. (no partial) | 3 pts |
| CSS: Visual cues for links, including navigation active page and hover. | 5 pts |
| CSS: Site looks professional | 10 pts |
| CSS: Consistent styling from page to page and no unused CSS styles. (no partial) | 5 pts |
| Testing: HTML pages contain no validation errors (5 pts ea) | 10 pts |
| Testing: CSS contains no validation errors (no partial) | 5 pts |
| Testing: Screenshot of one page in 2 browsers submitted (no partial) | 5 pts |
| Testing: Notation of differences noted, if any. (no partial) | 5 pts |
| HTML: Name included in an author tag on both pages (no partial) | 5 pts |
| HTML: Favicon included in code on both pages and displays as expected. (no partial) | 5 pts |
| HTML: Appropriate page titles used in head on both pages | 5 pts |
| HTML: Descriptive meta description tag included in head on both pages and is descriptive of the site and the page it is describing. | 5 pts |