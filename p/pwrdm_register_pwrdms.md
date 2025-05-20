# Function: <code>pwrdm_register_pwrdms</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
int pwrdm_register_pwrdms(struct powerdomain **ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/powerdomain.c (c0344d34)
Location: arch/arm/mach-omap2/powerdomain.c:321
Inline: False
Direct callers:
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:omap3xxx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains44xx_data.c:omap44xx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains33xx_data.c:am33xx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init
  - arch/arm/mach-omap2/powerdomains7xx_data.c:dra7xx_powerdomains_init
```
**Symbols:**

```
c0344d34-c0344f70: pwrdm_register_pwrdms (STB_GLOBAL)
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
