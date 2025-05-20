# Function: <code>_clktrctrl_write</code>

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
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void _clktrctrl_write(u8 c, u8 part, u16 inst, u16 cdoffs);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/cminst44xx.c (c0341cec)
Location: arch/arm/mach-omap2/cminst44xx.c:180
Inline: False
Direct callers:
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_clk_disable
```
```
In arch/arm/mach-omap2/cm33xx.c (c0343bec)
Location: arch/arm/mach-omap2/cm33xx.c:129
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_clk_disable
```
**Symbols:**

```
c0341cec-c0341d48: _clktrctrl_write (STB_LOCAL)
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
