# An Introduction to JSON Web Tokens

#### By Abdullah Alwael.

# What is JSON?
JSON is an abbreviation of JavaScript Object Notation, a standardized way of sending value-pair values over the internet between two computers. 

# What is a Token?
A token is an identifier string used primarily in a stateless network connection between a computer and a server. The network standard of today’s communication is called TCP/IP which is a transmission control protocol that sends and receives network chunks of data called packets over the very first Internet Protocol standard. It is used to “remember” the user even when the network connection gets interrupted between the computer and the server.

# What makes JSON Web Tokens Different?
With JSON Web Tokens, JSON objects are used to construct multiple identification data into one token. It usually consists of three JSON objects encoded with 64Bit encoding standard each separated by a dot (.).

# Benefits of using JSON Web Tokens
Tokens in the past were constructed using many ways for sending useful machine readable data such as XML or SAML, but they require longer strings to encode into 64bit strings. This makes JSON Web Tokens way more compact and faster to transmit even on slow network connections. 

They can also be used for authentication, authorization, and data transmission. They can be secured by further encoding or encrypting them into different string representations. Finally, the entire string can be digitally signed by a certificate authority to make it tamper-free and easily identify its legitimate owner.

# The Structure of a JSON Web Token
The three (dot . separated) data a JSON Web Token help transfer are:

  - Header, stores data that identifies the type of token it is, and the encryption algorithms used to secure the contained data.
  - Payload, the payload stores the actual data to be transferred on the network.
  - Signature, the signature is what identifies if the data was changed while transferring the token.
