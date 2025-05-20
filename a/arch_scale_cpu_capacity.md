# Function: <code>arch_scale_cpu_capacity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc6e0)
Location: kernel/sched/sched.h:1409
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfea0)
Location: kernel/sched/sched.h:1446
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5e6a)
Location: kernel/sched/sched.h:1485
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/sched.h:1485
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfa33)
Location: kernel/sched/sched.h:1666
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/sched.h:1666
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c71f1)
Location: kernel/sched/sched.h:1705
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/sched.h:1705
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cf0f8)
Location: kernel/sched/sched.h:1742
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1742
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/sched.h:1742
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:206
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:206
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:206
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/sched/topology.h:206
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:206
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:212
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:212
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:212
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:212
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:221
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:221
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:221
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:221
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:221
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:221
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
```
In drivers/cpuidle/governors/teo.c (0)
Location: include/linux/sched/topology.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:261
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:261
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/sched/topology.h:261
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched/topology.h:261
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/sched/topology.h:261
Inline: True
```
```
In drivers/cpuidle/governors/teo.c (0)
Location: include/linux/sched/topology.h:261
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/sched/topology.h:222
Inline: True
```
</details>
</li>
</ul>

## Differences
