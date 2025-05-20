# Function: <code>cpu_is_imx6sl</code>

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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-imx/anatop.c (c03327f0)
Location: arch/arm/mach-imx/mxc.h:42
Inline: True
Inline callers:
  - arch/arm/mach-imx/anatop.c:imx_anatop_post_resume
  - arch/arm/mach-imx/anatop.c:imx_anatop_pre_suspend
```
```
In arch/arm/mach-imx/mach-imx6sl.c (c150fa54)
Location: arch/arm/mach-imx/mxc.h:42
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_irq
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_machine
  - arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_late
```
```
In arch/arm/mach-imx/pm-imx6.c (c1510684)
Location: arch/arm/mach-imx/mxc.h:42
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6sl_pm_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6_set_lpm
  - arch/arm/mach-imx/pm-imx6.c:imx6_set_lpm
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
