**Task 1:**
# Create directory and open
"mkdir my_folder"
cd my_folder
# Create my_file.txt
cat > my_file.txt
# Add some line in same text file
cat >> my_file.txt
# Create another_file.txt
cat > another.txt
# Concatenate the content of ""another_file.txt"" to ""my_file.txt""
cat another_file.txt >> my_file.txt
# output display the updated content
cat my_file.txt
# List all files and directories in the current directory
ls- l
**Task 2:**
# Create directory and open
mkdir task2_folder
cd task2_folder
# Create 20 files with .txt extensions 
touch file{1..20}.txt
# rename the first 5 files to .yml
 for i in {1..5}; do mv file$i.txt file$i.yml; done
 # Print the latest created top 5 files among the total no of files
 ls -t | head -n 5
