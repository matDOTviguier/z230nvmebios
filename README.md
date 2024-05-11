# z230nvmebios
This project helps to make the [HP Z230 SFF Workstation](https://support.hp.com/us-en/document/c03943712#N65571) ready to boot from an NVMe SSD via a PCIe M.2 NVMe SSD to PCI-E 3.0 Adapter (M Key).

## Why the hell ?
For several years, I held the position of technical manager and operational driver at a computer refurbishment company. I noticed that many businesses dispose of their computers, often still capable of performing well, which can be refurbished by a skilled engineer to be resold at a higher level of performance than the previous owners anticipated.
This experience enabled me to develop significant expertise in hardware and software optimization. During purchasing, I observed that older generations of HP Z-series workstations offered an attractive performance-to-price ratio.
Consequently, I focused my efforts on optimizing these machines, which are widely available on the market. They often come equipped with either low-end or high-end processors intended for office use, but they are also compatible with Intel Xeon processors, which typically remain powerful enough for applications such as small labs or modest servers.
However, to fully utilize all features, including booting from NVME devices, BIOS modifications are required. I relied on the work of various communities to synthesize a procedure for BIOS upgrading.
Personally, I implemented this procedure on four identical computers that I use for virtualization, and all these systems work perfectly by booting from an NVME device.

## But How ?
There's still some space in the BIOS software component penthouse, just enough to slip in the NVME driver and add that missing functionality. HP could've easily done the job, but they chose to save these features for the Z 240 lineup.
One fine morning, I decided I didn't agree with that.

## OK I'm ready
Follow the [white rabbit](https://github.com/matDOTviguier/z230nvmebios/wiki) ... aka wiki.
