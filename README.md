
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
* 1. Find the button `new Repository` and click on it
* 2. For `Respository name` make sure you enter the exact same name as your username for the GitHub account
* 3. Make sure that you have selected the`Public`option since you want to be able to see your resume online
* 4. Then press on `create respository` to create your repository

### 3. Upload Resume 
You might be wondering why we use a Markdown version of your resume for this guide. Etter greatly explains that markdown has one of the cleanest syntax and is easy to get into. Since you are working with GitHub, you will be using GitHub Flavoured Markdown (GFM) which further expands the features compared to the vanila version pf Markdown.
GitHub falvoured Markdown. On your respository, you will find a button saying "add files" where you will find the option to upload files to your repository. You can then simply drag your resume to upload it on Github. Before you upload you will see a Commit changes section at the bottom page. This section becomes more important when wroking on different branches and working on one project with a team.
This helps to figure out changes made to this commit and keeps a log of changes to revert back to. For our purpose and keeping things simple we will not be using Commit changes since this guide focuses on having a resume uploaded and published on GitHub pages. To test if your page was successfully published, enter your repostioryname.github.io to access your resume page from any browser. 

### 4. Choose a Theme 
In the book we can see how etter recommend using statis site generators like jekyll due to its simplicity, quickness and efficency. Theres is no need to install additonal files or adjust your files for a specific theme. 
As you might have noticed, the webpage with your resume looks very plain and simple. To make your resume look more exiting we will select a theme that will automatically adjust and make your resume look better for everyone who visits it. At your repository go to the settings tab and scroll down until you come across the gitHub pages section. There you will find the Theme Chooser option to select a new theme. Press on change theme and it will redirect you to different jKeyll based themes where you can preview it and select one of your liking. 
Now if you revisit your page through the browser you will see any updated version with the theme you selected. Of course if you do not like the pre-exisitng themes you can also create your own theme using jekyll or other statis site generators. For more information on jekyll check out More Resources. 

---------------------------

## Authors and Acknowlegments


---------------------------

## FAQs

Why is Markdown better than a word processor?
The only purpose for a word processor is to create short and good looking PDFs that will be used and discarded later on. But for documentation on the other hand we need something that is kept up to date and lives in the online environemnt. Converting a word document to HTML is a total mess for creating websites. Word processor like Microsoft Word cost money, whereas Markdown is a free option for everyone at any platform.

Why is my resume not showing up?
If your resume is not showing up check if you have the following done.

Make sure:
your resume file is names as index.md
dont forget to access your page via respositorname.github.io
make sure your respository is online. To change the visiblity go to settings and at the bottom you will see the status of ur repository and you will be able to change it to public. 

