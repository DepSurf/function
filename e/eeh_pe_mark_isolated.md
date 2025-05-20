# Function: <code>eeh_pe_mark_isolated</code>

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
void eeh_pe_mark_isolated(struct eeh_pe *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/eeh_pe.c (c000000000046340)
Location: arch/powerpc/kernel/eeh_pe.c:601
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_get_state
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_get_state
```
**Symbols:**

```
c000000000046340-c000000000046440: eeh_pe_mark_isolated (STB_GLOBAL)
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
