# Function: <code>eeh_dev_to_pci_dev</code>

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
In arch/powerpc/kernel/eeh.c (c000000000045e40)
Location: arch/powerpc/include/asm/eeh.h:170
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_pe_reset
  - arch/powerpc/kernel/eeh.c:eeh_set_dev_freset
  - arch/powerpc/kernel/eeh.c:eeh_restore_dev_state
  - arch/powerpc/kernel/eeh.c:eeh_disable_and_save_dev_state
```
```
In arch/powerpc/kernel/eeh_pe.c (c000000000047d90)
Location: arch/powerpc/include/asm/eeh.h:170
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_state_clear
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_mark_isolated
```
```
In arch/powerpc/kernel/eeh_driver.c (c0000000000494c0)
Location: arch/powerpc/include/asm/eeh.h:170
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_add_virt_device
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
