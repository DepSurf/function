# Function: <code>sugov_update_single_freq</code>

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
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108510)
Location: kernel/sched/cpufreq_schedutil.c:454
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81108510-ffffffff811086d0: sugov_update_single_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a460)
Location: kernel/sched/cpufreq_schedutil.c:335
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff8110a460-ffffffff8110a5e9: sugov_update_single_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:336
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81128a70-ffffffff81128c8d: sugov_update_single_freq (STB_LOCAL)
ffffffff81ca92eb-ffffffff81ca9342: sugov_update_single_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:330
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81145870-ffffffff81145c0e: sugov_update_single_freq (STB_LOCAL)
ffffffff81e581fc-ffffffff81e5825f: sugov_update_single_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:329
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81172a10-ffffffff81172dae: sugov_update_single_freq (STB_LOCAL)
ffffffff82057fa2-ffffffff82058005: sugov_update_single_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:331
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff81183a90-ffffffff81183d4d: sugov_update_single_freq (STB_LOCAL)
ffffffff820d6895-ffffffff820d68ed: sugov_update_single_freq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_freq(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:370
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
```
**Symbols:**

```
ffffffff811921a0-ffffffff81192466: sugov_update_single_freq (STB_LOCAL)
ffffffff821b1adb-ffffffff821b1b79: sugov_update_single_freq.cold (STB_LOCAL)
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
