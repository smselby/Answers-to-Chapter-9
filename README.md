1.	What is the difference between shutil.copy() and shutil.copytree()?
Answer: shutil.copy() copies a single ﬁle, 
 shutil.copytree() copies an entire folder, with all its contents
2. What function is used to rename ﬁles?
Answer: shutil.move() is used for renaming ﬁles, as well as moving them
3.	What is the difference between the delete functions in the 
send2trash and shutil modules?
Answer: send2trash will move a ﬁle or folder to the recycle bin, shutil will permanently delete ﬁles and folders 
4.	ZipFile objects have a close() method just like File objects’ close() 
method. What ZipFile method is equivalent to File objects’ open() method?
Answer: zipfile.ZipFile() is equivalent to the open(); the ﬁrst argument is the ﬁlename, and the second argument is the mode to open the ZIP ﬁle in (read, write, or append)
