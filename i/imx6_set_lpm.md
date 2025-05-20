# Function: <code>imx6_set_lpm</code>

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
int imx6_set_lpm(enum mxc_cpu_pwr_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-imx/pm-imx6.c (c0334634)
Location: arch/arm/mach-imx/pm-imx6.c:291
Inline: False
Direct callers:
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6sl.c:imx6sl_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6sl.c:imx6sl_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
```
**Symbols:**

```
c0334634-c0334788: imx6_set_lpm (STB_GLOBAL)
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
