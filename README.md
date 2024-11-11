# Multithreaded Webserver
## Project Description
Implementation of a webserver that is capable of processing multiple simulatenuous service requests in parallel. The webserver is capable of opening pages in the browser. Implemented using sockets, HTTP requests, threads. Current implementation supports html files, css files, images with gif, jpeg, or png file extension.

## Requirements
- Java Development Kit (JDK)

## Compiling
Compile the java file with

```javac -c Webserver.java```

## Running
Run the compiled java class file using:

```java Webserver```

Then open your web browser and go to ```localhost:6789/index.html```

### URL Explanation 
It is localhost:6789, as the webserver is listening to Port 6789.

And index.html as that is the test file provided with this repository. The second part, index.html, can be replaced with another file as along as the path to that file from where [Webserver.class](Webserver.class) is located is what is replacing index.html.
