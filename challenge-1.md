----------------------------------------

# Print the last 5 lines of "access.log".

=> tail -n 5 access.log
=> tail -5 access.log

# Copy the file named m2-0922-cli to the directory tmp/files/ciccc

=> cp m2-0922-cli tmp/files/ciccc

# Delete all of the files in this directory including all subdirectories and their contents.

=> rm -r .* *

# There are files in this challenge with different file extensions. Remove all files with the .doc extension recursively in the current working directory.

=> rm -r **/*.doc