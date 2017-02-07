---
-api-type: winrt class
---
 Create the [StreamSocket](streamsocket.md).
 Get a [StreamSocketControl](streamsocketcontrol.md) object using the [Control](streamsocket_control.md) property and set any properties on the [StreamSocketControl](streamsocketcontrol.md) object before calling one of the [ConnectAsync](streamsocket_connectasync.md) methods.
 Call one of the [ConnectAsync](streamsocket_connectasync.md) methods to establish a connection with the remote endpoint. For Bluetooth, the remote service name is a Bluetooth Service ID. If an SSL/TLS connection for TCP or a level of encryption for Bluetooth is required immediately, this can be specified using some of the [ConnectAsync](streamsocket_connectasync.md) methods. If an SSL/TLS connection is desired after sending and receiving some initial data for a TCP socket, then the [UpgradeToSslAsync](streamsocket_upgradetosslasync.md) method can be called later to upgrade the connection to use SSL.
 Get the [OutputStream](streamsocket_outputstream.md) property to write data to the remote host.
 Get the [InputStream](streamsocket_inputstream.md) property to read data from the remote host.
 Read and write data as needed.
 Call the [Close](streamsocket_close.md) method to disconnect the socket, abort any pending operations, and release all unmanaged resources associated with the [StreamSocket](streamsocket.md) object.