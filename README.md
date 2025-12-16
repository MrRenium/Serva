## What is Serva?

- Serva is a hosting system for Linux with which you can easily use it in your Linux operating system and host your desired directory locally.

## Installation

1. Create directory
```mkdir serva```
and
```cd serva```

3. Download Serva
```git clone https://github.com/MrRenium/Serva.git```

4. Config Serva
```sudo mv serva /usr/local/bin```
and
```sudo chmod +x /usr/local/bin/serva```

- Now you have successfully installed Serva on your Linux system

## Example running Serva
- Make directory for your host
```mkdir test```
and
```cd test```

- Now create one HTML file for example
```nano index.html```
and put this code in your HTML file
```<h1>Hello world!</h1>```

- Start the local server with Serva
```serva start -p 80```
This command creates a local server on port 80 in the directory you are in.

- And to log in to the local server using a browser
```http://localhost/```

## Thank you!
