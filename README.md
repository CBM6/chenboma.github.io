# How to host an Online Resume
## Purpose:
1. This **README** will help you host your resume on github page step by step.
2. Principles, from [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), are applied to this **README**.
***
## Table of Contents:
  >1. [Prerequisites](#Prerequisites)
  >2. [Instructions](#Instructions)
  >3. [More resources](#More-resources)
  >4. [Authors and Acknoledgments](#Authors-and-Acknowledgments)
  >5. [FAQs](#FAQs)
***
## Prerequisites
  >1. Github account
  >2. A resume formatted in [Markdown](https://www.markdowntutorial.com/)
***
## Instructions:
**1. Sign in to your account on Github:**
  >1. Go to the main page of [Github](https://github.com/)
  >2. Click the **Sign-in** button which locates on right-up corner of the page.
  >3. Type your registered Email Adress and password, then click the **Sign-in** button
  ![signin](/assets/signin.gif "Sign in github")
  - Cool! You are using Github now. Github is an example of the Distributed Version Control Systems(**DVCS**). **DVCS** is the most popular system for technical writers and programmers. We will discuss why in the next step.

**2. Creat a new repository:**
  >1. After login into the account, website will automatically directs to main page.
  >2. Click **New** Button which is a green button on the left panel.
  >3. Type your repository name. Format is "your_own_name.github.io"
  >4. Click the **Public** check box to select if necessary.
  >5. Click the **Add a README file** check box to select it.
  >6. Click the **Create repository** button which is located at bottom of the page.
  ![creatre](/assets/creatrep.gif "Creat a new repository")
  - When you create a new repository. You need to select **public** and **Add a README file**. **Public** will allow others to read your document and contribute their changes to the document if they have permissions. This is a huge benefits of **DVCS**. **DVCS** allows people to work on the same documentation cocurrently and offline. People could merge their work by using **DVCS**.
  - **Add a README file** option that will add a **MARKDOWN** file named "README" into your root branch. Every repository should have this file in its root branch. The file will introduce your production or documentation, tell people how to contribute their changes to your repository and how to work with your repository offline.

**3. Set up a theme for your resume:**
  >1. Click **Setting** to access the setting menu
  >2. Scroll down until you see **Github page** menu
  >3. Click **Choose a theme** button to select a theme you prefer, then click **Select theme** button
  >4. Scroll down until you see **Commit changes** button, click it.
  >5. A new branch called "**gh-pages**" is created, and you are in this branch now.
  ![settheme](/assets/settheme.gif "Set theme for static website")
  - At this step, we are building a static website for you. Static websites do not need any server-side application. Static websites also do not need any database on server side, because it is static. People do not need to install any application. So, static websites are fast, cheap and secure. If you want to build a complex static website, a static website generator is highly recommeneded. The generator will build a static website by using your content and HTML and CSS.
  - We are using **Jekyll** over here, which is supported on github page. If you want to edit your static website. You can change your content in **index.mb** under **gh-pages**. Repeat **step3** to reselect a theme of your static website. More generators are introduced in the [book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

**4. Upload your resume:**
  >1. Click **pen icon**, which is located on the right-up area. ![uploade](/assets/pen.png)
  >2. Delete all contents in the file, then paste your resume
  >3. Scroll down until you see the **Commit changes** button, click it.
  >4. If you want to edit your resume on the Github page, please edit it in **ph-pages** branch.
  ![upload](/assets/upload.gif "Upload your resume")
  - You may already notice, all documentation is using **Markdown** language. Why? First of all, you could edit the **MARKDOWN** file on many platforms(Atom, text editor, Xcode,etc.). Secondly, **Markdown** language could directly be translated into HTML. It is convenient when you build a static website. **MARKDOWN** is easy to learn. Writers could spend less time on writing documentation with **MARKDOWN** language. This is what the most writers want.

**5. Check your resume online:**
  >1. Wait for some minutes. Servers need time to set up your online resume.
  >2. Click **Setting** to access the setting menu
  >3. Scroll down until you see **Github page**
  >4. There is a message:"**Your site is published at https://cbm6.github.io/chenboma.github.io/**"
  >5. Click the link or directly type the address in the address bar. The format is:"Your_account_name.github.io/your_repository_name"
  ![result](/assets/result.gif "Check your online resume")
  - Using tools and models from the book allows people to host their online resume easily. There are more tools and models in the book. These tools and models make the books very helpful.
***
## More resources:
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Set up Markdown Editor](https://www.portent.com/blog/copywriting/content-strategy/atom-markdown.htm)
***
## Authors and Acknowledgments:
- Andrew Etter
- Choy, Alex
- Sawka, Sean
- Huynh, Lucas A
## FAQs
1. Why is Markdown better than a word processor?
    >- First, operations of **word processors** are _more_ complicated. It requires people more time to write documentation. I will take **Microsoft Word** as an example because **Microsoft Word** is a famous word processor. For example, if you wanted to change a heading's size. In **Microsoft Word**, you need to select that heading and choose a proper font size and font style for it. In **Markdown**, you just change the number of "#" before the heading. Secondly, independence. People could edit **Markdown** file on many platforms(text editor, atom, Xcode, etc.). **Microsoft Word file** can only be edited on **Microsoft Word file**. Thirdly, a **Markdown file** can directly turn into an **html file** and be hosted online. So, **Markdown** is better than **a word processor**.

2. Why is my resume not showing up?
    >- It is mentioned in **instruction** section. The Server needs several minutes to apply the theme to your resume and host your resume online.
    >- If your resume was still not showing up, check your internet.
    >- If you followed the instruction and your internet is fine, there might be a problem on the server-side. You can check Github status over [here](https://www.githubstatus.com/).
