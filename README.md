# Chaos Muxy

Experiment with Muxy proxy for causing network failures in target apps.

Muxy causes failures on TCP and HTTP network layers.

## WSL 2

HTTP Muxy module doesn't work on WSL 2 due to missing netem module. Use VM, bare Linux machine or recompile WSL 2 kernel to use it.
