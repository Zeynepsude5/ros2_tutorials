## Ardupilot Installation

Git configuration:
```
git config --global http.postBuffer 524288000
git config --global http.lowSpeedLimit 0
git config --global http.lowSpeedTime 999999
```

Clone ardupilot:
```
git clone --depth 1 https://github.com/ArduPilot/ardupilot.git
```

Install prerequisites:
```
cd ardupilot
Tools/environment_install/install-prereqs-ubuntu.sh -y
```
