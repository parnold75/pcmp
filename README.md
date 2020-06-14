# pcmp
Pcmp creates a hash value from every file in the target directory and stores it in a tree. Afterwards the source-directory is searched and the hash-value of every file is compared with the hash-value of the target-directory. If the hash-value is not in the target-directory, the complete file-path of the source-directory will be output to standard output. 
