# Basic Authenticated HTTP Request in Rust

This is a simple Rust project that demonstrates how to send an authenticated HTTP GET request using the `reqwest` library.

## Functionality

The program creates a new HTTP client and sends a GET request to a specified URL. The request is sent with Basic Authentication headers. For simplicity, we're using a fixed username "testuser" and no password. 

Please note that the current URL we're using, `http://httpbin.org/get`, is only a placeholder and doesn't actually require authentication. 

The program then prints the HTTP response to the console. The printed response includes the HTTP status and headers, and other metadata about the response.

## Running the Program

Assuming you have Rust installed, you can run the program using the following command:

```bash
cargo run
```

## Dependencies

This project uses the following Rust crate:

- `reqwest` - for creating the HTTP client and sending the request.

## Future Improvements

This project is a simple demonstration and as such, there are many possible improvements:

- Adding error handling for the HTTP request.
- Allowing the user to specify the URL, username, and password.
- Processing the HTTP response body instead of just printing it.

