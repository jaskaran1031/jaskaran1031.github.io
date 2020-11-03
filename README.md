# How to host your Resume on GitHub Pages

This README describes how to post and host a resume and on GitHub pages and refers back to some strategies and ideas that are described in Etter's _Modern Technical Communication_. This guide will explain every step from opening a GitHub account up to designing your resume with themes. 

![](https://media.giphy.com/media/pkwz1yBwHmy2bMH6oi/giphy.gif) 

-------------------------
## Prerequisite

This guide requires a resume that is written and formated in GitHub Flavoured Markdown (GFM).
Don't have a resume in GitHub Flavoured Markdown? For more details on how to create a Markdown file see _More Resources_.

---------------------------

## Instructions


### 1. Create a GitHub account
In the book _Modern Technical Communication_, Andrew Etter explains why GitHub is a great choice for a Distributed Version Control system (DVCs) compared to a centralized system (Click [here](https://en.wikipedia.org/wiki/Distributed_version_control) for more info on DVCs). He explains that the key factor for GitHub being a great platform is the fast performance, allowing offline work and support concurrent work on the same file. GitHub also helps us to host static sites with way more simplicity. There is no need to install specific external programs or files. For future developers like you, GitHub is fully accessible and controllable through your terminal and can also provide enhanced functionality and features. 
So to start, your first step towards hosting your resume on GitHub is to open an account under www.github.com. An account will allow us to have all these features for posting our resume. 

### 2. Create a repository
In the book, Etter goes on and explains how repositories are used to store documents and files. Why use a repository? Etter prioritizes the fact that with repositories we can have files, documents, and codes stay synced and updated. This would result to encourage developers to further contribute to files and have updated repositories. It is also great when working together with a team where everyone needs to contribute to the final product. The repository can allow you to make different team-member branches and work on their part of the project independently without interfering with the main source. Why would you want this? It makes your project safe from unknown bugs that might develop if you and your team members merge branches into the project. In your case, you are just looking for uploading a resume which is not necessary to do.

After you have opened your account successfully:
> 1. Find the button `new Repository` and click on it
> 2. For `Repository name` make sure you enter the same name as your username as follows `<username>.github.io`
> 3. Make sure that you have selected the`Public`option since you want to be able to see your resume online
> 4. Then press on `create repository` to create your repository

### 3. Upload Resume 
You might be wondering why you are using a Markdown version of your resume for this guide. Markdown is one of the cleanest and easiest syntaxes to get into. Since you are working with GitHub, you will be using GitHub Flavoured Markdown (GFM) which further expands the features compared to the vanilla version of Markdown. Etter further emphasizes that different flavors of Markdown can bring you a set of features and you might have to update your markdown files if you switch to a new flavor. To learn more about GitHub flavored Markdown please head to _More Resources_ for a great tutorial on it.
To upload your markdown resume file: 

> 1. On your repository, find the button `add files` and then press on `upload file`
> 2. Before you add your file make sure your resume is named as `index.md` since GitHub sets the index file to be shown on the online page. 
> 3. After you have uploaded the file, you will come across the `commit changes'. This section becomes more important when working on different branches and working on one project where you need to document what the file is supposed to do and what changes were made to the file. For our reason, you can skip this section.
> 4. Press on the `commit changes` button to add your resume to the GitHub repository

To test if your page was successfully published, enter your `<username>.github.io` to access your resume page from any browser. 

### 4. Choose a Theme 


As you might have noticed, the webpage with your resume looks very plain and simple. To make your resume look more exciting you will select a theme that will automatically adjust your resume and make it a great looking static site. In the book, we can see how Etter recommends using static site generators like Jekyll due to its simplicity, quickness, and efficiency. There is no need to install additional files, adjust your files for a specific theme, or needing any databases. Jekyll gives you the tools to create and customize your static site template for your markdown files. Of course, creating your site template can take a bit of time. For more information on an in-depth tutorial for Jekyll check out _More Resources_.  In our guide, you will see a different option using GitHub pages themes that use pre-existing Jekyll themes. GitHub provides themes that can be easily selected and applied to your current repository without any concerns. 

To add a theme to your repository:
> 1. At your repository go to the `settings tab`
> 2. Scroll down until you come across the `GitHub Pages` section
> 3. Under Theme Chooser press on 'change theme' 
> 4. Scroll through the different options on Jekyll themes and choose one by pressing on `select theme`. Note: When you select a theme a new `_config.yml` will show up in your repository. This file will be used to further expand on the theme and make changes to it.

Now if you revisit your page through the browser you will see an updated version with the theme you selected. You might notice that the header of your newly looking page has your repository name with `github.io` on it.  

To change the title of your static page:
> 1. Under your repository open the newly created `_config.yml` file 
> 2. On the right side of the top bar, press on the little pencil icon to edit the file 
> 3. On the next line enter the following text `title: <Your Header>`


---------------------------
## More Resources

[GitHub Flavoured Markdown Tutorial](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax)

[Andrew Etters Modern Technical Writting](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

[Starting with Jekyll](https://jekyllrb.com/tutorials/video-walkthroughs/)


---------------------------

## Authors and Acknowledgments

[README template](https://github.com/PurpleBooth/a-good-readme-template)

---------------------------

## FAQs

#### Why is Markdown better than a word processor?
> The only purpose for a word processor is to create short and good looking PDFs that will be used and discarded later on. But for documentation on the other hand we need something that is kept up to date and lives in the online environment. Converting a word document to HTML is a total mess for creating websites. Word processors like Microsoft Word cost money, whereas Markdown is a free option for everyone on any platform. 

#### Why is my resume not showing up?

Make sure:
> 1. Your resume file is named `index.md`
> 2. Don't forget to access your page via `<username>.github.io`
> 3. Make sure your repository is online. To change the visibility go to `settings` and scroll to the bottom where you will see the status of your repository and change it to public. 

