```
yarn
yarn tsc
node example.js

TypeError: AwaitLock is not a constructor
    at file:///home/kaspar/projects/await-lock/repro/example.js:2:14
    at ModuleJob.run (node:internal/modules/esm/module_job:192:25)
    at async DefaultModuleLoader.import (node:internal/modules/esm/loader:228:24)
    at async loadESM (node:internal/process/esm_loader:40:7)
    at async handleMainPromise (node:internal/modules/run_main:66:12)

```
