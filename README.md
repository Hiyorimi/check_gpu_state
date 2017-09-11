check_gpu_state

A small Nagios plugin that checks the GPU state with nvidia-smi.
It's written in Bash and uses *nix "nvidia-smi" and some sed & awk.
The plugin is based on check_temp [plugin](https://github.com/jackbenny/check_temp) by jackbenny.
The plugin complies with the guidelines, for example uses -w -c -v arguments 
etc. It also does some basic sanity checks and has a exit 3 catch-all.

