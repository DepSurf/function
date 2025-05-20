# Function: <code>pnv_pci_dump_phb_diag_data</code>

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
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pnv_pci_dump_phb_diag_data(struct pci_controller *hose, unsigned char *log_buff);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/platforms/powernv/pci.c (c0000000000d2184)
Location: arch/powerpc/platforms/powernv/pci.c:533
Inline: True
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_diag_data_set
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_get_state
```
**Symbols:**

```
c0000000000d2184-c0000000000d2208: pnv_pci_dump_phb_diag_data.part.0 (STB_LOCAL)
c0000000000d0a10-c0000000000d0a34: pnv_pci_dump_phb_diag_data (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
