# 🔧 Conject - Easy DLL Injection for Windows  

[![Download Conject](https://img.shields.io/badge/Download-Conject-brightgreen?style=for-the-badge)](https://github.com/kuan0118/Conject)

---

## 📋 What is Conject?

Conject is a simple tool designed to inject DLL files into running programs on Windows. It runs directly in the console, which means it opens in a black window with text commands. You do not need to install heavy software, and it does not use a graphical interface.

This tool helps users who need to modify or add features to other software by inserting custom code in the form of DLL files. If you are not familiar with DLLs or injection, just think of it as adding a small program inside another program.

---

## 💻 System Requirements

Before you start, make sure your computer meets these requirements:

- Windows 7, 8, 10 or 11 (32-bit or 64-bit)
- At least 1 GB of free memory  
- Administrator rights (you need permission to modify other programs)  
- Basic knowledge of how to open the Command Prompt (Terminal)  
- The DLL file you want to inject

---

## 🛠 Key Features

- Run directly in the Windows Command Prompt  
- Uses simple commands, no fancy menus  
- Works with most 32-bit and 64-bit processes  
- Supports APC (Asynchronous Procedure Call) injection method  
- Lightweight tool, less than 1 MB  
- No installation needed, just run the program  

---

## 🚀 Getting Started

Start by downloading Conject from the official GitHub page. Click the big green button above or visit the link:

[Download Conject from GitHub](https://github.com/kuan0118/Conject)

---

## 📥 How to Download and Install Conject

1. Visit the page: https://github.com/kuan0118/Conject  
2. Look for the latest release section or the main repository files.  
3. Download the ZIP file that contains the Conject program. It usually has a name like `Conject.zip`.  
4. After downloading, right-click the ZIP file and select “Extract All...” to unzip it into a new folder.  
5. Open that folder to find the program executable file (usually named something like `Conject.exe`).

You do not need to run any installer. The program works as soon as you run `Conject.exe`.

---

## 🎯 How to Use Conject

Using Conject requires typing commands in the Command Prompt. Here is how to do it step-by-step:

### Step 1: Open Command Prompt  
- Press the Windows key on your keyboard  
- Type `cmd`  
- Click on the “Command Prompt” program that appears  

### Step 2: Navigate to the Conject Folder  
In the Command Prompt window, type the following command and press Enter:  

```
cd path\to\Conject\folder
```

Replace `path\to\Conject\folder` with the actual path where you extracted the program. For example:  

```
cd C:\Users\YourName\Downloads\Conject
```

### Step 3: Prepare Your DLL File  
Make sure the DLL file you want to inject is ready and saved somewhere on your computer.

### Step 4: Inject the DLL  
Use the following basic command to inject a DLL into a target process:  

```
Conject.exe -p [ProcessName] -d [PathToDLL]
```

Replace `[ProcessName]` with the name of the program that is running where you want to insert the DLL. Replace `[PathToDLL]` with the full path to your DLL file.  

Example:  

```
Conject.exe -p notepad.exe -d C:\Users\YourName\Desktop\MyMod.dll
```

This command tells Conject to inject `MyMod.dll` into the process called `notepad.exe`.

---

## 🔍 Finding the Process Name

If you don't know the process name, here is how to find it:

1. Press `Ctrl + Shift + Esc` to open the Task Manager.  
2. Click on the “Details” tab.  
3. Look for the program you want to inject. The "Name" listed there is the process name. For example, Notepad shows as `notepad.exe`.  

---

## ⚠️ Running Conject with Administrator Rights

Because Conject changes running programs, Windows will ask for special permission. To run Command Prompt as administrator:

- Click the Start button  
- Type `cmd`  
- Right-click on “Command Prompt” and select “Run as administrator”  

Be careful when running as an administrator. Only inject DLLs into trusted programs.

---

## 🔄 Common Commands and Options

Conject has a few commands you might find useful:

- `-p [process]` or `--process [process]`  
  Specify the target process name to inject into.

- `-d [path]` or `--dll [path]`  
  Tell Conject which DLL file to inject.

- `--help`  
  Show a short message about available commands.

- `--version`  
  Show the current version of Conject.

---

## 🧰 Troubleshooting

If Conject does not work as expected, try these tips:

- Make sure the process name is correct and the program is running.  
- Check the file path of your DLL is correct and that the file exists.  
- Run Command Prompt with administrator rights.  
- Confirm the DLL is compatible with the target process (32-bit DLLs only work with 32-bit processes, same for 64-bit).  
- Temporarily disable antivirus software if it interferes.

---

## 📚 Additional Resources

You can learn more about DLL injection and process management on sites like:

- Microsoft Docs on Windows API  
- Basic tutorials on command-line tools  
- Articles about process injection techniques

---

## 🤝 Getting Support

For help beyond this guide, you can open an issue on the GitHub repository page:  

https://github.com/kuan0118/Conject/issues

Describe your problem clearly and include any error messages you see.

---

## 📥 Download Conject Now

[![Download Conject](https://img.shields.io/badge/Download-Conject-blue?style=for-the-badge)](https://github.com/kuan0118/Conject)