# IvycdkAccordion

> app@0.0.0 ngcc-compile /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion
> ngcc -t ./@angular/cdk/accordion --async -l debug -p esm5 esm2015

Debug: Running ngcc on ClusterExecutor (using 8 worker processes).
Debug: Analyzing entry-points...
Debug: Analyzed 3 entry-points in 1s. (Total tasks: 6)
Debug: Processing tasks...
Debug: All 1 workers are currently busy and cannot take on more work.
Debug: All 2 workers are currently busy and cannot take on more work.
Debug: No assignments for 1 idle (out of 3 total) workers. Busy workers: 1, 2
Debug: No assignments for 2 idle (out of 4 total) workers. Busy workers: 1, 2
Debug: No assignments for 3 idle (out of 5 total) workers. Busy workers: 1, 2
Debug: No assignments for 4 idle (out of 6 total) workers. Busy workers: 1, 2
Debug: No assignments for 5 idle (out of 7 total) workers. Busy workers: 1, 2
Debug: No assignments for 6 idle (out of 8 total) workers. Busy workers: 1, 2
Compiling @angular/core : esm2015 as esm2015
Compiling @angular/core : esm5 as esm5
Debug: No assignments for 7 idle (out of 8 total) workers. Busy workers: 1
Debug: No assignments for 6 idle (out of 8 total) workers. Busy workers: 1, 2
Compiling @angular/cdk/collections : esm2015 as esm2015
Compiling @angular/cdk/collections : esm5 as esm5
Debug: No assignments for 7 idle (out of 8 total) workers. Busy workers: 1
Debug: No assignments for 6 idle (out of 8 total) workers. Busy workers: 1, 2
Compiling @angular/cdk/accordion : esm2015 as esm2015
Debug: Stopping 8 workers...
Error: Error on worker #2: Error: Unable to write a reference to CdkAccordion in /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/cdk/esm2015/accordion/accordion.js from /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/cdk/esm2015/accordion/accordion-module.js
    at ReferenceEmitter.emit (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/src/ngtsc/imports/src/emitter.js:54:19)
    at Object.toR3Reference (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/util.js:165:31)
    at NgModuleDecoratorHandler._toR3Reference (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/ng_module.js:345:31)
    at /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/ng_module.js:173:83
    at Array.map (<anonymous>)
    at NgModuleDecoratorHandler.analyze (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/src/ngtsc/annotations/src/ng_module.js:173:48)
    at Object.analyzeDecorators (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/analysis/util.js:75:38)
    at DecorationAnalyzer.analyzeClass (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/analysis/decoration_analyzer.js:138:40)
    at /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/analysis/decoration_analyzer.js:131:55
    at Array.map (<anonymous>)
    at ClusterMaster.onWorkerMessage (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:158:27)
    at /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:46:95
    at ClusterMaster.<anonymous> (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:238:57)
    at step (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/tslib/tslib.js:136:27)
    at Object.next (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/tslib/tslib.js:117:57)
    at /Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/tslib/tslib.js:110:75
    at new Promise (<anonymous>)
    at Object.__awaiter (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/tslib/tslib.js:106:16)
    at EventEmitter.<anonymous> (/Users/dmitry.vasiliev/Desktop/forReproduce/IvycdkAccordion/node_modules/@angular/compiler-cli/ngcc/src/execution/cluster/master.js:232:32)
    at EventEmitter.emit (events.js:193:13)
Compiling @angular/cdk/accordion : esm5 as esm5
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! app@0.0.0 ngcc-compile: `ngcc -t ./@angular/cdk/accordion --async -l debug -p esm5 esm2015`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the app@0.0.0 ngcc-compile script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/dmitry.vasiliev/.npm/_logs/2019-11-01T10_23_03_238Z-debug.log
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! app@0.0.0 postinstall: `npm run ngcc-compile`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the app@0.0.0 postinstall script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/dmitry.vasiliev/.npm/_logs/2019-11-01T10_23_03_302Z-debug.log
