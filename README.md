# hello-ballerina
A simple "Hello World" webservice written in [Ballerina](https://ballerina.io).

## Prerequisites
This example requires that you have the [Ballerina Distribution](https://ballerina.io/downloads/) installed.

## Running the Example
1. Run the following command to start the service:

        ballerina run hello_service.bal

    If the service successfully starts you will see the following:

        Initiating service(s) in 'hello_service.bal'
        ballerina: started HTTP/WS endpoint 0.0.0.0:9090

2. In a new terminal window, run the following curl command to test the service:

        curl http://localhost:9090/hello/sayHello

    If successful, you will see the following response:

        Hello World!

3. Next, run the following curl command:

        curl http://localhost:9090/hello/sayHello?name=You

    You should see the following response:

        Hello, You!

## Bugs and Feedback
For bugs, questions, and discussions please use the [Github Issues](https://github.com/gregwhitaker/hello-ballerina/issues).

## License
MIT License

Copyright (c) 2018 Greg Whitaker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.