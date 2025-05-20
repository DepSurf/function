# Function: <code>eeh_pe_dev_traverse</code>

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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void eeh_pe_dev_traverse(struct eeh_pe *root, eeh_edev_traverse_func fn, void *flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/eeh_pe.c (c0000000000472c0)
Location: arch/powerpc/kernel/eeh_pe.c:234
Inline: True
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_pe_reset_full
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_restore_bars
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_dev_mode_mark
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_reset_and_recover
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_reset_and_recover
```
**Symbols:**

```
c0000000000472c0-c0000000000473f0: eeh_pe_dev_traverse (STB_GLOBAL)
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
