# Function: <code>eeh_pe_next</code>

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
struct eeh_pe *eeh_pe_next(struct eeh_pe *pe, struct eeh_pe *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/eeh_pe.c (c000000000047d34)
Location: arch/powerpc/kernel/eeh_pe.c:182
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_state_clear
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_mark_isolated
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_state_mark
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_traverse
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_pe_reset_full
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_clear_pe_frozen_state
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_report
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_channel_state
```
**Symbols:**

```
c000000000047180-c0000000000471c4: eeh_pe_next (STB_GLOBAL)
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
