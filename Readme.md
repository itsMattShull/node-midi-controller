# NodeJS MIDI Controller

Simple Keyboard to control host software via the browser in real time using Node.JS, Express, Socket.IO and MIDI.

[Video Demo](https://www.youtube.com/watch?v=027eHIw4eAo)

##Why?
Because it's awesome.

## Install
    
- git clone git://github.com/derekshull/node-midi-controller.git
- npm install
- nano public/javascripts/script.js
- Change line 3 to the local IP Address of your computer (leave :3000 unless you changed the port)
- node app.js
- Open up host software (I used Ableton Live 9)
- Go to the settings of the host software and look for the MIDI device RaspberryPi Midi
- Enable it as a controller and load up a sound in the host software
- Point your browser to your local IP Address on port 3000 (Ex: 192.168.0.101:3000)
- Have fun :-)

## License 

(The MIT License)

Copyright (c) 2012 Matt Varone &lt;contact@mattvarone.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
