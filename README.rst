========================
 Colloquy speech plugin
========================

-----------------------------------------------------
 A text-to-speech plugin for the Colloquy IRC client
-----------------------------------------------------
Forked to add /speech rate, volume commands  

:author: James Tatum, <jtatum@gmail.com>


Installation
============
Drop speech.py into one of these locations::

  ~/Library/Application Support/Colloquy/PlugIns (current user)
  /Library/Application Support/Colloquy/PlugIns (all users)
  /Network/Library/Application Support/Colloquy/PlugIns (all users on the network)

If Colloquy is running, reload the plugin with /reload plugins

Usage
=====
/speech on
  Enable speech. That's pretty much all you have to do to use this plugin.
  The computer will begin speaking every line of text in channel.

/speech off
  Disable the plugin

/speech voices
  Display a list of available voices

/speech voice
  Select a speaking voice, for instance **/speech voice agnes**

/speech nick
  Use **/speech nick on** to enable speaking the nickname before each message.
  This can be disabled with **/speech nick off**

/speech help
  Produce a list of all commands available in the speech plugin.

/speech rate
  Sets the speech rate. Defaults to 200 WPM.  

/speech volume
  Sets the speech volume. 0.0 to 1.0. Default is 0.7
