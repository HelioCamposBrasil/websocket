# File Watch example.

This example sends a file to the browser client for display whenever the file is modified.

    $ go get github.com/HelioCamposBrasil/websocket
    $ cd `go list -f '{{.Dir}}' github.com/HelioCamposBrasil/websocket/examples/filewatch`
    $ go run main.go <name of file to watch>
    # Open http://localhost:8080/ .
    # Modify the file to see it update in the browser.
