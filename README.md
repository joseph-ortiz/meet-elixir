# meet-elixir
- Create an Elixir Project with mix
- Write an inital unit test
- Understand the power of assert in Elixir
- Start implementing the Streamers module

## Lesssons
>Part of the Erlang philosophy is we don't want to use exceptions as flow control.
- In the world of networking, when communicating to a node, it won't be there.
 - An error is a common use case.
- In elixir, executing a File.open(/1) would result in a tuple giving the status and the content.
- Adding a bug  after a method name, it gives you more detailed error message
- I/O does not block in erlang, To create a file, Erlang rrates a new process which runs concurrently with other processes.

### Testing
- Elixir has a difference between documentation and code comment. code comments are for the audience of the developer working on the code. docs are for the audience of the consumer of the code
- doctests are the ability to add tests as docuemtnation in the code. these tests can be executed when running your other tests. 
 - doctests are self contained tests. You should be able to copy and paste code into  a REPL 
 - normal tests should exist with explicit test cases and data.
- Elixir generates byte code

### Input

