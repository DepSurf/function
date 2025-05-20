# Function: <code>sugov_iowait_boost</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d4e9f)
Location: kernel/sched/cpufreq_schedutil.c:179
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d40af)
Location: kernel/sched/cpufreq_schedutil.c:182
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, long unsigned int *util, long unsigned int *max);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db580)
Location: kernel/sched/cpufreq_schedutil.c:217
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810db580-ffffffff810db5d2: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e37b0)
Location: kernel/sched/cpufreq_schedutil.c:251
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810e37b0-ffffffff810e381c: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ede30)
Location: kernel/sched/cpufreq_schedutil.c:326
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810ede30-ffffffff810ede9c: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4750)
Location: kernel/sched/cpufreq_schedutil.c:341
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810f4750-ffffffff810f47b0: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100410)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff81100410-ffffffff81100470: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110aab0)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff8110aab0-ffffffff8110ab10: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811079c0)
Location: kernel/sched/cpufreq_schedutil.c:331
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff811079c0-ffffffff81107a20: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109a90)
Location: kernel/sched/cpufreq_schedutil.c:214
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81109a90-ffffffff81109aee: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8112872e)
Location: kernel/sched/cpufreq_schedutil.c:215
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff811286f0-ffffffff81128769: sugov_iowait_boost (STB_LOCAL)
ffffffff81ca9298-ffffffff81ca92ad: sugov_iowait_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113e9ac)
Location: kernel/sched/cpufreq_schedutil.c:208
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff8113e960-ffffffff8113e9f5: sugov_iowait_boost (STB_LOCAL)
ffffffff81e56c78-ffffffff81e56c8d: sugov_iowait_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168f7c)
Location: kernel/sched/cpufreq_schedutil.c:207
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81168f30-ffffffff81168fc5: sugov_iowait_boost (STB_LOCAL)
ffffffff82057c53-ffffffff82057c68: sugov_iowait_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811796ec)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff811796a0-ffffffff81179735: sugov_iowait_boost (STB_LOCAL)
ffffffff820d6473-ffffffff820d6488: sugov_iowait_boost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118722c)
Location: kernel/sched/cpufreq_schedutil.c:248
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff811871e0-ffffffff81187275: sugov_iowait_boost (STB_LOCAL)
ffffffff821b15c5-ffffffff821b15da: sugov_iowait_boost.cold (STB_LOCAL)
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
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010164b18)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffff800010164b18-ffff800010164bc4: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b1150)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
c03b1150-c03b11f8: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bba40)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
c0000000001bba40-c0000000001bbae8: sugov_iowait_boost (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9720)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810f9720-ffffffff810f9780: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9900)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810e9900-ffffffff810e9960: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6940)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810f6940-ffffffff810f69a0: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sugov_iowait_boost(struct sugov_cpu *sg_cpu, u64 time, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811019a0)
Location: kernel/sched/cpufreq_schedutil.c:344
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff811019a0-ffffffff81101a00: sugov_iowait_boost (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 time</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *util</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *max</code>
</li>
</ul>
</details>
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
