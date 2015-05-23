### Peote Telnet - terminal emulation and telnet client

This Library is written in [Haxe](http://haxe.org). Uses [OpenFl/Lime](http://www.openfl.org/documentation/setup/install-haxe/)
to run on multiple hardware devices.


####Depends
[peote-socket](https://github.com/maitag/peote-socket) and [peote-view](https://github.com/maitag/peote-view)
(please download this first)

####Build

(first look into peoteTelnetClient.lime file where external sources are!)


#####native OS:

`$ lime build peoteTelnetClient.lime linux  (android/windows)`



#####Javascript/WebGL:

`$ lime build peoteTelnetClient.lime html5`

see html5-test folder how to get it run with flash raw socket (PeoteSocketBridge.swf)

####Why another Terminal Emulation ?

- use power of haxe-lime multiplatform code generation
- build mud-clients ;)

####Todo

- configfile for server/port
- outsource code to display textarea into peote-view
- more control commands (keyboard-input)
- local echo switch
- ansi-colors
- reconnect socket