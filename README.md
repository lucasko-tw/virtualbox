
Virtualbox Command
=================================================


### VBoxManage list vms
```sh
VBoxManage list vms
```

```
"xxxxxVM" {a11123cl-5f7a-859b-1330-g47f06bfgh78}
"yyyyyVM" {b1921c1e-bsd9-df9s-bfba-5afv1136ff91}
"zzzzzVM" {l98axvb7-cf9c-a78e-hb13-027aaa93d9e9}
```


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
VBoxManage startvm  1efaee1e-573a-471b-9843-952ce48414ef
```
