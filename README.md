# About sshhttptunnel

Creates a seamless tunnel between SSH and HTTP connections across the globe. It leverages the power of Go channels and the io.Copy() function for efficient data transfer.

To start the tunnel, simply execute the following command in your terminal:

```sh
go run main.go
```

Testing the Tunnel

To test the functionality, you can pipe the contents of main.go as input to an SSH session:

```sh
ssh localhost -p 2222 < main.go
```

This command connects to the SSH server running on localhost at port 2222 and uses the main.go file as the data source.
