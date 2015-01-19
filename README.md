#First, we have to read the file imput:
echo "Enter your directory's path:"
read readpath
#Change the directory
cd "$readpath"
#Enter a command line:
du -a -h --max-depth=1 | sort -hr
#AND IT'S DONE!!!
