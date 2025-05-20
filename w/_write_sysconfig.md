# Function: <code>_write_sysconfig</code>

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
void _write_sysconfig(u32 v, struct omap_hwmod *oh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/omap_hwmod.c (c0338068)
Location: arch/arm/mach-omap2/omap_hwmod.c:295
Inline: True
Direct callers:
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_disable_wakeup
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_enable_wakeup
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_softreset
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_softreset
  - arch/arm/mach-omap2/omap_hwmod.c:_shutdown
  - arch/arm/mach-omap2/omap_hwmod.c:_enable_sysc
  - arch/arm/mach-omap2/omap_hwmod.c:_enable_sysc
  - arch/arm/mach-omap2/omap_hwmod.c:_enable_sysc
```
**Symbols:**

```
c0338068-c0338124: _write_sysconfig (STB_LOCAL)
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
