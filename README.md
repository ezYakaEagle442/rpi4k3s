# rpi-travel-case

```
Some important notes about Rancher/K3s: 

1. The Rancher management server does not run on armv7. It will run on a 64 bit architecture. 
2. You can import K3s clusters into an external Rancher, but the Rancher server components do not run on armv7, as that is 32 bit. The latest Raspberry Pi's actually have 64 bit hardware, but the Raspbian Buster image is 32 bit. So, as long as you put a 64 bit OS on the Pi, you can import that K3s cluster into an external Rancher management server. 
```

This repository contains all info needed to recreate my Raspberry Pi Travel Case. This travel case was created to demo K3s and consists of 6 Raspberry Pi 4B's, a 7" Touchscreen, 500GB SSD. The setup consists of a Server and 5 clients. With PXE boot the clients netboot of the server. 

For more info on K3s, checkout: https://k3s.io  

**/!\ Internet access is required to update OS packages and to get K3S from GitHub**

## Shopping list
Go to: [Shopping list](./docs/shopping-list.md)  

## Setup Client
Go to: [Setup Client](./docs/setup-client.md)  

## Setup Server 
Go to: [Setup Server](./docs/setup-server.md)  

## Setup Network
Go to: [Setup network](./docs/setup-network.md)

## Use SSD instead of SD
Go to: [SD to SSD](./docs/sd-to-ssd.md)

## Setup K3s
Go to: [Setup K3s](./docs/setup-k3s.md)

## Hardware
Go to: [Hardware](./docs/hardware.md)

## Setup Cam
Go to: [Cam](./docs/cam.md)
See [https://www.raspberrypi.org/documentation/configuration/camera.md](https://www.raspberrypi.org/documentation/configuration/camera.md)

![Alt text](./docs/images/2.jpg?raw=true "Raspberry Pi Travel Case Cluster")
![Alt text](./docs/images/1.jpg?raw=true "Raspberry Pi Travel Case Cluster")


## Credits :
- [Setup K3S on a Raspberry-Pi in 15 minutes](https://medium.com/@alexellisuk/walk-through-install-kubernetes-to-your-raspberry-pi-in-15-minutes-84a8492dc95a)
- [https://github.com/Sheldonwl/rpi-travel-case](https://github.com/Sheldonwl/rpi-travel-case)
- [https://doingdata.cloud/2020/05/24/how-to-k3s-on-raspberry-pi](https://doingdata.cloud/2020/05/24/how-to-k3s-on-raspberry-pi)
- [https://opensource.com/article/20/3/kubernetes-raspberry-pi-k3s](https://opensource.com/article/20/3/kubernetes-raspberry-pi-k3s)
- [https://blog.alexellis.io/visiting-pimoroni](https://blog.alexellis.io/visiting-pimoroni)
- [https://blog.alexellis.io/raspberry-pi-homelab-with-k3sup](https://blog.alexellis.io/raspberry-pi-homelab-with-k3sup)
- [https://www.jeffgeerling.com/blog/2019/raspberry-pi-4-needs-fan-heres-why-and-how-you-can-add-one](https://www.jeffgeerling.com/blog/2019/raspberry-pi-4-needs-fan-heres-why-and-how-you-can-add-one)
- [https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-blinkt](https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-blinkt)
- [https://raspberrytips.com/install-heat-sinks-raspberry-pi](https://raspberrytips.com/install-heat-sinks-raspberry-pi)
- https://www.makeuseof.com/tag/raspberry-pi-wont-boot-fix 
 
