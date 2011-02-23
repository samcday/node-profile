# node-profile

A script that makes profiling node.js apps a little easier.

## Installation

Via [npm](http://github.com/isaacs/npm):

    $ npm install profile

## Usage
### Output to stdout
`> nodeprofile yourapp.js`
### Output to file
`> nodeprofile yourapp.js -o=profile.txt`
### Lazy profiling (profiling disabled on startup)
This is useful if you want to profile certain areas of your code using [bnoordhuis/node-profiler](https://github.com/bnoordhuis/node-profiler):

`> nodeprofile yourapp.js --prof_lazy`

## "Dependencies"
* python
* That the `locate` command can find a copy of `linux-tick-processor.py` (bundled with node.js)

## Output

<img src="http://mape.me/nodeprofile.png" alt="">
