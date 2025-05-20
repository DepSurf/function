# Function: <code>cpu_cluster_pm_enter</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpu_cluster_pm_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (ffff80001025b540)
Location: kernel/cpu_pm.c:132
Inline: False
Direct callers:
  - kernel/cpu_pm.c:cpu_pm_suspend
```
**Symbols:**

```
ffff80001025b540-ffff80001025b5bc: cpu_cluster_pm_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_cluster_pm_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (c048e698)
Location: kernel/cpu_pm.c:132
Inline: False
Direct callers:
  - arch/arm/mach-highbank/pm.c:highbank_pm_enter
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-tegra/pm.c:tegra_idle_lp2_last
  - kernel/cpu_pm.c:cpu_pm_suspend
```
**Symbols:**

```
c048e698-c048e71c: cpu_cluster_pm_enter (STB_GLOBAL)
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
