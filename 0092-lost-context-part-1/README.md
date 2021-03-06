## STARTING OFF:

Make sure you have npm installed.
Run:
```
npm install http-server -g
```

Run:
```
http-server
```

View at: http://localhost:8080/

## CONCEPTS:

#### Lost Context
* When the GPU is using too many resources (perhaps another tab is using the GPU as well), and the browser frees up resources to regain control.
* gl.isContextLost()
* gl.getExtension('WEBGL_lose_context').loseContext()
* gl.getExtension('WEBGL_lose_context').restoreContext()

## RESOURCES:

* https://github.com/davidwparker/programmingtil-webgl/tree/master/0092-lost-context-part-1
* https://developer.mozilla.org/en-US/docs/Web/API/WEBGL_lose_context/loseContext
* https://developer.mozilla.org/en-US/docs/Web/API/WEBGL_lose_context/restoreContext
