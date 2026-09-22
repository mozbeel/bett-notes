#CABS

CPU 
	=> Chipset
		=> NVMe (Non Volatile Memory Express)
		=> I/O
			=> Keyboard: Input
			=> Mouse: Input
			=> Monitor: Output
			=> Network (NIC, Network Card): I/O
			=> SSD: within an SSD there's SATA to connect
					-> Flash technlogy
					-> AHCI (Advance Host Controller Interface)
					-> SATA 3 cant do more than 6Gbit/s
			=> NVMe (Non Volatile Memory express): connected via M.2
					-> 22mm width, 80mm length -> M.2 interface
					-> Flash technology
					-> PCIe Bus
					-> PCIe 5 can 24 GB/s
					-> M.2 -> small RAM chip (cache) to make it faster
	=> RAM: needs to be fastest connection
	=> PCIe Bus

