---
id: creating-listform-templates
title: List form templates
---
<div class = "objectives"> 

**目的**

Create your first list form template.</div> <div class = "prerequisites"> 

**必要条件**

Click [here](prerequisites.html) to see what you'll need to get started!</div> 

In this tutorial, we'll cover nearly all aspects of creating a list form template such as: creating a list form with a **searchBar** and a table displaying an **image**, a **title**, and a **subtitle** for each cell.

![List form template final result](assets/en/custom-listform/custom-template-final-result.png)

## スタータープロジェクトをダウンロードする

Before we begin, be sure to download the **Starter Project** which includes:

* A **List form** folder 
* A **Contact.4dbase** file (a demo database with a ready-to-use mobile app project)

<div style="text-align: center; margin-top: 20px; margin-bottom: 20px">
  <p>
    

<a class="button"
href="../assets/en/custom-listform/CustomListFormStarterProject.zip">LISTFORM STARTER PROJECT</a>

  </p>
</div>

You are now ready to create your first list form template!

## Add a list form template to your mobile project

The first thing you'll need to do is create a .../Resources/Mobile/form/list folder next to the Contact.4dbase file. Then drag and drop your **list form** folder into it.

![Mobile folder list form template](assets/en/custom-listform/mobile-folder-custom-template.png)

Next, open the Contact.4dbase file with 4D. (File > open > Mobile Project > **Contact Demo App**)

Finally, in the **Forms section** of the project editor, you'll see that your list form template has been successfully added to the list of available list form templates!

![Forms section](assets/en/custom-listform/custom-listform-template.png)

Now let's focus on the contents of the **Custom List form** folder.

## List form template content

In this folder, you'll find:

* **a layoutIconx2.png** icon in 160x160px (it'll be displayed in the project editor when you select your template)
* **a manifest.json file** (includes a basic description of the template)
* **a template.svg file** (the visual representation of your template displayed when you define your list form content)
* Source folder including the **storyboard** (graphical interface) and **Swift** file (code for the form)

What are these files? What are they used for? How can you customize them?