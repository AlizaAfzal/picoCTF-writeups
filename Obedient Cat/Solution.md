# OBEDIENT CAT CHALLENGE SOLUTION

## CHALLENGE OVERVIEW
The objective of this challenge was to retrieve the hidden flag from a provided downloadable file.
The challenge tested basic file analysis and command line investigation skills.

# Method 1: Manual File Inspection
## Step 1: Download the file
the file provided in the challenge was downloaded to the local system.

## Step 2: Open the File
The file was opened using Notepad (text editor)

## Observation
Upon opening the file, the flag was visible in plain text format inside the file content.

<img width="716" height="772" alt="Screenshot (357)" src="https://github.com/user-attachments/assets/e5420fc8-98a3-4943-85ff-cf08db092881" />

# Method 2: Using Command Line (wget and cat)
this method demonstrates command line investigation skills.

## Step 1: Download the File Using wget
wget <file_url>

this command downloads the file directly from the server.

## Step 2: Display File contents Using cat
cat <filename>

the cat command printed the contents of the file to the terminal.

# Observation
The flag was clearly visible in the output.

<img width="764" height="543" alt="Screenshot (358)" src="https://github.com/user-attachments/assets/7f2a7248-98c1-491b-9017-c9dd22d6747e" />

# TOOLS USED
* Browser
* Notepad
* wget
* cat
* Linux Terminal

# CREDIT
Grateful to **CyberConnect** for arranging CTF challenges every Monday and providing valuable hands-on cybersecurity learning opportunities.
