# Function: <code>cpufreq_driver_test_flags</code>

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
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81998560)
Location: drivers/cpufreq/cpufreq.c:1921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81998560-ffffffff81998579: cpufreq_driver_test_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197ced0)
Location: drivers/cpufreq/cpufreq.c:1927
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff8197ced0-ffffffff8197cee9: cpufreq_driver_test_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25f10)
Location: drivers/cpufreq/cpufreq.c:1933
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81a25f10-ffffffff81a25f29: cpufreq_driver_test_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8f8b0)
Location: drivers/cpufreq/cpufreq.c:1965
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81b8f8b0-ffffffff81b8f8cf: cpufreq_driver_test_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2f920)
Location: drivers/cpufreq/cpufreq.c:1962
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81d2f920-ffffffff81d2f93f: cpufreq_driver_test_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d98c00)
Location: drivers/cpufreq/cpufreq.c:1969
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81d98c00-ffffffff81d98c1f: cpufreq_driver_test_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpufreq_driver_test_flags(u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e50880)
Location: drivers/cpufreq/cpufreq.c:2010
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81e50880-ffffffff81e5089f: cpufreq_driver_test_flags (STB_GLOBAL)
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
