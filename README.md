# Roblox RCE (2023)

# BEFORE STARTING: This vulnerability can be executed ONLY if you patch the client or the server script level identity, this isn't possible to do that if you didn't patch it

Hi! someone named "7zap" found a way to execute pc's app by abusing "MessageBusService" service on roblox, he used the GetMessageId function from this service by setting "domainName" parameter to 'calc.exe' or even 'notepad.exe', here is the video: 

![7zapgif](https://cdn.discordapp.com/attachments/839412308467384330/1089132890585047131/4cUoGJj.gif)

# How?

7zap did that by patching the level indentity on the serverside, this is why he can execute that on the server command bar.
