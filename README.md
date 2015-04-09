# spawncamping-batman
LaTeX Source Code Listings Generator for lazy people. It uses LaTeX, minted, Pygments, Node JS.


#Installation

This tool requires:

* Node.js - Download and install latest version for your platform from [nodejs.org] (https://nodejs.org/download/)
* minted - See document here for its [installation guide here](https://github.com/gpoore/minted/blob/master/source/minted.pdf)

Run the following command to install latest version of spawncamping-batman.

    $ npm install -g https://github.com/kintesh/spawncamping-batman/tarball/master

Note: You may need to run this command with sudo (i.e. `$ sudo npm install -g https://github.com/kintesh/spawncamping-batman/tarball/master`).


# Usage

    $ spawncamping-batman [options] [source directory]
    
    
    Options:
    
    -h, --help            output usage information
    -V, --version         output the version number
    -i, --ignore [value]  Do not include those files that match the wild-card pattern
    -n, --nofile          Do not output file
    -v, --verbose         Print verbose output on console

--ignore takes regular expression to ignore matched files and folders.


# Licence
---------
Copyright 2015 Kintesh Patel

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.