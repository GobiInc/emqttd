Global Flirt
============

This is the fork of Emqttd for Global Flirt. It supports a build with
two custom plugins, EmqttdTranslate and EmqttdAuthDynamoDB.

This was working until recently, when Emqttd upgraded. The upgrade removed
the plugins directory and was (it would seem) a complete overhaul of the build
process. This project was mothballed while I was probably 75% of the way
through figuring out how to get the custom plugins to build with the new
build process. The old build process broke because a dependency (jsone) seemed
to fetch a latest version but required a specific version.

https://github.com/GobiInc/EmqttdTranslate

https://github.com/GobiInc/EmqttdAuthDynamoDB

Note that emqttd has releases in their own github repo. Likely this should
not be based on emqttd but emqttd-relx


https://github.com/emqtt/emqttd-relx

