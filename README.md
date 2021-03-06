VmConfigTrigger VMware PowerCLI Script
=============

# About

## Project Owner:

Markus Kraus [@vMarkus_K](https://twitter.com/vMarkus_K)

MY CLOUD-(R)EVOLUTION [mycloudrevolution.com](http://mycloudrevolution.com/)

## Project WebSite:

[mycloudrevolution.com](http://mycloudrevolution.com/)

## Project Description:

The 'VmConfigTrigger' PowerShell Script can be used to trigger a VMware vSphere VM reconfiguration when the VM is powered off.

* The Script is created as a permanent loop
* Input is a JSON config file

__JSON Example:__
```json
[
    {
        "Name": "test",
        "RAM": "2",
        "CPU": "1",
        "Start": "no"


    },
    {
        "Name": "test2",
        "RAM": "2",
        "CPU": "1",
        "Start": "yes"
    }
]
```


![VmConfigTrigger-Shell](/media/VmConfigTrigger-Shell_v2.png)



