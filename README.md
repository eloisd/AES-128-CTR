# READ ME

The main goal of this projet is to encrypt messages using AES (Advanced Encryption Standard) with a key and an iv (Initial Vector) of 128 bits. 

The thing which is <span class="text-danger">**interesting**</span> is that this code <span class="text-danger"> bb **does not use any cryptograpfy package**</span>.

# Installation

### STEP 1
You will need node.js et npm, here are the command to run in your terminal.
Here are some ways to do it manualy. 

### Ubuntu

```
$ curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - sudo apt install -y nodejs
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

### STEP 2
Clone my project to use it on your computer
```
$ git clone https://github.com/eloisd/git-test/
```

### STEP 3
Go inside the directory.
```
$ cd AES-128-CTR
```

### STEP 4
Install the 'readline' package
```
$ npm install readline
```

### STEP 5
Run the code.
```
$ node aes128ctr.js
```