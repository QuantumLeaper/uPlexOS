# uPlexOS

uPlexOS brings privacy and security together through a fairly simplistic operating system.

## How it works
uPlexOS utilizes secure compartementalization via Xen hypvervisor and airgapped virtual machines. By default, uPlexaOS comes with the following setup:

* HostOS (Host operating system - no internet connectivity, airgapped and secure by default)
* AppVMs (Virtual machines)
* SysNET (Default systen network gateway)
* SysFWL (System network + firewall)
* WhoNET (Whonix networking gateway via Plexanet)
* Disposable AppVMs (VM's for one-time use)
* Persistent AppVMs (VM's for multi-use)
* Default AppVM templates: Fedora, Debian, Whonix
* AppVMs work parallel to other VMs via an interface in which runs apps under other VMs as though the machine is only running one operating system. Thus, your browser in AppVM #1, your messaging app in app in AppVM #2 and your airgapped vault running KeyPassXC would all be in seperate virtual machines but would be managable via one desktop, all seeming like typical apps on one deskop environment.


## More Notes
The system architecture will also include full disk encryption via LUKS/dm-crypt. Privacy based applications will come default with all AppVM tempates. Users are able to create their own AppVM templates, as-well.

... More to come.
