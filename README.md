# A resource cache implementation

This module implement a resource cache

#LICENSE:

This module is licensed under the Apache License v2.0

# Installation

npm install node-cache

# Include this as a module in your own project

    var Cache = require('node-cache'),
        cache  = new Cache(250,1000*60*60); // One hour

    cache.queue(filename, this, this.loadFromDisk, filename, text, voice, callback);
