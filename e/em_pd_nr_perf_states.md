# Function: <code>em_pd_nr_perf_states</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ffb55)
Location: include/linux/energy_model.h:184
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81962b9f)
Location: include/linux/energy_model.h:184
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In kernel/sched/topology.c (ffffffff81101f95)
Location: include/linux/energy_model.h:184
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81946190)
Location: include/linux/energy_model.h:184
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In kernel/sched/topology.c (ffffffff8111e909)
Location: include/linux/energy_model.h:209
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff819eaba0)
Location: include/linux/energy_model.h:209
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In kernel/sched/build_utility.c (ffffffff81142f89)
Location: include/linux/energy_model.h:308
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81b509f8)
Location: include/linux/energy_model.h:308
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In kernel/sched/build_utility.c (ffffffff81170551)
Location: include/linux/energy_model.h:308
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce898f)
Location: include/linux/energy_model.h:308
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In kernel/sched/build_utility.c (ffffffff81180161)
Location: include/linux/energy_model.h:308
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81d5114f)
Location: include/linux/energy_model.h:308
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In kernel/sched/build_utility.c (ffffffff8118f0ad)
Location: include/linux/energy_model.h:307
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_perf_domains
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07ece)
Location: include/linux/energy_model.h:307
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
