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
```

<img width="334" height="33" alt="691872256-fe34af08-1f91-4d72-ae7e-bf84c20b7f5e" src="https://github.com/user-attachments/assets/6708b639-28bb-40cd-9a13-ec781a9e5683" />

```
Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
<img width="323" height="40" alt="691872362-d65a9fbf-7451-4fdd-9faf-b32eadc94b33" src="https://github.com/user-attachments/assets/a93f1330-90bc-4264-95b3-59862c1e5387" />
```

Create the file Rose.txt

## COMMAND AND OUTPUT
```
<img width="567" height="406" alt="691872492-8068c18f-f7ae-429a-aaf2-9ce56c5d1c01" src="https://github.com/user-attachments/assets/63d6a9dc-8ce0-4f44-a6eb-348fd1b27d5b" />
```

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
<img width="490" height="93" alt="691873724-19a8e7a3-6f21-44a7-9a10-ecbd9f2492a0" src="https://github.com/user-attachments/assets/e525da48-3055-47ae-a68d-c08bf338814d" />
```
Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
```
<img width="490" height="93" alt="691873881-49f14224-eb21-4e03-80b9-e8260c7400d6" src="https://github.com/user-attachments/assets/bbdf3234-d565-4c6b-8f32-de1a98de8429" />
```

Remove the file hello1.txt

## COMMAND AND OUTPUT
```
<img width="342" height="42" alt="691875345-9677f986-acd2-4c86-8cc9-d5dade4dbb9b" src="https://github.com/user-attachments/assets/1c7f1be1-9762-4028-87ee-8ac5039f4cfd" />
```

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
```
<img width="476" height="625" alt="691875548-7598f03f-3a34-4425-869c-a1fb5034d537" src="https://github.com/user-attachments/assets/4174aeec-f5f8-4d5e-a5f4-9300bd0d9aeb" />
```
List out all the associated file extensions 

## COMMAND AND OUTPUT
```
<img width="513" height="189" alt="691875786-f92e2990-692d-4dee-95e5-26a6b8cd9355" src="https://github.com/user-attachments/assets/f52cb35c-3cd7-4052-b716-60ed2dd11274" />
```

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
```
<img width="387" height="75" alt="691876133-4eca0b53-7874-4569-ade0-d8b4b2bb86f9" src="https://github.com/user-attachments/assets/ce3d49dc-60ea-4965-b105-4348dd96cf59" />
```



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
```
<img width="620" height="232" alt="691876247-029fc714-e3da-49c0-b490-0e90ce8ad003" src="https://github.com/user-attachments/assets/4211138a-10b3-4b68-9c01-1bae21408268" />
```



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
```
<img width="533" height="174" alt="691876369-e4e08f43-d460-4dff-9274-b2007e2b068c" src="https://github.com/user-attachments/assets/56337844-9bba-4c0b-8085-0b0afa4b3632" />
```



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
```
<img width="631" height="193" alt="691876789-05760966-1b3a-480b-a219-07fa6809a512" src="https://github.com/user-attachments/assets/9dd7ab9e-1300-4007-bf2f-f17bd644b78d" />
```

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
```
<img width="505" height="476" alt="691876980-e3c3963d-2e33-46e8-bf1b-b2ad264b1094" src="https://github.com/user-attachments/assets/f8385b6a-bfd0-42e0-9c8e-359eb408a369" />
```


# RESULT:
The commands/batch files are executed successfully.

