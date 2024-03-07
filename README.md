# How to Host and Format a Resume on GitHub

An easy guide to create and host your resume on a static website using GitHub Pages, Jekyll, and Markdown.


- [Tutorial on Hosting a Resume on Github Pages](#tutorial-on-hosting-a-resume-on-github-pages)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
    - [0. Create your resume using markdown](#0-create-your-resume)
    - [1. Hosting your resume](#1-host-your-resume)
    - [2. Jekyll Themes](#2-jekyll-themes)
    - [3. More Resources](#3-more-resources)
  - [Authors and Acknowledgements](#authors-and-acknowledgements)
  - [FAQS](#faqs)

  
## Prerequisites
  Before explainig the steps needed to host and format a resume on github. You first need to make sure you have all the tools needed.
  - **Markdown Editor** 
  Markdown is the most widely used lightweight markup language as stated by Andrew Etter in his book Modern Technical Writing. Markdown is easy to use and versatile, which is why it is important to learn about. You can choose to use github flavored Markdown, as it is useful when hosting the resume on github after. You are also free to use vanilla markdown or other flavors of it. To be able to see how it will be displayed, you can use any editor of your choice. These are some well known editors[Ghostwriter](https://ghostwriter.kde.org/), [MarkText](https://github.com/marktext/marktext), or [Visual Studio Code's](https://code.visualstudio.com/) built in editor. 

  - **Github Account** 
      
  You will need a github account to host your website on github pages. All you need to do is go to this [link](https://github.com/) and sign up. 


## Instructions
### 0. Creating your resume

To begin with you need to create your resume using markdown. Resources on how to use markdown to format your text will be added in the More Resources.
### 1. Hosting your resume

**Creating a Repository:**
The first thing you will do is to open github, open your profile page, and then click on the Repositories button. There you will find a green button called New. When you press on it you will be able to create your new repository. Make sure that your repository's name ends with an **.io**. You can make your repository public or private based on your needs.

**Editing your settings:**
After having your repository published, you will see a settings button. After clicking on it, look at the panel to the left and click on pages. Make sure your source is **deploy from branch** and that the github pages website will built from the **main** branch. 

** Upload Files into Repository**

After creating your repository and editing the settings, you will need to upload three files. 
  - index.md 
  - _config.yml 
  - README.md 

#### index.md
The index.md file will contain your resume formatted using markdown. The reason why it's called index is because that will allow github to know that this is the file you want to host.

#### _config.yml
The _config.yml file will add the Jekyll theme which will add some color and will format your file.

#### README.md
Finally, the README.md file is where you explain what you're doing in this repository.


### 2. Jekyll Themes

As previously mentioned, the _config.yml file will include Jekyll Themes. You can either to choose to use remote custom Jekyll Themes or use github's [supported theme's](https://pages.github.com/themes/). 
This is how the format should look, this example uses a remote theme, but feel free to choose otheriwse:

```
remote_theme: pages-themes/hacker@v0.2.0
plugins:
- jekyll-remote-theme 
```

### 3. More Resources
1. [Andrew Etter's *Modern Technical Writing*](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS): Dive deeper into Technical Writing with this book.
2. [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
3. [Markdown Tutorial](https://www.markdowntutorial.com/)

## Authors and Acknowledgements
[Farah Hegazi](https://github.com/farahhegazi)

Special thanks to my group mates:
- [Jacob Seraspi](https://github.com/jacobseraspi)
- [Fengfan Bian]()

## FAQS
1. *Why is Markdown better than a word processor?*
Markdown is better than a word processor due to its flexibility, and simple syntax. Using Markdown is better for displaying content on the web, since it can be easily converted to XHTML.

2. *Why is my resume not showing up?*
Some reasons why your resume might not be showing up is that:
- your repository doesnt end with .io
- you didnt edit your settings to ensure that it is deploying from the main branch.
- your resume isnt named as index.md
If you checked all of the points above, you might just need to wait for github pages to deploy your resume.



