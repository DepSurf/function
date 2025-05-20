# Function: <code>cpuidle_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff816bbd60)
Location: drivers/cpuidle/cpuidle.c:573
Inline: False
```
**Symbols:**

```
ffffffff816bbd60-ffffffff816bbe18: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8171d630)
Location: drivers/cpuidle/cpuidle.c:575
Inline: False
```
**Symbols:**

```
ffffffff8171d630-ffffffff8171d6e8: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81750220)
Location: drivers/cpuidle/cpuidle.c:592
Inline: False
```
**Symbols:**

```
ffffffff81750220-ffffffff817502da: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8176ece0)
Location: drivers/cpuidle/cpuidle.c:595
Inline: False
```
**Symbols:**

```
ffffffff8176ece0-ffffffff8176ed99: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff817e45d0)
Location: drivers/cpuidle/cpuidle.c:601
Inline: False
```
**Symbols:**

```
ffffffff817e45d0-ffffffff817e4670: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:616
Inline: True
```
**Symbols:**

```
ffffffff8182d8d7-ffffffff8182d907: cpuidle_register.cold.13 (STB_LOCAL)
ffffffff8182d7f0-ffffffff8182d86e: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:645
Inline: True
```
**Symbols:**

```
ffffffff81859a57-ffffffff81859a87: cpuidle_register.cold.14 (STB_LOCAL)
ffffffff81859970-ffffffff818599ee: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:660
Inline: False
```
**Symbols:**

```
ffffffff8189d39a-ffffffff8189d3ca: cpuidle_register.cold (STB_LOCAL)
ffffffff8189d2a0-ffffffff8189d31c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
```
**Symbols:**

```
ffffffff818cf747-ffffffff818cf777: cpuidle_register.cold (STB_LOCAL)
ffffffff818cf660-ffffffff818cf6dc: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:702
Inline: False
```
**Symbols:**

```
ffffffff819a1d47-ffffffff819a1d77: cpuidle_register.cold (STB_LOCAL)
ffffffff819a1320-ffffffff819a139c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:727
Inline: False
```
**Symbols:**

```
ffffffff81c2a018-ffffffff81c2a048: cpuidle_register.cold (STB_LOCAL)
ffffffff819a4370-ffffffff819a43ec: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:727
Inline: False
```
**Symbols:**

```
ffffffff81c1c3ee-ffffffff81c1c41e: cpuidle_register.cold (STB_LOCAL)
ffffffff81988fb0-ffffffff8198902c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:727
Inline: False
```
**Symbols:**

```
ffffffff81d2cc6f-ffffffff81d2cca3: cpuidle_register.cold (STB_LOCAL)
ffffffff81a331e0-ffffffff81a33286: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:727
Inline: False
```
**Symbols:**

```
ffffffff81ef901a-ffffffff81ef9049: cpuidle_register.cold (STB_LOCAL)
ffffffff81b9fa40-ffffffff81b9faf0: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81d414a0)
Location: drivers/cpuidle/cpuidle.c:732
Inline: True
```
**Symbols:**

```
ffffffff81d414a0-ffffffff81d4158d: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81dabe70)
Location: drivers/cpuidle/cpuidle.c:764
Inline: True
```
**Symbols:**

```
ffffffff81dabe70-ffffffff81dabf5d: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81e63f10)
Location: drivers/cpuidle/cpuidle.c:764
Inline: True
```
**Symbols:**

```
ffffffff81e63f10-ffffffff81e63ffd: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffff800010b27578)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
**Symbols:**

```
ffff800010b27578-ffff800010b27648: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c0c023bc)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
Direct callers:
  - arch/arm/mach-imx/cpuidle-imx5.c:imx5_cpuidle_init
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_cpuidle_init
  - arch/arm/mach-imx/cpuidle-imx6sl.c:imx6sl_cpuidle_init
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_cpuidle_init
  - arch/arm/mach-imx/cpuidle-imx7ulp.c:imx7ulp_cpuidle_init
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_idle_init
  - arch/arm/mach-omap2/cpuidle44xx.c:omap4_idle_init
  - arch/arm/mach-tegra/cpuidle-tegra20.c:tegra20_cpuidle_init
  - arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_cpuidle_init
  - arch/arm/mach-tegra/cpuidle-tegra114.c:tegra114_cpuidle_init
  - drivers/cpuidle/cpuidle-mvebu-v7.c:mvebu_v7_cpuidle_probe
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_init
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_init
  - drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_probe
  - drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_probe
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
```
**Symbols:**

```
c0c023bc-c0c0248c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c000000000c1e910)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init
  - drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init
```
**Symbols:**

```
c000000000c1e910-c000000000c1ea1c: cpuidle_register (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
```
**Symbols:**

```
ffffffff818731e7-ffffffff81873217: cpuidle_register.cold (STB_LOCAL)
ffffffff81873100-ffffffff8187317c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
```
**Symbols:**

```
ffffffff8183cfd7-ffffffff8183d007: cpuidle_register.cold (STB_LOCAL)
ffffffff8183cef0-ffffffff8183cf6c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
```
**Symbols:**

```
ffffffff818c4bf7-ffffffff818c4c27: cpuidle_register.cold (STB_LOCAL)
ffffffff818c4b10-ffffffff818c4b8c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cpuidle_register(struct cpuidle_driver *drv, const const struct cpumask * coupled_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:691
Inline: False
```
**Symbols:**

```
ffffffff818e0fb7-ffffffff818e0fe7: cpuidle_register.cold (STB_LOCAL)
ffffffff818e0ed0-ffffffff818e0f4c: cpuidle_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
