---
layout: tutorial_page
permalink: /rule_3
title: Rule 3
header1: Workshop Pages for Students
header2: Create templates and hace a consistent structure
image: /site_images/CBW_bigdata_icon.jpg
home: https://bioinformaticsdotca.github.io/GOBLET_GitHub_2017
description: This rule will cover creating templates.
author: Ann Meyer
modified: 2017-11-17
---

# Learning Objectives

Be able to:

* Create page templates

# Templates

Templates take care of the tedious layout bits of your pages.  These layouts are consistent across pages and contain things that should be on every page.  You should have a few different templates (workshop landing page, tutorial page, etc).  

Templates are found in the `_layouts` directory and are written in html.

Currently, there should only be one template, default.html.  This is the template index.md is using.

# Creating a New Template

Let's create the template for the landing page for a 2 day workshop.

In the `_layouts` directory, click "Create new file".  

<img src="https://github.com/bioinformaticsdotca/10_Simple_Rules/blob/master/img/new_file.png?raw=true" alt="New File" width="450" align="middle" />

Name the file "2_day_main.html".

<img src="https://github.com/bioinformaticsdotca/10_Simple_Rules/blob/master/img/file_name.png?raw=true" alt="Fle Name" width="450" align="middle" />

Standard things we need are the html tags; the head tags and content; and the body tags.  However, there are a few things we'd like to have modifiable on each page such as:

* Title that appears in internet tab
* Title and subtitle that appear on the page
* Image associate with the page
* Page content itself

Content that is modifiable is contained within curly bracket `{ {   } }` placeholders.

The code for our template can be found [here](https://raw.githubusercontent.com/bioinformaticsdotca/10_Simple_Rules/master/2_day_main.txt).

Copy the text (Ctrl+A and Ctrl+C) and paste it (Ctrl+V) into the textbox and commit it.

<img src="https://github.com/bioinformaticsdotca/10_Simple_Rules/blob/master/img/PasteText.png?raw=true" alt="Paste Text Box" width="450" align="middle" />


We should also make a template for our tutorials.  Repeat the steps above to create a template named tutorial.html with the code found [here](https://raw.githubusercontent.com/bioinformaticsdotca/10_Simple_Rules/master/tutorial.txt).  


Let's pull all our changes to our local computer.  On your local computer in your website repo type:

```
git pull origin master
```

[Next rule](https://bioinformaticsdotca.github.io/rule_4)
