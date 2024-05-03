# wsdlfirstws

--------Git----------------
echo "# wsdlfirstws" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/moumitacloud08/wsdlfirstws.git
git push -u origin main

------WSDL File----------

Type − WSDL files type section is used to define the data types that will be used in the web service operations and they are defined in XMLSchema

The message section defines the data elements that are being exchanged between the web service provider and the service user.
(similar to java parameters and return types)

The portType section describes a set of operations(methods in java) that can be performed by the web service.It defines the abstract interface for the service,
 listing the operations along with their input  and output  messages.
 
 The binding section(what types of SOAP messages will go in and come out) specifies how the abstract operations defined 
 in portType are mapped to a concrete protocol for communication.It defines details such as the message format and the protocol (e.g., SOAP).
  
  The port section specifies the network address where the web service can be accessed.

  