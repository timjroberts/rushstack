[Home](./index) &gt; [@microsoft/node-core-library](./node-core-library.md) &gt; [IProtectableMapParameters](./node-core-library.iprotectablemapparameters.md) &gt; [onSet](./node-core-library.iprotectablemapparameters.onset.md)

# IProtectableMapParameters.onSet property

An optional hook that will be invoked before Map.set() is performed.

**Signature:**
```javascript
onSet: (source: ProtectableMap<K, V>, key: K, value: V) => V
```

## Remarks

If this hook is provided, the function MUST return the \`value\` parameter. This provides the opportunity to modify the value before it is added to the map.