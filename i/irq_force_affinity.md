# Function: <code>irq_force_affinity</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_force_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811402f0)
Location: kernel/irq/manage.c:483
Inline: False
```
**Symbols:**

```
ffffffff811402f0-ffffffff81140355: irq_force_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_force_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163c40)
Location: kernel/irq/manage.c:498
Inline: False
```
**Symbols:**

```
ffffffff81163c40-ffffffff81163cac: irq_force_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_force_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81197940)
Location: kernel/irq/manage.c:490
Inline: False
```
**Symbols:**

```
ffffffff81197940-ffffffff811979ac: irq_force_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_force_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a9600)
Location: kernel/irq/manage.c:493
Inline: False
```
**Symbols:**

```
ffffffff811a9600-ffffffff811a966c: irq_force_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_force_affinity(unsigned int irq, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b9160)
Location: kernel/irq/manage.c:495
Inline: False
```
**Symbols:**

```
ffffffff811b9160-ffffffff811b91cc: irq_force_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/perf/arm_pmu.c (ffff800010b95458)
Location: include/linux/interrupt.h:331
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-tegra.c (c0c49c10)
Location: include/linux/interrupt.h:331
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
```
```
In drivers/clocksource/exynos_mct.c (c0c4a2c8)
Location: include/linux/interrupt.h:331
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:exynos4_mct_starting_cpu
```
```
In drivers/perf/arm_pmu.c (c0c7ea20)
Location: include/linux/interrupt.h:331
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
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
<b>Regular</b>
<ul>
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
