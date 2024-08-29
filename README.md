# simpleTF
Simplified SDK to operate tensorflow.js

This would be about a module that is triggered by the **consumption of an object** of the type discussed below.

## Taking notes ...
Praful, starting the conversation, where you worry about the TF spaguetti and I worry about the eadability of that object in the [ARPA-H](https://arpa-h.gov/research-and-funding/programs/arpa-h-bdf-toolbox/teaming) "social network" [console](https://github.com/epiverse/arpah):

```javascript
simpleTF({
    data:[/*default iris?*/]
    layers:[/*default [] logistic?*/],
    lossFun: SSD,
    ...
})
```
maybe approaching it as instances of a simpleTF class would help ... or confuse?

```javascript

simpleTFmod = await import("url_simpleTF_mod.mjs")

stf_iris = new simpleTFmod.simpleTF({
    data:[/*default iris?*/]
    layers:[/*default [] logistic?*/],
    lossFun: SSD,
    ...
})
```
