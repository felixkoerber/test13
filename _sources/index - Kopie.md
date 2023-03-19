# Digital Storytelling
    


    - add reminder that lab-notebooks stored in github can be easiyl integrated as documentation into jb books

https://tlp-lpa.ca/digital-skills/digital-storytelling

https://en.wikipedia.org/wiki/Living_document
https://contractbook.com/dictionary/living-document-or-dynamic-document

e.g.

https://www.uni-bielefeld.de/lehre/living-document/


### Jupyter Books

Jupyter Books provides a flexible and powerful platform for creating, publishing, and sharing your work. Creating content using Jupyter Books is a simple process that allows you to combine text, code, and other multimedia elements into a single, interactive document. 

Here's a TL:DR guide on how to create content using Jupyter Books form our [tutorial on how to use Jupyter Books](https://felixkoerber.github.io/jb/10min.html):


#### 1. [Make sure you have all the prerequisites installed](https://felixkoerber.github.io/jb/setup.html)
Before you start setting up your course using Jupyter Book, make sure you have the following tools installed on your machine:
- **Git**: A version control system that helps you keep track of your code changes.
- **Jupyter Book**: A tool that helps you build and publish interactive books or documents. You can install Jupyter Book using pip install jupyter-book.
- A **text editor of your choice**: You can use any text editor, such as Visual Studio Code, Sublime Text, or Atom, to create and edit your content.


#### 2. [Create a fresh Git Repository for your project](https://felixkoerber.github.io/jb/tutorialcontent/publishing/account.html#start-a-project-setup-a-public-repository)
2.1. Go to the GitHub website (https://github.com) and click on the plus button on the upper right corner.
![GHNewRepo](https://github.com/felixkoerber/jb/blob/main/static/New_repo.jpg?raw=true)

</br>

2.2. Create a new repository for your course by giving it a name and a description.

</br>

![GHNewRepo_Description](https://github.com/felixkoerber/jb/blob/main/static/new_repo_example.png?raw=true)

</br>

2.3. On GitHub, open up the empty project in your browser.
-  Navigate to `settings`, `actions`, then `general` to change **Workflow permissions** to **Read and Write Permission** to change the Workflow permissions to Read and Write Permission. This will allow you to push changes to the repository from your local machine.

</br>

![Workflow_Permissions](https://raw.githubusercontent.com/felixkoerber/jb/0bd9a2930a41bc3f79ad876b603ea5534ef1a23a/static/Workflow_permission.jpg)

</br>

2.4. Save your changes.

2.5. Open up a terminal window and navigate to the location where you want to store your local course copy.

2.6. Copy the project's link and clone the repository using the following command: git clone https://github.com/yourprojectname.
    
#### 3. [Copy our course template](https://felixkoerber.github.io/jb/tutorialcontent/publishing/account.html#working-with-the-course-template)

- open our [course template repository](https://github.com/M-earnest/course_template_diler)

- click on `code` and then on *Download ZIP*
![Download_template](https://github.com/felixkoerber/jb/blob/main/static/Download_template.jpg?raw=true)

- Extract the contents of the ZIP file in the folder linked to your GitHub repository.
    
#### 4. [Create Content](https://felixkoerber.github.io/jb/tutorialcontent/writing/writing.html)

- Open the Markdown (.md) or Jupyter (.ipynb) files and copy your interactive content and code.

- Make sure to give each file a meaningful name and add a title to each page.

- You can use the provided style guide as a reference to see how to effectively implement MyST Markdown.


#### 5. [Table of Contents and config](https://felixkoerber.github.io/jb/tutorialcontent/structure.html)

-  Once you've created files, open the `_toc.yml`

-  add your newly created files in the sequence of your choice according to our template

-  open the `_config.yml`

-  Change the title, author, and the location of your GitHub repository.

#### 6. [Share it online](https://felixkoerber.github.io/jb/tutorialcontent/publishing/account.html)

- In your terminal, navigate to the location of your project and type the following commands:

- a. ) `git add .`

- b. ) `git commit -m "my first commit`

- c. ) `git push`

- Alternatively use the Gitkraken Client


#### 7. Add the pages

- On Github, navigate first to `settings` and then `pages`

- Click on `branch` and select `gh-pages`

![Set-Up_Pages](https://github.com/felixkoerber/jb/blob/main/static/Set_Up_Pages.jpg?raw=true)
You're all set! Once you're ready, make sure to make your repository public, so that others can view your beautiful website.

```{note}
GitHub Pages is a free web hosting service provided by GitHub. It allows one to easily publish websites directly from a GitHub repository. With GitHub Pages, you can create static websites, blogs, and even project portfolios without having to worry about managing servers or purchasing web hosting.

You simply create a repository in GitHub and push your website files (HTML, CSS, JavaScript, etc.) to the repository. GitHub Pages then automatically generates the website and makes it available at a unique URL. This URL is typically in the format "username.github.io/repository-name".

GitHub Pages makes it relatively easy to host your own website for developers and programmers, e.g. this course, but can be confusing for non-technical users. 
A workaround for non-technical users is to work with a preconfigured setup. Our workgroup for example has created a template that you can use to host a website like the one you're seeing right now. This is achieved by using a so called "github-worklflow". Checkout our tutorial for creating a website using Github pages [here](https://felixkoerber.github.io/jb/intro.html)

```

