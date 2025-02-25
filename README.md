# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/user-attachments/assets/ec211886-ef1e-4fe2-8e2e-c7ad339e5148)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/user-attachments/assets/5b4de9da-3fda-4542-bffb-bce880645053)

![image](https://github.com/user-attachments/assets/8d6cc45f-803f-4430-b9a3-641203e875b1)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/user-attachments/assets/54d438cb-72f0-4b78-9029-6cc599eafb92)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/user-attachments/assets/0fdddb2e-8ac1-4bb4-a032-b476aa555458)

![image](https://github.com/user-attachments/assets/805d075b-8b57-4b90-96d4-28c5ad1c27cf)

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/0228500d-bc7c-4a88-b0d6-fdccc434039f)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

## COMMAND:
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

![image](https://github.com/user-attachments/assets/e9087b32-ac17-4b4d-8f85-7939b03fe79f)

## COMMAND:
```

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```


## OUTPUT
![image](https://github.com/user-attachments/assets/a1da3263-ea0b-45b1-a49b-fa67e7992de4)


# RESULT:
The commands/batch files are executed successfully.


# RESULT:
The commands/batch files are executed successfully.

