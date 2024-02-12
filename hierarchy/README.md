## Hardware Specs : c220g1  90 nodes (Haswell, 16 core, 3 disks)

- CPU     Two Intel E5-2630 v3 8-core CPUs at 2.40 GHz (Haswell w/ EM64T)
- RAM     128GB ECC Memory (8x 16 GB DDR4 1866 MHz dual rank RDIMMs)
- Disk    Two 1.2 TB 10K RPM 6G SAS SFF HDDs
- Disk    One Intel DC S3500 480 GB 6G SATA SSDs
- NIC     Dual-port Intel X520-DA2 10Gb NIC (PCIe v3.0, 8 lanes) (both ports available for experiment use)
- NIC     Onboard Intel i350 1Gb



<br>

## Comments

- Latency to DRAM in another server in the rack is lower than latency to local disk
  <br>
- Local DRAM has the lowest latency
  <br>
- Since the main disk is a HDD, we notice that Write operations are much slower than Read.
  <br>
- The Network Bandwidth is greater than that of the Local Disk and the Racks, therefore the bandwidth is bottlenecked 

<br>
<br>
