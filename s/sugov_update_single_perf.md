# Function: <code>sugov_update_single_perf</code>

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
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108900)
Location: kernel/sched/cpufreq_schedutil.c:491
Inline: False
```
**Symbols:**

```
ffffffff81108900-ffffffff81108a31: sugov_update_single_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a5f0)
Location: kernel/sched/cpufreq_schedutil.c:375
Inline: False
```
**Symbols:**

```
ffffffff8110a5f0-ffffffff8110a726: sugov_update_single_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (0)
Location: kernel/sched/cpufreq_schedutil.c:376
Inline: False
```
**Symbols:**

```
ffffffff81128c90-ffffffff81128e2d: sugov_update_single_perf (STB_LOCAL)
ffffffff81ca9342-ffffffff81ca9357: sugov_update_single_perf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:373
Inline: False
```
**Symbols:**

```
ffffffff81145c10-ffffffff81145efd: sugov_update_single_perf (STB_LOCAL)
ffffffff81e5825f-ffffffff81e5827a: sugov_update_single_perf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:372
Inline: False
```
**Symbols:**

```
ffffffff81172dc0-ffffffff811730ad: sugov_update_single_perf (STB_LOCAL)
ffffffff82058005-ffffffff82058020: sugov_update_single_perf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:377
Inline: False
```
**Symbols:**

```
ffffffff81183d60-ffffffff81183f91: sugov_update_single_perf (STB_LOCAL)
ffffffff820d68ed-ffffffff820d6908: sugov_update_single_perf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sugov_update_single_perf(struct update_util_data *hook, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq_schedutil.c:417
Inline: False
```
**Symbols:**

```
ffffffff81192480-ffffffff8119266d: sugov_update_single_perf (STB_LOCAL)
ffffffff821b1b79-ffffffff821b1b94: sugov_update_single_perf.cold (STB_LOCAL)
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
