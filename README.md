# Windows in Docker

We've all been there, you're busy working away and then *bang* you run into what you suspect might be a platform-specific bug. How are you supposed to quickly check that? 

Well, the conventional wisdom would be to go to a Windows machine or spin up a Windows VM. Well, you could do that... But it's a drag and you have to contend with setting up QEMU/KVM and persistent storage, and then you have to remember to tear it all down again.

This solution may not be the most elegant, but it does what it says on the tin, you get a Windows machine that you can RDP into contained within a Docker container. You can `docker run` it, rdp in, get what you need to done then get gone!

The contents of this repo were made referencing [this article on Medium](https://medium.com/axon-technologies/installing-a-windows-virtual-machine-in-a-linux-docker-container-c78e4c3f9ba1) but several changes have been made to make it work better.
