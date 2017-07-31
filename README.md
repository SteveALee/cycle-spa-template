# cycle-spa-template
A cycleJS template for a SPA. Each page is a cycle component and has its own state, which is persisted in local storage

Adds use of these cycle packages to the [create-cycle-app one-fits-all](https://github.com/cyclejs-community/create-cycle-app-flavors/tree/master/packages/cycle-scripts-one-fits-all) flavor:
* cycle-onionify and @cycle/isolate for fractal single state atom 
* cycle-storageify and @cycle/storage for persistence in browser local storage
* cyclic-router and switch-path for routing and history management
* Custom speech driver (write only)
