# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
<img width="1033" height="175" alt="image" src="https://github.com/user-attachments/assets/a1586c72-b629-4f9f-81a0-6c6fca579721" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="1070" height="141" alt="image" src="https://github.com/user-attachments/assets/5883852b-0a5e-4bbf-988f-60fd787c94f0" />

## COMMAND AND OUTPUT
Create the file Rose.txt
<img width="1080" height="401" alt="image" src="https://github.com/user-attachments/assets/49bb61a0-2b68-4431-876c-416e3c0beea3" />

## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection
<img width="1615" height="171" alt="image" src="https://github.com/user-attachments/assets/1bcefda4-f54b-415c-8fe8-701fa632fc4d" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="1227" height="150" alt="image" src="https://github.com/user-attachments/assets/e1c92662-1fec-438f-b9de-1408c1c47ecb" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="1350" height="47" alt="image" src="https://github.com/user-attachments/assets/39f8be2c-db62-4f13-a76e-084a7cedf7f4" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="1270" height="220" alt="image" src="https://github.com/user-attachments/assets/a0c24829-9d6f-44ff-80ed-106a76466fb8" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="687" height="765" alt="image" src="https://github.com/user-attachments/assets/5c2ca503-45ba-42de-8724-fe3d7093f6e1" />

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt
<img width="515" height="118" alt="image" src="https://github.com/user-attachments/assets/e36b706d-e085-4ded-8df7-ec088bc153e1" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT
<img width="1057" height="268" alt="image" src="https://github.com/user-attachments/assets/eaff4524-c622-4282-887e-90103f8b1fdc" />
Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.
## OUTPUT
<img width="1061" height="211" alt="image" src="https://github.com/user-attachments/assets/563c7cb8-3cc8-4c69-8858-d84e72f154fd" />
Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.
## OUTPUT
<img width="782" height="148" alt="image" src="https://github.com/user-attachments/assets/25e77aea-1a50-4ab1-8c1b-26253205246b" />
Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="777" height="346" alt="image" src="https://github.com/user-attachments/assets/4c5b8c35-042f-4100-b2e7-d9b5ae64971f" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT
<img width="777" height="346" alt="image" src="https://github.com/user-attachments/assets/1b5c70eb-a958-41d0-8252-690dfd5bd6b8" />

# RESULT:
The commands/batch files are executed successfully.

