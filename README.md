# Internship_Task

ML_Internship_Task1.ipynb

**The task file is a Notebook and can be executed through Google Colab or Anaconda Jupyter**

Important:

How to convert gmail content to mbox for the dataset please follow the instructions given below

This will create data.mbox but since I have downloaded only inbox content thus my filename is Inbox.mbox

Other details are mentioned in the text cell of the Notebook

A few outputs of the code cell execution are deleted for security reason

# Steps get all the contents of Gmail (this task solution was done specific for Gmail):

  1. Login to Gmail
  2. Then got to https://myaccount.google.com/
  3. On left side you will find `Data & personalization menu`, click on it
  4. Then on right side scroll down and you will get `Download, delete, or make a plan for your data` in that you will find `Download your data`, click on it
  
  ![image for step 3 and 4](<https://github.com/mygoal-javadeveloper/Internship_Task/blob/main/mbox1.png>)
  
  To get only Gmail data scroll down to `CREATE A NEW EXPORT` and in that click `Deselect all`, then scroll down to Mail and select the checkbox there
  
  ![alt](<https://github.com/mygoal-javadeveloper/Internship_Task/blob/main/mbox2.png>)
  
  By default it is `MBOX format` that is supported for exporting Gmail. Also by default `All Mail data included` is selected. You can click on this box and select the required folders (Drafts, Inbox, Junk E-mail, sent, etc). I have selected only Inbox for my this task
  
  ![alt](<https://github.com/mygoal-javadeveloper/Internship_Task/blob/main/mbox3.jpg>)

Then scroll down to the bottom of the page and click `Next Step`

![alt](<https://spinbackup.com/blog/wp-content/uploads/2019/04/image-006.jpg>)

Then click on `Create archive`, the mbox will be archive in a .zip file for downloading

![alt](<https://spinbackup.com/blog/wp-content/uploads/2019/04/image-008.jpg>)

Then Archive process begins

Once the archive is completed, it will be avalable for download

Then unzip the downloaded archive and in that you will find Inbox.mbox or data.inbox according to the option selected

For **Google Colab**:

On left side you will find a folder icon click on it and the left-side panel will expand, in that click on upload and upload the mbox file.

For **Jupyter**:

Place the mbox file in the same folder where the Notebook is there.
