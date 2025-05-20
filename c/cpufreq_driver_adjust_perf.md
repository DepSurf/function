# Function: <code>cpufreq_driver_adjust_perf</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998580)
Location: drivers/cpufreq/cpufreq.c:2121
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81998580-ffffffff8199859b: cpufreq_driver_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197cef0)
Location: drivers/cpufreq/cpufreq.c:2127
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff8197cef0-ffffffff8197cf0b: cpufreq_driver_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25f30)
Location: drivers/cpufreq/cpufreq.c:2133
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81a25f30-ffffffff81a25f4b: cpufreq_driver_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8f8d0)
Location: drivers/cpufreq/cpufreq.c:2165
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81b8f8d0-ffffffff81b8f8f9: cpufreq_driver_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2f950)
Location: drivers/cpufreq/cpufreq.c:2162
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81d2f950-ffffffff81d2f979: cpufreq_driver_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d98c30)
Location: drivers/cpufreq/cpufreq.c:2169
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81d98c30-ffffffff81d98c59: cpufreq_driver_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpufreq_driver_adjust_perf(unsigned int cpu, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e508b0)
Location: drivers/cpufreq/cpufreq.c:2210
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81e508b0-ffffffff81e508d9: cpufreq_driver_adjust_perf (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
