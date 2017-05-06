# securityspy-tools
Some scripts I use with SecuritySpy for OSX

watch-vtdecoder - detects when the VTDecoderXPCService takes up too much CPU and automatically kills it
kill commands are debounced so they will not run more than once per 5 minutes

cd watch-vtdecoder

npm install

node ./watch-vtdecoder.js
