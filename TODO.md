- [ ] add C++20 concepts for the VM::add_custom() function
- [ ] add c++20 module support 
- [ ] upload the lib to dnf 
- [ ] upload the lib to apt 
- [ ] make a man file in markdown for the cli tool
- [ ] implement techniques from here https://stackoverflow.com/questions/43026032/detect-running-on-virtual-machine
- [ ] check if bios date in /sys/class/dmi/id/ could be useful under QEMU
- [ ] add a .so, .dll, and .dylib shared object files in the release 
- [ ] /sys/class/dmi/id/product_name check this in qemu
- [ ] fix "dmidecode not found" error
- [ ] rearrange the techniques so that the more likely ones will be executed first
- [ ] implement techniques from here https://www.cyberciti.biz/faq/linux-determine-virtualization-technology-command/
- [ ] implement techniques from virt-what
 
QEMU default: 0x1234
Intel: 0x8086
AMD: 0x1022
VMware: 0x15ad
Red Hat/Qumranet: 0x1af4
In the QEMU source:
include/hw/pci/pci.h
include/hw/pci/pci_ids.h

# Distant plans
- add the library to conan.io when released
- add a python version of the library (or any other lang for that matter)
- add a GUI version of the lib
- add a rust version of the lib
- submit the project to oss-fuzz 
