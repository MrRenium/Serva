## What is Serva?

- Serva is a hosting system for Linux with which you can easily use it in your Linux operating system and host your desired directory locally.

## Installation

1. Create directory with 
```mkdir serva‍‍‍```
 and 
```cd serva```

3. Download Serva with 
```git clone https://github.com/MrRenium/Serva.git```

4. Config Serva with 
```sudo mv serva /usr/local/bin```
 and 
```sudo chmod +x /usr/local/bin/serva```

- Now you have successfully installed Serva on your Linux system

## Usage
1. Make directory for your host with 
```mkdir test```
 and 
```cd test```

2. Now create one HTML file for example use 
```nano index.html```
 and put this code in your HTML file 
```<h1>Hello world!</h1>```

3. Start the local server with Serva with 
```serva start -p 80```
- This command creates a local server on port 80 in the directory you are in.

4. And to log in to the local server using a browser
```http://localhost/```

- Thank you!
