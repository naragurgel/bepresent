# Testing

The Be Present site has been tested in the following ways - 

- [Code Validation](#code-validation)
    - [W3C HTML Validator](#w3c-html-validator) 
    - [W3C CSS Validator](#w3c-css-validator)
- [Lighthouse](#lighthouse)
- [A11y Color Contrast Accessibility Checker](#a11y-color-contrast-accessibility-checker)
- [Browser Compatibility](#browser-compatibility)
- [Manual Testing](#manual-testing)
- [Bugs](#bugs)
    - [Defects of Note](#defects-of-note) 
    - [Unresolved](#unresolved)

## Code Validation 

### W3C HTML Validator

Index Page

![image](https://user-images.githubusercontent.com/112726044/195717426-d9cdcfd3-ea1a-402f-8daf-516eb2d51995.png)

Thank-You Page

![image](https://user-images.githubusercontent.com/112726044/195717434-c361608a-266d-4df3-9598-d79a30e11a35.png)

404 Page

![image](https://user-images.githubusercontent.com/112726044/196798010-b7df50dc-4a91-469f-a208-0733a47dc03e.png)


### W3C CSS Validator 

All pages passed the CSS validator without error. 

![image](https://user-images.githubusercontent.com/112726044/195717602-83005520-073c-4c58-9306-0f63a5bb55ba.png)

### Lighthouse 

I Used Lighthouse in Chrome Developer Tools to test each of the pages for:

- Performance - How the page performs whilst loading.
- Accessibility - How accessible is the site for all users and how can it be improved.
- Best Practices - How does the site conform to industry best practices.
- SEO - Search engine optimisation. Is the site optimised for search engine result rankings.

- As an example, the results for the Be present website for desktop.

![image](https://user-images.githubusercontent.com/112726044/195717752-68b62fb8-2f0f-4d79-963c-b14d6a20d7ae.png)


### A11y Color Contrast Accessibility Checker

Colour contrast tests were carried out across the website and all came back without issue. 

![image](https://user-images.githubusercontent.com/112726044/195717827-f139c052-a025-4e12-9234-dd5f46c27667.png)

### Browser Compatibility

The site was tested and I ensured my site is working well as fallow in the table below:

| Device             | BROSWER        | OS           | VIEWPOINT     |
|--------------------|----------------|--------------|---------------|
| Iphone 11          | Safari         | iOS, v14     | 414 x 715px   |
| Iphone 12          | Safari         | iOS, v16     | 428 x 746px   |
| Vivo Y21           | Firefox        | Android, v11 | 384x 724px    |
| OnePlus 6T         | Chrome         | Android, v9  | 412 x 757px   |
| Samsung Galaxy     | Samsung        | Android, v12 | 360 x 649px   |
| Motorola Moto G71  | Chrome         | Android, v11 | 412 x 797px   |
| Huawei P30         | Firefox        | Android, v09 | 360 x 657px   |
| Samsung Galaxy Tab | Chrome         | Android, v12 | 753 x 1037px  |
| Ipad Pro 12.9      | Safari         | iOS, V12     | 1024 x 1292px |
| Windows 10         | Microsoft Edge | Windows 10   | 1920 x 946px  |
| MAC BOOK           | Safari 12.1    | Mohave       | 1400 x 766px  |

## Manual Testing

**Manual Testing For Contact Form**
- The submit button is working
- The error mensage about the required fields appears if you submit a empty input
- The error mensage appears if you submit a invalid email address
- I tested the sucess message after submit all the correct inputs
- No console errors
- Looks good on mobile 
- Looks good on tablet
- Looks good on desktop

**Thank You Page**
- When sign up form is successfully entered, a thank you page comes up
- Links go to the right page
- Social media footers open in new window to correct destination
- Navigation links go to correct page/section on index.html

**Custom 404 page**:
- User goes within https://naragurgel.github.io/ domain, but outside of expected index.html, 404.html or tks.html, they see the custom 404.html page
- Links on page go to right page
- Social media footers open in new window to correct destination
- Navigation links go to correct page/section on index.html

**home page (index.html)**
- Navigation links smoothly scroll to correct section on index.html
- Social media footers open in new window to correct destination

**Responsiveness**
- Relax image takes 100% with across all devices
- Main sections don't go wider ultra wide, they have margin on super wide screens
- As screen width is less than 1200px, Benefits of mediation goes from 3 columns to 1
- As screen width is less thatn 1200px, Guided meditations goes from 3 columns to 1
- Sign up section background images takes up 100% across all devices
- Sign up form takes up almost all width on phones
- Navigation text rearranges size so it takes up less space on smaller devices
- Navigation is sticky and always visible
- Footer icons don't get too spacey on desktop, and maximized spacing on small devices so its easy to select what the user wants to tap

## Bugs
Constant unit test was done as features were added. Fixed were checked in promptly with appropriate commit messages, but defects were not officially tracked.

### Defects of Note
The hasrdest parts to fix were: 
-sticky navagation
-getting videos to be responsive, but I used xyz site to figure that out

### Unresolved
There is a small gap between the logo image and the relax-image for mobile screen that I couldn't adjust.

## README

[README.md](README.md) 




