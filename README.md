# node-v8-version

What version of v8 does my node.js use? 

Parses the node.js changelog to find the version of node.js and then walks back through
to find the last mention of a v8 change (upgrade or downgrade)

### Usage:

```
$ npm install -g node-v8-version

# Get last v8 change based on node --version
$ v8v
# => Last V8 change for node v0.12.4 was: update to 3.28.71.19

# Get last v8 change for a specific node version
$ v8v --version=0.10.24
$ v8v -v 0.10.24
# => Last V8 change for node v0.10.24 was: update to 3.14.5.9

# Get last v8 change, version only
$ v8v -s
# => 3.28.71.19
```
