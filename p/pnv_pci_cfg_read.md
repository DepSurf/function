# Function: <code>pnv_pci_cfg_read</code>

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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pnv_pci_cfg_read(struct pci_dn *pdn, int where, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0a40)
Location: arch/powerpc/platforms/powernv/pci.c:655
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_read_config
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_read_config
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_find_cap
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_find_cap
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_find_cap
```
**Symbols:**

```
c0000000000d0a40-c0000000000d0bcc: pnv_pci_cfg_read (STB_GLOBAL)
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
