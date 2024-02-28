# Welcome to PassePort

This is Abigail Cherdy Hartono's from Team 3 Module & Checkpoint Assignment

## Details about the Advanced Module Assignment
On this module assignment, the main deliverables are:

- Deploying the website on netlify
- Writing a Readme.MD containing Netlify Sign Up and Deployment Process
- Auto Deployment on GitHub with Netlify
- Connecting custom domain and DNS accordingly

## Module Assignment Submission
### PassePort Website: http://passeport.site
### Alternative link to website: https://abigailcherdyhartono-passeport.netlify.app/

## Deployment Documentation

### Sign Up on Netlify

1. Go to https://www.netlify.com/
2. Click on SignUp
    ![Netlify SignUp](assets/netlify-signup.png)
3. Select SignUp using GitHub
    ![SignUp with Github](assets/signup-github.png)
4. Enter your GitHub Credentials
    ![GitHub Creds](assets/github-credentials.png)
5. Congratulations! You've successfully logged in to Netlify!


### Deployment on Netlify

1. On your homepage on Netlify, go on to **Sites**
    ![Netlify Home](assets/netlify-home.png)
2. Click on **New Site** and select _import from existing project_
    ![GitHub Deployment](assets/netlify-newsite.png)
3. Select _deploy with GitHub_ as your deployment option
    ![deployment option](assets/deploy-options.png)
4. Select the correct Repository on your GitHub account. Be sure that you are in the correct organisation.
    ![GitHub Creds](assets/select-repo.png)
5. Fill in your deployment details, make sure you select the right branch, If you leave the Site Name as empty, Netlify will assign a random unused domain name for your site. Once done, click on **Deploy**
    ![Deployment Details](assets/site-details.png)
6. Once you've deployed your site, Netlify will take some time to deploy your site. At this point, all you need to do is wait.
    ![Deployment Progress](assets/deploy-progress.png)
7. Your Deployment is completed once you can see your domain url under your site name.
    ![Deployment Successful](assets/deployed.png)
8. Congratulations! You just successfully deployed your site directly from GitHub!


### Initializing your Custom Domain on Netlify

1. Go to your Netlify Account, then login.

2. Go to _Site_ then select the website that you want to set up the custom domain for. 
    ![Select your site](assets/netlifyhome.png)
3. Click on _Domain Management_.
    ![Domain Management](assets/domain-management.png)
4. Click on _Add a Domain_.
    ![Add a domain](assets/add-domain.png)
5. Enter the domain name that you have owned, then click on _Verify_, then _Add Domain_
    ![Enter domain](assets/enter-domain.png)
6. You will be redirected to your _Production Domain_ page, then next to your domain name, click on _Options_ then select _Go to DNS Panel_
    ![DNS Panel](assets/dns-panel.png)
7. Scroll down to your Name Servers, then copy all of the listed name servers and save them to clipboard, or any text editor. (This step is taken just to keep these nameservers).
    ![Nameservers](assets/name-servers.png)
8. Go to your **Domain Registrar**, login and go to your Custom Domain's domain management, then go to the DNS/Nameserver page. 
    ![Manage Domain](assets/manage-domain.png)
9. Click on Change Nameservers, then paste all the copied nameservers into the 4 available fields.
    ![Change nameservers](assets/change-nameservers.png)
10. It will take 24 hours for your nameservers changes to propegate. After 24 hours, check again and your custom domain should now be connected to your


## Details about the Checkpoint Assigment

On this checkpoint assignment, the main deliverables are:

- Custom font via embed or @font-face
- Applying text shadow
- Adding list style to list
- Applying 1 responsive image using **srcet** + **source** + **picture**
- Creating 1 asymmetrical grid (layouting both container and children)
- Creating animation using animation and transition


## Checkpoint Assignment Submission

My submission on this checkpoint assignment is [index.html](index.html), [style.css](style.css), and [script.js](script.js). In addition, [assets folder](/assets) contains all assets related to the project. This is my submission on the Checkpoint Assignment and will be deployed and developed further for my submission on the **Module 2 Assignment**.

The website title is PassePort. It is meant to be a website about 

## A little overview about PassePort

PassePort is a European specific tour and travel provider that can arrange tours all across Europe from Paris to Zermatt. 

### The navigation bar and homepage

![The navigation bar](assets/PassePort.png)

This navigation bar contains some animation on the icon when hovered and during page load. The navbar is responsive and will turn into a hamburger menu on mobile (or under 768px).

The homepage contains a responsive background image and animated overlaying text during page load.

### The About page

![The about page](assets/homepage.png)

This about page is implemented using picture + source + srcset and will adjust accordingly when screen is below 768px. 

### The Tours page

![The tours page](assets/tours.png)

This about page is implemented using picture + source + srcset and will adjust accordingly when screen is below 768px. 

### The Gallery page

![The gallery page](assets/gallery.png)

This page contains an image carousel implemented using only CSS and HTML. The circle buttons can be click to go to the next picture or you can simply scroll to the left side to go to the next one!

### Footer and Switch Mode

![The footer](assets/footer.png)

The footer has the author details, and a button to switch mode. When click, it will switch the whole page into Dark Mode or vice versa. There is a DOM local storage update through js so the mode chosen will pertain regardless of closing the tab. 

![The dark mode](assets/darkmode.png)
