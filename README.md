# wasm-runtime

WebAssembly-powered, sandboxed implementation of Python runtime for safely `exec()`-cuting dynamic Python code.

This is an active version of [wasm_exec](https://github.com/Jflick58/wasm_exec) created by [Justin Flick](https://github.com/Jflick58). See [Jflick58/wasm_exec/LICENSE](https://github.com/Jflick58/wasm_exec/blob/main/LICENSE) and [● wasm_runtime/LICENSE](https://github.com/AWeirdDev/wasm_runtime).

<div align="center">

`$ pip install wasm-runtime`

</div>

```python
from wasm_runtime import WasmRuntime

runtime = WasmRuntime()
result = runtime.exec("print('Hi, Mom!')")

print(result)
# Result(stdout='Hi, Mom!\n', stderr='', ...)
```
