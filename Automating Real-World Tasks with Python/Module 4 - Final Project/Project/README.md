# Qwiklabs Assessment: Automate updating catalog information

## Introduction

You work for an online fruits store, and you need to develop a system that will update the catalog information with data
provided by your suppliers. The suppliers send the data as large images with an associated description of the products
in two files (.TIF for the image and .txt for the description). The images need to be converted to smaller jpeg images
and the text needs to be turned into an HTML file that shows the image and the product description. The contents of the
HTML file need to be uploaded to a web service that is already running using Django. You also need to gather the name
and weight of all fruits from the .txt files and use a Python request to upload it to your Django server.

You will create a Python script that will process the images and descriptions and then update your company's online
website to add the new products.

Once the task is complete, the supplier should be notified with an email that indicates the total weight of fruit (in
lbs) that were uploaded. The email should have a PDF attached with the name of the fruit and its total weight (in lbs).

Finally, in parallel to the automation running, we want to check the health of the system and send an email if something
goes wrong.

## What you’ll do

* Write a script that summarizes and processes sales data into different categories
* Generate a PDF using Python
* Automatically send a PDF by email
* Write a script to check the health status of the system

# Module 4 Introduction

Great job, you've made it to the final module! You’ve come so far! Can you believe how much you’ve learned?

In the past few modules, you've seen how you can modify images using Python Imaging Library; how you can interact with
web services using the Python requests module, sending data in JSON format; how you can generate PDF files with the
content you want; and how you can send emails with those PDFs as an attachment.

For the final project in this course, you’ll use the techniques and concepts you've seen to build a solution to a
complex IT task. This can seem a bit daunting at first, but don't worry, you already have all the tools to solve this
task!

In the next couple of readings, we're going to get into what to expect, and some things you should keep in mind when
writing your solution.