# Function: <code>ifc_in32</code>

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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 ifc_in32(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/memory/fsl_ifc.c (ffff800010b8b3dc)
Location: include/linux/fsl_ifc.h:853
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:check_nand_stat
  - drivers/memory/fsl_ifc.c:check_nand_stat
Direct callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
```
**Symbols:**

```
ffff800010b8b1d8-ffff800010b8b21c: ifc_in32 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
