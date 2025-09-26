#README.md
# Install
. Git
. DB Browser for SOLite

# Linux command
mkdir [folder.name] #create new folder in current directory
cd [folder.name] # go to next level folder in cuurnet directory
cd .. # go to 1 stage high root of current directory
ls # show file and folder list of current directory

# Initialize Enviroment
in terminal :
. git --version
. git config --global user.name 'Ya-Fan Hsiao'
. git config --global user.email 'lisa100177@gmail.com'
. git init

# Common Used Instruction
. git status
. git log --oneline

# Track File and Folder
create a new README.md file, ctrl + s
. git add [full file name]
. git add *.file_sub_name
. git add .
. git commit -m 'message'

# Supplementary: others instruction of modify file
. git reset --soft HEAD~ #回到上一步/canceling commit
. git reset --hard [version.number]
. git diff [version.number] -- [filename]
. git checkout [version.number] -- [filename]