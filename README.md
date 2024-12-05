Bygone Backend
By Niko Norwood

Basic NodeJS Library that adds some funtionality for basic web servers.

Features
  Unified console output with output logged in a TXT
  Ability to cache a JS object using a JSON File (read to and from)

Usage 

object = new bygone.cachedFile("file.json")
bygone.output("console output");
bygone.debugOutput("hidden console output")