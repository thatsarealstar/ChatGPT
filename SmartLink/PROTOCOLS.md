# Format:
The format for the protocols.

#1 - {""} (Protocol Requesting)

Well, protocols can have the same names, but you have to specify the type. (Read below for using 'Type.')

Using this, you can request a single protocol if you only have one protocol with the name you need.

Example: I have one protocol named 'Dave', that needs to be loaded instantly. Just do:

{"Dave"}.Start()

(Read below for 'Protocol Functions')

Or, I have two protocols named 'Dave', one of them with type 'protocol' and another one with type 'command'. Just do:

{"Dave"}.Start(config=(type="protocol")

or

{"Dave"}.Start(config=(type="command")

# Protocols:
#1 - Name

Specifies the name of a protocol.

Usage: Names a protocol. Varies for everything.

Example: {{name="protocol name"}}

----

#2 - Type

Allows you to specify the type of way you set something up.

Usage: Can be used with name to specify a protocol and the way it can be used. There are also other ways, but you cannot use 'Type' alone.

Example: {{name="protocol name"}}:{{type="protocol"}}

----

#3 - Reply

Allows you to specify the reply of a protocol.

Usage: It will allow the AI to reply with an answer. Can be used with name and type to name a protocol and to specify a way it can be used. There are also other ways, but you cannot use 'Reply' alone.

Example: {{name="protocol name"}}:{{type="protocol"}}:{{reply="Reply with the usage."

----

# Protocol Functions

These are extremely required (especially with same named protocols).

These can be used for configuration of specific protocols.
