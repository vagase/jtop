
# jtop: Convert JOSN to Plist

## Introduction
This is a command line tool to convert json file to plist format output.

## Installation
You can deploy the binary product to $PATH on your system.

## Usage(OS X)

```jtop xxx.json```  
jtop print output to screen by default.

```jtop xxx.json > xxx.plist;```  
Save to file.

```jtop xxx.json > xxx.plist; if [ 0 == $? ]; then open xxx.plist; fi; ```  
View file instantly. 