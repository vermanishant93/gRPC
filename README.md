# gRPC
  - Google Remote Procedure Call
  - Uses HTTP/2 protocol to transport binary messages (inc TLS)
  - High Performance
  - Relies on Protocol Buffers aka Protobuf to define contracts between endpoints
  - Multi-language support (C# can call a Ruby Service)
  - gRPCs field names are in snake case: 
      -string to_do_status = 4;

# Commands
  - dotnet new grpc -o ToDoGrpc
  - dotnet ef migrations add AddMigrations
  - dotnet ef database update

### Added gRPC annotations to use HTTP Equivalent endpoints using annotation files
