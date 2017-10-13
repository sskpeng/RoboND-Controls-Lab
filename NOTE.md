# Note for this project

### 1. change the ros_settings.txt file of the simulator to following:

```sf
{
	"vm-ip" : "172.16.16.129",
	"vm-port" : 11311,
	"vm-override" : true,
	"host-ip": "192.168.0.21",
	"host-override" : true
}
```

`vm-ip` and `vm-port` are from virtual machine IP. Get it by typing `echo $(hostname -I)` on the VM terminal.
`vm_override` set to true when using the simulator out of VM
`host-ip` should set to the IP of the PC or MAC
`host-override` set to true

hover controller Kp = 10,Ki = 5, Kd = 5
