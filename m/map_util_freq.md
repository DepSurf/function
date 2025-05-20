# Function: <code>map_util_freq</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee72e)
Location: include/linux/sched/cpufreq.h:24
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f5539)
Location: include/linux/sched/cpufreq.h:24
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811011f1)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
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
In kernel/sched/fair.c (ffffffff810e8f36)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110ac84)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff810e6cde)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81107b94)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff810e9a79)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109cd7)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff8110131c)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811284d4)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff8111ca33)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/build_utility.c (ffffffff8113e304)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff811463c4)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/build_utility.c (ffffffff81168804)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff811541d8)
Location: include/linux/sched/cpufreq.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/build_utility.c (ffffffff8117987e)
Location: include/linux/sched/cpufreq.h:26
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
In kernel/sched/fair.c (0)
Location: include/linux/sched/cpufreq.h:26
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81187371)
Location: include/linux/sched/cpufreq.h:26
Inline: True
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
In kernel/sched/cpufreq_schedutil.c (ffff800010165b88)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b2130)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bcf50)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa501)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea6e1)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f76c1)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811027a1)
Location: include/linux/sched/cpufreq.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
</ul>

## Differences
