# Markdown startup guide

1. Purpose of the document
2. What is Markdown?
3. Setting up for markdown
4. How to write Markdown

## Purpose of the document
This document will be used to explain how to setup a local environment to write documents in markdown and the basics of the language.

## What is Markdown?

Markdown is a markup language, this means that whatever we write in the file will be interpreted and translated to HTML with a certain style and/or format, this means that we will have to learn a few in-line commands to get the document as we want it.

It offers a unified way to write and document files in an extremely simple way, and if we add third party tools it can be even easier to write and to export files to PDF or other formats besides HTML. 

## Setting up for markdown
To write in Markdown we will be using Visual Studio Code, since the software is not bound to any licenses, has a wide availability of extensions that will make things easier and it's installation doesn't require elevated privileges.

### Visual Studio Code Installation

If you don't have Visual Studio Code installed in your computer, you can download it from _[here](https://code.visualstudio.com/)_ And follow the instructions below. You should be redirected to the following page:

1. You will be redirected to the following page, download the installer:

![VisualStudioDownload](sources/VisualStudioDownload.png)

2. After the download is complete, execute the installer and click _Next_

![VisualStudioCodeWizard1](sources/VisualStudioCodeWizard1.png)

3. Accept the terms and click _Next_

![VisualStudioCodeWizard2](sources/VisualStudioCodeWizard2.png)

4. __Make sure the installation is taking place in the 'AppData' folder for your user__ (prozenberg, in this case) and click _Next_

![VisualStudioCodeWizard3](sources/VisualStudioCodeWizard3.png)

5. Click _Next_

![VisualStudioCodeWizard4](sources/VisualStudioCodeWizard4.png)

6. Check option as you desire and click _Next_

![VisualStudioCodeWizard5](sources/VisualStudioCodeWizard5.png)

7. Click _Install_

![VisualStudioCodeWizard6](sources/VisualStudioCodeWizard6.png)

### Setting up Visual Studio Code

Once the installation is complete, jump to _Visual Studio Code_. Close the several windows that automatically open and click on the extensions tab (highlighted below):

![VisualStudioCode2](sources/VisualStudioCode1.png)

In this place you can download extensions for every programming language. For now, we will focus on the ones we will be using for Markdown.

To find them, type markdown in the searchbar as shown below:

![VisualStudioCode3](sources/VisualStudioCode2.png)

You will want to install _Markdown All in One_ and _Markdown PDF_. The first one offers a live preview of the document we're writing and a few shortcuts to make development easier; the second one will let us export our document to PDF and other several formats.  

More extensions and tools exist, but for now we will only be using these ones.

Click _reload_ after installing both.

Go to _File_ and create a new one, or hit _CTRL+N_. The first thing we will have to do is make sure our file is being written in markdown.

For this, click the area highlighted below:

![VisualStudioCode4](sources/VisualStudioCode4.png)

A modal will show up, write markdown and click the only available option. An installation of Chromium may begin:

![VisualStudioCode5](sources/VisualStudioCode5.png)

Let it finish before saving your file, then hit _CTRL+SHIFT+V_. This will open the live preview for our Markdown document. 

You can move it to the side to have both tabs open, like this:

![VisualStudioCode6](sources/VisualStudioCode6.png)

Type '# Hello World' to see the results:

![VisualStudioCode7](sources/VisualStudioCode7.png)

The last step is to export our file as a PDF. For this, hit _CTRL+SHIFT+P_. Type _'export'_ and a number of options will appear:

![VisualStudioCode8](sources/VisualStudioCode8.png)

Select _'Markdown PDF: Export (pdf)'_. The PDF file will automatically appear in the folder where the markdown file is saved.

## How to wirte Markdown

Everything you can learn about Markdown can be found in this _[link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#emphasis)_

For a Markdown example, this PDF's Markdown code can be found _[here](https://raw.githubusercontent.com/prozenberg/MarkdownBasics/master/MarkdownStartupGuide.md)_