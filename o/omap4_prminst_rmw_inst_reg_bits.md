# Function: <code>omap4_prminst_rmw_inst_reg_bits</code>

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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 omap4_prminst_rmw_inst_reg_bits(u32 mask, u32 bits, u8 part, s16 inst, u16 idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/prminst44xx.c (c03430a0)
Location: arch/arm/mach-omap2/prminst44xx.c:76
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset
Direct callers:
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_logic_retst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_clear_all_prev_pwrst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_lowpwrstchange
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/prm44xx.c:omap4_prm_vcvp_rmw
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_assert_hardreset
```
**Symbols:**

```
c0342f28-c0342f88: omap4_prminst_rmw_inst_reg_bits (STB_GLOBAL)
```
</details>
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
