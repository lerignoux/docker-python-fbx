# docker-python-fbx
A container to run python scripts on the FBX SDK

# tldr
docker build -t docker-python-fbx .
create your scripts with a `main.py`
```
docker run -v <your script folder>:/app docker-python-fbx
```

# Licensing
The FBX SDK is under Autodesk Licence (see [License.txt](License.txt))
