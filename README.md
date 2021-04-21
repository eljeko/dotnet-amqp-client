# .net AMQP examples

These examples are tested with dotnet core 3.1.302.

# Producer

## Build

To test this client follow this steps:

1. Clean the project: `dotnet clean`
2. Restore: `dotnet restore`
3. Build: `dotnet build`

## Run the example

Just execute `dotnet run MyQueueName`

Use an existing queue to send messages

# Consumer

The conumser exmple starts and wait for the first message to arrive, then exit.

## Build

To test this client follow this steps:

1. Clean the project: `dotnet clean`
2. Restore: `dotnet restore`
3. Build: `dotnet build`

## Run the example

Just execute `dotnet run MyQueueName`

Use an existing queue to consume messages
