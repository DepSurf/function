# Function: <code>eeh_pe_passed</code>

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
In arch/powerpc/kernel/eeh.c (c000000000045e8c)
Location: arch/powerpc/include/asm/eeh.h:112
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_pe_reset
  - arch/powerpc/kernel/eeh.c:eeh_dev_release
  - arch/powerpc/kernel/eeh.c:eeh_pe_reset_full
```
```
In arch/powerpc/kernel/eeh_pe.c (c000000000047d18)
Location: arch/powerpc/include/asm/eeh.h:112
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_state_clear
```
```
In arch/powerpc/kernel/eeh_driver.c (c00000000004ad20)
Location: arch/powerpc/include/asm/eeh.h:112
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_clear_pe_frozen_state
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_report
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000ddd38)
Location: arch/powerpc/include/asm/eeh.h:112
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
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
