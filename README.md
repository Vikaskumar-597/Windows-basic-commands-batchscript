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

## COMMAND AND OUTPUT
<img width="512" height="299" alt="image" src="https://github.com/user-attachments/assets/d7966f99-96d9-44d7-b696-1f8dc431a4a8" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="513" height="285" alt="image" src="https://github.com/user-attachments/assets/7c9dd445-dc39-4688-87e9-ecb7f03603aa" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="538" height="117" alt="image" src="https://github.com/user-attachments/assets/c49d3c48-357a-4502-9ba2-3375b2075b4d" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="618" height="81" alt="image" src="https://github.com/user-attachments/assets/707f8cdf-9896-4d26-a9b7-a80c76bb4653" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="593" height="104" alt="image" src="https://github.com/user-attachments/assets/73d53759-7276-4b80-b576-84e7b54addf4" />


Remove the file hello1.txt
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="520" height="140" alt="image" src="https://github.com/user-attachments/assets/2f8fec50-59b8-4ac8-83d6-c5309aebdf1a" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="486" height="329" alt="image" src="https://github.com/user-attachments/assets/dc114deb-0e78-4e0b-a4fb-43fef42d0367" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="572" height="152" alt="image" src="https://github.com/user-attachments/assets/149582cf-ec74-49d0-a2e6-47825e675445" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT
<img width="429" height="69" alt="image" src="https://github.com/user-attachments/assets/b5ce63a6-0949-407f-a026-ecc23c71d24e" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="422" height="171" alt="image" src="https://github.com/user-attachments/assets/e296d5ad-fff9-455c-b3c6-c9a35a61b3b1" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="429" height="135" alt="image" src="https://github.com/user-attachments/assets/3fed2bf3-50d4-46fd-97b5-f239c416a66b" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="427" height="67" alt="image" src="https://github.com/user-attachments/assets/1cfa996c-13d3-4489-bf10-4ed33beb4990" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="435" height="311" alt="image" src="https://github.com/user-attachments/assets/898164b9-0da2-4dfd-9bd5-7e82a6c05497" />


# RESULT:
The commands/batch files are executed successfully.

