# Function: <code>pdn_to_eeh_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/rtas_pci.c (c00000000003fd70)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas_pci.c:rtas_pci_read_config
```
```
In arch/powerpc/kernel/eeh.c (c000000000044dbc)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_restore_vf_config
```
```
In arch/powerpc/kernel/eeh_pe.c (c000000000047688)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_add_to_parent_pe
```
```
In arch/powerpc/kernel/eeh_cache.c (c00000000004836c)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev
```
```
In arch/powerpc/kernel/pci_dn.c (c00000000006a2a8)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_dn.c:pci_remove_device_node_info
  - arch/powerpc/kernel/pci_dn.c:remove_dev_pci_data
```
```
In arch/powerpc/kernel/pci_of_scan.c (c00000000006f8e4)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000dcd70)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_restore_config
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_write_config
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_read_config
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
```
```
In arch/powerpc/platforms/pseries/eeh_pseries.c (c0000000000f6d98)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_notify_resume
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_restore_config
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_probe
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_probe
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_probe
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_pcibios_bus_add_device
```
```
In arch/powerpc/platforms/pseries/msi.c (c0000000000f7844)
Location: arch/powerpc/include/asm/pci-bridge.h:243
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
