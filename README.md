# Deploy a new VM from a vCenter template and configure networking and hostname

## __Dependencies:__
- pip
- pyvmomi
- ansible
- openssh-clients
- openssh
Consider running a preperation script to match these dependencies e.g. https://github.com/siw36/prepare-workstation

## __Before you start:__
The template you want to deploy must be available on the destination esxi host.
Deployment of a template from a vCenter library is not yet supported.

The vmware vsphere_guest configuration option is not supported for every guest OS.
To find out wich OS is supported for vmware_guest customization see:
http://partnerweb.vmware.com/programs/guestOS/guest-os-customization-matrix.pdf

## __Wich playbook to use:__
### The guest OS is NOT supported for customization
- deploy_template_no_customization.yml
