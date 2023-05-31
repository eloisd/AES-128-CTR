# READ ME

The main goal of this projet is to encrypt messages using AES (Advanced Encryption Standard) with a key and an iv (Initial Vector) of 128 bits. 

The thing which is <span class="text-danger">**interesting**</span> is that this code <span class="text-danger"> bb **does not use any cryptograpfy package**</span>.

# Installation

## Step 1
You will need node.js, here are the command to run in your terminal.
Here are some ways to do it manualy. 

### Ubuntu

```
$ sudo apt update
$ sudo apt install Node.js
```

### MacOS

#### Using Homebrew
```
$ brew install node
```
If you do not have brew run this before and go drink a coffee, it will take some time. 
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Windows

#### Using Winget
```
$ winget install OpenJS.NodeJS
```

## Step 2
Clone my project to use it on your computer
```
$ git clone https://github.com/eloisd/git-test/
```

## Step 3
Go inside the directory.
```
$ cd AES-128-CTR
```

## Step 4
Install the 'readline' package
```
$ install.packages('readline')
```

## Step 5
Run the code.
```
$ node aes128ctr.js
```