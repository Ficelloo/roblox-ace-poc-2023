# Roblox RCE (2023)

# BEFORE STARTING: This vulnerability can be executed ONLY if you patch the client or the server script level identity, this isn't possible to do that if you didn't patch it

Hi! someone named "7ap" found a way to execute pc's app by abusing "MessageBusService" service on roblox, he used the GetMessageId function from this service by setting "domainName" parameter to 'calc.exe' or even 'notepad.exe', here is the video: 

![7zapgif](https://cdn.discordapp.com/attachments/839412308467384330/1089132890585047131/4cUoGJj.gif)

# How?

I think 7ap did that by patching the level indentity on the server side, this is why he can execute that on the server command bar.

# Client vulnerability

Me and my friend found a way to do the exact thing by patching the script identity level on the actual roblox client by editing the function in the memory and setting the level to '0' instead of '5', And now we can actually exploit this vulnerability on the REAL roblox without being frozen unlike 7ap's server patched.

here is our video:

![vid](./Animation.gif)

# What tools used here to reproduce 7ap's vuln?

https://github.com/ElCapor/lego-exploder made by mogus#2891 with a bit of Ficello.zip#9910 help

# Credits:
7ap#8640
mogus#2891
Ficello.zip#9910
