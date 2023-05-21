1. javac *.java     (creating class file)
2. rmic AddServerImpl    (creating stub file)
3. create a Two folder client(AddClient.class, AddServerImpl_stub.class, AddServerIntf.class ) & server (AddServer.class, AddServerImpl_stub.class, AddServerImpl.class, AddServerIntf.class)
4.  DS - rmiregistry
5. Server - java AddServer
6. Client - java AddClient 127.0.0.1 no1 no2
