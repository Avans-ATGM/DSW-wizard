# DSW-wizard
Storage(backup) of dataknowledge models and document templates





# content #
- 1. how to edit
- 2. how to upload

## 1. how to edit ##

- change template in directory of interest

### 1.1 change document details ####
- nano template.json
- edit variables

### 1.2 change document ###

### 1.2.1 index.html.j2 ###

The index contain the total workflow of the whole document.
To increase clarity are files divided into subfiles.
From this file are the macros and UUIDs imported into the file.
Further in the workflow is style.css called which influence the appearence.
the src/frontpage creates an custome frontpage about the persons who worked on the document/
in src/content is the index of all questions and sub files.

### 1.2.2 content.html.j2  and questions ###

In the content file are the headers and sections described.
Each sections calls the information out of the src/question folder.
The src/questions folder contains all questions are writing of the document generated.
the UUID file parameters are imported into these files to increase clarity.

# 2. upload a document model
- install dsw-tdk
- '' dsw-tdk put ''
- fill in API ( go to the website -> help -> about -> copy api_url
- Username (user email)
- Password

be sure that the template.json is valid and all variables are okay
