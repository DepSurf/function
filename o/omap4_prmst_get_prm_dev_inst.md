# Function: <code>omap4_prmst_get_prm_dev_inst</code>

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
s32 omap4_prmst_get_prm_dev_inst();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/prminst44xx.c (c0343144)
Location: arch/arm/mach-omap2/prminst44xx.c:47
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset
Direct callers:
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_reset_sources
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap4_prm_vcvp_rmw
  - arch/arm/mach-omap2/prm44xx.c:omap4_prm_vcvp_write
  - arch/arm/mach-omap2/prm44xx.c:omap4_prm_vcvp_read
```
**Symbols:**

```
c0342e40-c0342e64: omap4_prmst_get_prm_dev_inst (STB_GLOBAL)
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
