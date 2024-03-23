# gRPC HelloWorld Example

This project is a simple example of a gRPC service using Protocol Buffers (protobuf) in Java. It uses Maven as a build tool.

## Project Structure

The main components of the project are:

- `src/main/proto/helloworld.proto`: This is the Protocol Buffers (protobuf) file that defines the `Greeter` service and the `HelloRequest` and `HelloReply` message types for the gRPC service.

- `Greeter` service: This service has two methods: `SayHello` and `SayHelloAgain`. Both methods take a `HelloRequest` message as input and return a `HelloReply` message.

- `HelloRequest` and `HelloReply` messages: These are the request and response message types. Each `HelloRequest` message has three fields: `firstName`, `lastName`, and `email`. The `HelloReply` message has a `message` field.
  
   NB: you can change these fileds in the client code (HelloWorldClient.java).
  
## How to Run

To run this project, you need to have Java and Maven installed on your machine. Then, you can clone this repository and run the following command in the project directory:

```bash
mvn clean install
