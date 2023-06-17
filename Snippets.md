## Instantiate a scene

```
var myScene = load("pathto.tscn file")
var instance: Spatial = myScene.instance()
add_child(instance)
```

To eliminate the pause on load() you can preload() the scene earlier in the flow.
