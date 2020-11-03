# How to host your Resume on GitHub Pages (and the idea of Tech Communication)

This README describes how to post and host a resume and on GitHub pages and refers back to some strategies and ideas that are described in Etter's book Modern Tehcnical Communication. This guide will explain every step from opening a GitHub account up to designing your resume with themes. 

![](https://media.giphy.com/media/qKlHOvwluxmmOTUZ45/giphy.gif) 

-------------------------
## Prerequisit

This guide requires a resume that is written and formated in GitHub Flavoured Markdown (GFM).
Don't have a resume in GitHub Flavoured Markdown? For more details o  How to create a Markdown file see More Resources.

---------------------------

## Instructions


### 1. Create a GitHub pages account
In the book Modern Tehcnical Communication, Andrew Etter explains why GitHub is a great choice for a Distirbuted Version Control system (DVCs) compared to a centralized system (Click here for more info on DVCs). He explains that the key factor for GitHub being a great platform is the fast performance, allowing offline work and support concurrent work on the same file. GitHub also helps us to host static sites with way more simplicitiy. There is no need to install specific external programs or files. For future developers like you, GitHub is fully accessible and controllable through your terminal and can also provide enhanced functionallity and features. 
So to start off, your first step towards hosting your resume on GitHub is to open an account under www.github.com. An account will allow us to have full access to the platform for our resume. 

### 2. Create a repository
In the book Etter goes on and explains how repositories are used to store documents and files. Why use a repository? Etter prioritizes the fact that with repositories we can have files, documents and codes stay synced and updated. This would result to encoruage developers to further contirbute to files and have updated repositories. Repository are also great when working together with a team where everyone needs to contribute towards the final product. The repository can allow to make different memebrs of your team create branches and work on their part of the projec without interfering with the main piece of the project. Why would you want that? This makes your project safe from unknown bugs that might develop if you and your team memebrs merge together for the project. In our case, we are just looking for uploading a resume which would not apply to it. 

After you have opened you account successfully:
> 1. Find the button `new Repository` and click on it
> 2. For `Respository name` make sure you enter the exact same name as your username for the GitHub account
> 3. Make sure that you have selected the`Public`option since you want to be able to see your resume online
> 4. Then press on `create respository` to create your repository

### 3. Upload Resume 
You might be wondering why you are using a Markdown version of your resume for this guide. Mardkwon is one of the cleanest and easiest sytnax to get into. Since you are working with GitHub, you will be using GitHub Flavoured Markdown (GFM) which further expands the features compared to the vanila version of Markdown. Etter further emphazies that different falavours of Markdown can bring you set of features and you might have to update your markdown files if you swtich to a new flavour. To learn more about GitHub flavoured Markdown please head to More Resources for a great tutorial into GitHub flavoured Markdown.
To upload your markdown resume file: 

> 1. On your resposity, find the button `add files` and then press on `upload file`
> 2. Before you add your file make sure your resume is named as `index.md` since GitHub sets the index file to be shown on the online page. 
> 3. After you have uploaded the file, you will come accros the `commit changes' . This section becomes more important when wroking on different branches and working on one project where you need to document what the file is suppose to do and what changes were made to the file. For our reason you can skip this section.
> 4. Press on the `commit changes` button to add your resume to the github respository

To test if your page was successfully published, enter your `<username>.github.io` to access your resume page from any browser. 

### 4. Choose a Theme 


As you might have noticed, the webpage with your resume looks very plain and simple. To make your resume look more exiting you will select a theme that will automatically adjusts your resume and make it a great looking static site. In the book we can see how Etter recommends using static site generators like jekyll due to its simplicity, quickness and efficency. Theres is no need to install additonal files, adjust your files for a specific themes or needing any databases. Jekyll gives you the tools to create and customize your own static site template for your markdown files. Of course creating your own site template can take a bit of time. For more information on jekyll check out More Resources.  In our guide you will see a different option using GitHub pages themes. GitHub provides themes that can be easily selected and applied to your current respository without any concerns. 

To add a theme to your repository:
> 1. At your repository go to the `settings tab`
> 2. Scroll down until you come across the `GitHub Pages` section
> 3. Under Theme Chooser press on 'change theme' 
> 4. Scroll through the different options on Jkelly themes and choose one by pressing on 'select theme'

Now if you revisit your page through the browser you will see an updated version with the theme you selected.

---------------------------
## More Resources

[GitHub Flavoured Markdown Tutorial](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax)

[Andrew Etters Modern Tehcnical Writting](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

[Starting with Jekyll](https://jekyllrb.com/tutorials/video-walkthroughs/)


---------------------------

## Authors and Acknowlegments

[README template](https://github.com/PurpleBooth/a-good-readme-template)

---------------------------

## FAQs

#### Why is Markdown better than a word processor?
> The only purpose for a word processor is to create short and good looking PDFs that will be used and discarded later on. But for documentation on the other hand we need something that is kept up to date and lives in the online environemnt. Converting a word document to HTML is a total mess for creating websites. Word processor like Microsoft Word cost money, whereas Markdown is a free option for everyone at any platform.

#### Why is my resume not showing up?

Make sure:
> 1. Your resume file is named as index.md
> 2. Dont forget to access your page via respositorname.github.io
> 3. Make sure your respository is online. To change the visiblity go to `settings` and scroll to the bottom where you will see the status of your repository and change it to public. 

