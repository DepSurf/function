# Function: <code>cpufreq_driver_has_adjust_perf</code>

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
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819985a0)
Location: drivers/cpufreq/cpufreq.c:2135
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
**Symbols:**

```
ffffffff819985a0-ffffffff819985ba: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197cf10)
Location: drivers/cpufreq/cpufreq.c:2141
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
**Symbols:**

```
ffffffff8197cf10-ffffffff8197cf2a: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25f50)
Location: drivers/cpufreq/cpufreq.c:2147
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
**Symbols:**

```
ffffffff81a25f50-ffffffff81a25f6a: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8f900)
Location: drivers/cpufreq/cpufreq.c:2179
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
```
**Symbols:**

```
ffffffff81b8f900-ffffffff81b8f91e: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2f990)
Location: drivers/cpufreq/cpufreq.c:2176
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
```
**Symbols:**

```
ffffffff81d2f990-ffffffff81d2f9ae: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d98c70)
Location: drivers/cpufreq/cpufreq.c:2183
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
```
**Symbols:**

```
ffffffff81d98c70-ffffffff81d98c8e: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpufreq_driver_has_adjust_perf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e508f0)
Location: drivers/cpufreq/cpufreq.c:2224
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
```
**Symbols:**

```
ffffffff81e508f0-ffffffff81e5090e: cpufreq_driver_has_adjust_perf (STB_GLOBAL)
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
