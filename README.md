# Lock Folder on Windows (Vulnerable Solution)

## Steps
1. Open the `.bat` file in a text editor (e.g., Notepad).
2. Find and replace `PASSWORD_HERE` with your own password.
3. Save and close the file.
4. Run the `.bat` file. This will create a folder named `Locker`.
5. Place your files into the `Locker` folder.
6. Run the `.bat` file again to lock the folder. To unlock, run the `.bat` file and enter your password.

## Why is it Vulnerable?
- The password can be easily viewed and edited by anyone with access to the `.bat` file, making the protection weak.

## How to Mitigate the Vulnerability
- Compress the `.bat` file into a WinRAR `.zip` or `.rar` archive and protect the archive with a strong password.
- When you need to access your locker:
  1. Extract the `.bat` file from the archive.
  2. Run the `.bat` file in the original location where the `Locker` folder was created.
  3. The `.bat` file will make the `Locker` folder visible.
  4. After accessing your files, repeat the process to lock the folder again.

### Note
- Ensure you remember the password for the archive to avoid being locked out of your files.

## Disclaimer
- This code is sourced from a third party, and I did not write it myself.
