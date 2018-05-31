# Sublime Text Build system to Python 3

## 1. Go to Sublime Text to: Tools -> Build System -> New Build System 
and put the next lines:

{
    "cmd": ["python3", "-i", "-u", "$file"],
    "file_regex": "^[ ]File \"(...?)\", line ([0-9]*)",
    "selector": "source.python"
}

Then save it with a meaningful name like: python3.sublime-build

## 2. Go to Tools -> Build system -> and check python3 

test it with:

 - import sys
 -print(sys.version)

`Press: Ctrl + b `
