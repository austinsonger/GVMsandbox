# GVM Sandbox
Working on a new GVM Docker Container


## TO-DO
- Add `open_scanner_protocol_daemon` to Dockerfile
- Add `gvm_tools_version` to Dockerfile
- Add `python_gvm_version` to Dockerfile
- Get add ssh for scanner so [baseenv.sh](/modules/base/baseenv.sh)
    - Remove username and password option for scanner 

## Thinking About
- Thinking about separating gvm components from Dockerfile and make them into separate scripts.

## NOTE:
`ospd_openvas` is taken care of on [openVAS/install-pkgs.sh](/modules/openvas/install-pkgs.sh)







