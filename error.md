> 01_jsdn@1.0.0 test /home/pink/Projects/mocha_chai_sandbox/01_jsdn
> mocha --compilers js:babel-register

/home/pink/Projects/mocha_chai_sandbox/01_jsdn/src/index.js:1
(function (exports, require, module, __filename, __dirname) { export class PrimeChecker {
                                                              ^^^^^^

SyntaxError: Unexpected token export
    at createScript (vm.js:56:10)
    at Object.runInThisContext (vm.js:97:10)
    at Module._compile (module.js:549:28)
    at loader (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/babel-register/lib/node.js:144:5)
    at Object.require.extensions.(anonymous function) [as .js] (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/babel-register/lib/node.js:154:7)
    at Module.load (module.js:494:32)
    at tryModuleLoad (module.js:453:12)
    at Function.Module._load (module.js:445:3)
    at Module.require (module.js:504:17)
    at require (internal/module.js:20:19)
    at Object.<anonymous> (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/test/tests.spec.js:9:1)
    at Module._compile (module.js:577:32)
    at loader (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/babel-register/lib/node.js:144:5)
    at Object.require.extensions.(anonymous function) [as .js] (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/babel-register/lib/node.js:154:7)
    at Module.load (module.js:494:32)
    at tryModuleLoad (module.js:453:12)
    at Function.Module._load (module.js:445:3)
    at Module.require (module.js:504:17)
    at require (internal/module.js:20:19)
    at /home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/mocha/lib/mocha.js:231:27
    at Array.forEach (native)
    at Mocha.loadFiles (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/mocha/lib/mocha.js:228:14)
    at Mocha.run (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/mocha/lib/mocha.js:536:10)
    at Object.<anonymous> (/home/pink/Projects/mocha_chai_sandbox/01_jsdn/node_modules/mocha/bin/_mocha:582:18)
    at Module._compile (module.js:577:32)
    at Object.Module._extensions..js (module.js:586:10)
    at Module.load (module.js:494:32)
    at tryModuleLoad (module.js:453:12)
    at Function.Module._load (module.js:445:3)
    at Module.runMain (module.js:611:10)
    at run (bootstrap_node.js:387:7)
    at startup (bootstrap_node.js:153:9)
    at bootstrap_node.js:500:3
npm ERR! Test failed.  See above for more details.