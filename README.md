
Virtualbox Command
=================================================


### Savestate | poweroff VirtualBox VM
```
VBoxManage controlvm        <uuid|vmname>
                            pause|resume|reset|poweroff|savestate|
                            acpipowerbutton|acpisleepbutton|
```

for example 
```sh
VBoxManage controlvm 1efaee1e-573a-471b-9843-952ce48414ef savestate
```


### Start VirtualBox VM
```sh
virtualbox startvm  1efaee1e-573a-471b-9843-952ce48414ef savestate
```
