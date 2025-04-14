# Contributing to the Helping Hands Charity Project (Pure HTML/CSS Version)

![Project cover photo](./repo_images/helping_hands_charity_website.png)

Thank you for your interest in contributing to the project **[Helping Hands Charity](https://helping-hands-charity.netlify.app/)**. This document outlines how you can contribute to the development of this project. Please read this guideline carefully to ensure your contribution aligns with the project's requirements.

## Table Of Contents

- [Before You Contribute](#before-you-contribute)
  - [Privacy](#privacy)
  - [Prerequisites](#prerequisites)
- [Contribution Guidelines](#contribution-guidelines)
  - [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
  - [1. Set Up Your Development Environment](#1-set-up-your-development-environment)
  - [2. Log into Your GitHub Account](#2-log-into-your-github-account)
  - [3. Check Your Email for an Invitation](#3-check-your-email-for-an-invitation)
  - [4. Fork the Repository](#4-fork-the-repository)
  - [5. Clone Your Fork](#5-clone-your-fork)
  - [6. Change Directory into the Cloned Repository](#6-change-directory-into-the-cloned-repository)
  - [7. Open VS Code from the New Directory](#7-open-vs-code-from-the-new-directory)
- [Building the Project](#building-the-project)
  - [Step 1: Create Your Project Files](#step-1-create-your-project-files)
  - [Step 2: Use Bootstrap](#step-2-use-bootstrap)
  - [Step 3: Create Template Outline](#step-3-create-template-outline)
  - [Step 4: Link All Templates](#step-4-link-all-templates)
  - [Step 5: CSS Link](#step-5-css-link)
  - [Step 6: Update All Your Sections](#step-6-update-all-your-sections)
  - [Step 7: Find All Your Images](#step-7-find-all-your-images)
  - [Step 8: Add Google Maps](#step-8-add-google-maps)
  - [Step 9: Enhancements](#step-9-enhancements)
  - [Step 10: Update Your README](#step-10-update-your-readme)
  - [Step 11: Push to Your Fork](#step-11-push-to-your-fork)
  - [Step 12: Open a Pull Request](#step-12-open-a-pull-request)

---

## Before You Contribute

### **Privacy**

Please note that this project should remain private during your development. As a contributor, you must respect the confidentiality of all materials and discussions related to this project. This [LICENSE](LICENCE) applies once you have completed your assessment and your teacher(s) have accepted your application and allowed it to be made public.

### **Prerequisites**

To contribute, ensure that you have the following skills:

- Knowledge of **HTML** and **CSS**
- Experience using the [Bootstrap Framework](https://getbootstrap.com/)
- Experience deploying your work on [Netlify](https://www.netlify.com/)
- Familiarity with `git` and [GitHub](https://github.com/)

---

## Contribution Guidelines

### **Code of Conduct**

By contributing, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## How to Contribute

### 1. Set Up Your Development Environment

Ensure that you have the necessary tools for development:

- **VS Code**
- **Live Server** extension
- **Markdown Preview**
- A modern browser (preferably **Chrome** or **Brave**)

### 2. Log into Your GitHub Account

### 3. Check Your Email for an Invitation

Look for a notification to join the **Pets Lover** private repository by **Bolder Learner Tech School**.

- Click the notification to access the link to the private repository.

 ![Email Notification](./repo_images/blts_invitation_email.png)

- Click the green button to accept the invitation.

 ![Accept Invitation](./repo_images/blts_accept_invitation.png)

### 4. Fork the Repository

- Fork the repository to your GitHub account.
 ![Fork Repo](./repo_images/fork.png)
- Follow the steps to complete the forking process.
 ![Complete Forking](./repo_images/create_fork.png)

### 5. Clone Your Fork

- Copy the SSH link from your fork.
 ![Copy Repo SSH](./repo_images/blts_ssh_link.png)
- In your VS Code terminal, run the following command:

 ```bash
  git clone <paste-your-ssh-link-here>
 ```

 ![Clone Fork](./repo_images/blts_clone.png)

### 6. Change Directory into the Cloned Repository

Run this command:

```bash
cd <name_of_cloned_repo>
```

![Change Directory](./repo_images/blts_cd.png)

### 7. Open VS Code from the New Directory

Run this command to open the project in VS Code:

```bash
code . # There is a trailing full stop
```

![Open VS Code](./repo_images/blts_run_code2.png)

---

## Building the Project

**Note**: Following instructions is key to success in this project. Make sure to adhere to the steps outlined here to avoid losing valuable points.

### Step 1: Create Your Project Files

Click on the [live link of Helping Hands Charity Website](https://helping-hands-charity.netlify.app/) website. You'll notice the navigation bar has three links. This may indicate the need to create several HTML files:

- `index.html`
- `about.html`
- `contact.html`
- And others

The website also contains images, so you might need to create an images subfolder:

- `images/`

Additionally, you may need a custom CSS file:

- `style.css`

**Important**:

- Add and push these files and folders to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 2: Use Bootstrap

Let us say you have chosen to begin with the `contact.html` file. Do you recall how to use Bootstrap in your template? If not, check your lesson. Alternatively, browse the [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) for a quick startup guide.

Once you have figured out how to use Bootstrap in your first HTML file (say `contact.html`), update it with the Bootstrap quickstart guide.

Commit this change to your repository.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 3: Create Template Outline

Before you can build any page, be it `index.html`, `about.html`, or `donate.html`, you need to break that page into sections. Let us use the [contact.html](https://helping-hands-charity.netlify.app/contact) page as an example:

![contact page](./app/static/images/blts_contact_page.png)

This page seems to have five parts:

- A navigation bar
- A hero section
- A section with a form and more contact information
- A Google Map section
- A call for volunteers
- A footer

In your `contact.html` page, you need to clearly define these sections. Here is an example:

```html
<!-- 
 Demonstration of how to properly structure your contact.html 
 -->

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Contact</title>
    <link 
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
      rel="stylesheet" 
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
      crossorigin="anonymous">
  </head>
  <body>
    <!-- Start of navbar -->
    <nav>

    <nav>
    <!-- end of navbar -->



    <!-- Start of hero section -->
    <section class="hero">

    </section>
    <!-- end of hero section -->



    <!-- Start of contact section -->
    <section class="contact">

    </section>
    <!-- end of contact section -->

     <!-- Start of map section -->
    <section class="contact">

    </section>
    <!-- end of map section -->

     <!-- Start of footer section -->
    <section class="contact">

    </section>
    <!-- end of footer section -->

    <script 
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
      integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
      crossorigin="anonymous">
    </script>
  </body>
</html>
```

What we have done here within our `body` tags is that we have added comments to each section. These comments help to guide you, and any other person reading your code, to understand your thoughts. Notice that the sections at this stage are currently empty.

**Do this for all your HTML files**. Once you have identified the sections in your pages and commented them out, you are required to push these changes.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 4: Link All Templates

Now that you have all the pages of the website in place, you need to link them. Do you recall how to link templates to your website? Ensure that you have linked all the pages of your website by referring to the [live application](https://helping-hands-charity.netlify.app/).

To do this, you first need to update the `nav` element you defined in [step 3 above](#step-3-create-template-outline). Head over to [Bootstrap](https://getbootstrap.com/), search for a suitable Navbar snippet (you can also search online or other platforms), then update this `nav` section.

Once you have linked them, add and push your changes as a single commit.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 5: CSS Link

Add a link to your `style.css` file in all your templates. Once you complete doing this, push your changes as one commit.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 6: Update All Your Sections

Now, with all pages properly outlined, it is time for you to add all individual elements. For example, for the section called `nav`, add your navigation bar. Wherever there are headings or paragraphs or images, add them.

**Important**:

- Add and push these changes to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 7: Find All Your Images

It is far easier to go get images for the website because we already know, from looking at the website, how many we will need. It is critical that you use ONLY high-quality images and not anything from the internet. Here are some resources you can use to download high-quality images:

- [Pexels](https://www.pexels.com/)
- [Pixabay](https://pixabay.com/)
- [Unsplash](https://unsplash.com/)
- [Undraw](https://undraw.co/)

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push this as a single commit**.

### Step 8: Add Google Maps

The `contact.html` page has Google Maps embedded. This may be something you do not know how to integrate, but it is worth learning. You are encouraged to find possible ways of adding it by researching extensively.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push this as a single commit**.

### Step 9: Enhancements

Modify the application as much as you want, adding styles to your liking. Play around with the design, and personalize the outcome. Remember to commit your changes.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 10: Update Your README

Modify your README file to reflect your final changes. It is recommended that you include as much of details of your changes in the README.

**Important**:

- Add and push this change to your GitHub repository.
- **Ensure that you push these as a single commit**.

### Step 11: Push to Your Fork

Push your changes to your forked repository.

```bash
git push origin main
```

### Step 12: Open a Pull Request

- Navigate to the original repository on GitHub and open a Pull Request from **your forked branch**.
- Include a detailed description of what your pull request does.
- Mention any new files, changes, or deletions.

**Pull Request Review Process**:

- **Review**: Your pull request will be reviewed by the project maintainers. Feedback or changes might be requested.
- **Merging**: Once approved, your changes will be merged into the main branch. Congratulations!
