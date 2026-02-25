# onnxruntime-qa

This project runs scheduled CI jobs against the `main` and latest `rel-*` branch found in  https://github.com/microsoft/onnxruntime .
At the time of writing CI is run daily on the `win-64`, `osx-arm64`, `linux-64`, and `linux-aarch64` platforms and against Python 3.11 and 3.14. 
Currently, only ctests and tests defined in `onnxruntime/test/python/onnxruntime_test_python_mlops.py` are executed.

See https://github.com/microsoft/onnxruntime/issues/27392 for further context.
