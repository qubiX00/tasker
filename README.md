# Tasker
Simple task manager written in Bash, with [eww](https://github.com/elkowar/eww) in mind

# Installation
First Method (recommended)
```
git clone https://github.com/qubiX00/tasker.git && cd tasker
chmod +x tasker
sudo mv tasker /usr/local/bin/
```
Second Method
```
Copy Source Code to File named tasker 
chmod +x tasker
sudo mv tasker /usr/local/bin/
```

# Usage
CLI
Listing all tasks:
```
tasker --listall
```
Display how much tasks you have:
```
tasker --count
```
Making a task:
```
tasker --make <id> <name> <due date>
```
Example:
```
tasker --make 1 "go buy grocceries" 16-06-2023/11:50
```
Marking task as finished
```
tasker --finish <id>
```
Example:
```
tasker --finish 1
```
Deleting task:
```
tasker --delete <id>
```
Example
```
tasker --delete 1
```
EWW
Coming soon!
