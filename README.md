# ansible-deploy-vcsa-vm
Deploy a new VM from a vCenter template and configure networking and hostname

Deps
- pip
- pyvmomi
- ansible
- openssh-clients
- openssh

consider running a preperation script e.g. https://github.com/siw36/prepare-workstation

To find out wich os is supported for vmware_guest customization see:
http://partnerweb.vmware.com/programs/guestOS/guest-os-customization-matrix.pdf
