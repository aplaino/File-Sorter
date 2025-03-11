# File-Sorter

This is a simple Python script that sorts files into designated folders based on their extensions. It scans a specified directory (e.g., the Desktop) and organizes `.csv`, `.png`, and `.txt` files into separate folders:  

### **How It Works:**
1. **Imports Required Modules**: Uses `os` and `shutil` for file and directory operations.  
2. **Defines the Path**: Sets the directory where files need to be sorted.  
3. **Lists Files**: Reads all file names from the specified directory.  
4. **Creates Folders**: If folders for CSV, PNG, and TXT files do not exist, the script creates them.  
5. **Moves Files**: Iterates through the files in the directory and moves them to the respective folders based on their file extensions.  

### **Usage:**
- Update the `path` variable with the directory you want to organize.  
- Run the script, and it will automatically sort the files into `csv files`, `png files`, and `txt files` folders.  

This script can be modified to support additional file types by extending the `folder_names` list and modifying the `if-elif` conditions accordingly.
