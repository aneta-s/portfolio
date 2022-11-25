# Workflow How To Update My Portfolio Website On Netlify

1.  Open the source code on your computer in VSC
2.  Navigate to test-portfolio folder in Git anetas>test-portfolio
3.  Make changes in the code there
4.  Deploy to test environment: Push changes to test-portfolio to test on your devices git status, git add ., git commit -m 'description', git push
5.  Changes should be visible on https://aneta-s.github.io/test-portfolio/ Repo url https://github.com/aneta-s/test-portfolio
6.  Deploy to live environment: copy all files manually from folder test-portfolio to portfolio on your computer except readme.md. test-portfolio should have a clean readme.md file. portfolio readme.md has content "Workflow How To Update My Portfolio Website On Netlify"
6.  Push changes to portfolio repo on Github: git status, git add ., git commit -m 'description', git push
7.  Changes should be deployed on https://github.com/aneta-s/portfolio
8.  Website is automatically published and changes should be visible on aneta.netlify.app
9.  See status website https://app.netlify.com/sites/aneta/overview
10. Check the performance of the website https://gtmetrix.com/ and fix the issues. You can also check Lightroom in the console
11. Resolve eventually errors in the console


# Bugs And Browser related errors
 🟠 Safari First buttons are without borders
 ✅ Resolved: use playinline. 🔴 Video does not play on iPhone https://stackoverflow.com/questions/20347352/html5-video-tag-not-working-in-safari-iphone-and-ipad
 🟠 Testing: add code in .tilt.js file https://answers.netlify.com/t/added-new-site-using-old-url-and-netlify-display-old-website-continuous-deployment/74175/15


# Differences test-portfolio from portfolio
 🟠 Heading Aneta Stojanowska and Amsterdam is changed
    <h1 class="heading-primary">                                                                                                                                                    <span class="heading-primary-main">
      Hello, I'm <strong> Full Name</strong></span
      >
      <!-- span is to style elements differently -->
      <span class="heading-primary-sub">
        a UX/UI/Motion Designer, based in the City.</span
        >
      </h1>

🟠 Profile image profile-foto.png is changed to profile-foto.jpg
 <img
            src="image/profile-foto.jpg"
            alt="Profile Photo"
            class="photo"
            height="auto"
            width="200px"
            />

# Notes
🟢  Developer uses these widths, but the wish is to change to our breakpoints given below the file
1400
1200
992
600


# Backlog Portfolio2

❎  Parralex: I want page colors on index.html to change in parallex effect. Example:
❎  Make footer a reusable component
❎  Add favicon to the project details pages ie project details pages does not have favicon
❎  A: A white box appears at the bottom, isn't the element fit always span to the bottom of the page?
❎  A: I want the Homepage button equal to Projects buttons. Create a component to reuse it
❎  A: I want get rid off this white line in the button Screenshot 2022-07-06 at 16.27.29.png
❎  In Project Details pages there are two different classes. class="project-container mb-0" and class="project-container”. Why not one generic class for all descriptions of the process?
❎  I want to edit styling of the project three and one ie. I want to adjust color of the main header and the sub-header, how to do it?
❎  Is it necessary to upload the same image to website for both desktop and smaller devices? class="mobile-image" 
❎  D&T: Layout for Project: in order to have a better space repartition and a good layout balance I want to alternate between the text being in the left side and the picture being on the right 1/2 times.This will dynamise the site + will keep the user captivation Screenshot 2022-05-30 at 10.02.54.png

Legenda

Devices
D: desktop
T: tablet
S: smartphone
A: All

Test on real browsers and OS combinations using Lambdatest
CH: Chrome
S: Safari
M: Mozilla
F: Firefox
SI: Samsung Internet
O: Opera
UC: UC Browser
EL: Edge Legacy
IE: IE
E: Edge
O: Other

Breakpoints for widths of devices
0 - 320px:          Phone-xs
0 - 600px:          Phone
600px - 900px       Table Portrait
900px - 1200px      Table Landscape
[1200px - 1800px]   Desktop Normal Styles
1800px +            Big Desktop
1em = 16px


🟢🔴🟠🔳🔘✅❎❌ Icons


