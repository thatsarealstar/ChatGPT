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

The protocol for naming. The usage varies on the way the devs have setup the dataset.

Example: {{name="protocol name"}}

----

#2 - Type

Allows you to specify the type of way you set something up.

Example: {{name="protocol name"}}:{{type="protocol"}}

----

#3 - Reply

Allows you to specify the reply of a protocol.

Example: {{name="protocol name"}}:{{type="protocol"}}:{{reply="Reply with the usage."

----

# Protocol Functions

These are extremely required (especially with same named protocols).

These can be used for configuration of specific protocols.
