# Function: <code>cpufreq_this_cpu_can_update</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e32a6)
Location: include/linux/cpufreq.h:574
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_should_update_freq
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825f2d)
Location: include/linux/cpufreq.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ed9d9)
Location: include/linux/cpufreq.h:566
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_should_update_freq
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851e0d)
Location: include/linux/cpufreq.h:566
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4925)
Location: include/linux/cpufreq.h:595
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_should_update_freq
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8189535c)
Location: include/linux/cpufreq.h:595
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff811003c0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff811003c0-ffffffff81100403: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff8110aa60)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff8110aa60-ffffffff8110aaa3: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81107970)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81107970-ffffffff811079b3: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81109a40)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81109a40-ffffffff81109a83: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq.c (0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81ca91f7-ffffffff81ca9212: cpufreq_this_cpu_can_update.cold (STB_LOCAL)
ffffffff81127f50-ffffffff81127fa1: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq.c:69
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81e5818e-ffffffff81e581a9: cpufreq_this_cpu_can_update.cold (STB_LOCAL)
ffffffff81145570-ffffffff811455d5: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq.c:69
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff82057f34-ffffffff82057f4f: cpufreq_this_cpu_can_update.cold (STB_LOCAL)
ffffffff811726e0-ffffffff81172745: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq.c:69
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff820d6827-ffffffff820d6842: cpufreq_this_cpu_can_update.cold (STB_LOCAL)
ffffffff81183790-ffffffff811837f5: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/cpufreq.c:69
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff821b1a6d-ffffffff821b1a88: cpufreq_this_cpu_can_update.cold (STB_LOCAL)
ffffffff81191ed0-ffffffff81191f35: cpufreq_this_cpu_can_update (STB_GLOBAL)
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffff800010164aa0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffff800010164aa0-ffff800010164b14: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (c03b10d8)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
c03b10d8-c03b1150: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (c0000000001bb9d0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
c0000000001bb9d0-c0000000001bba38: cpufreq_this_cpu_can_update (STB_GLOBAL)
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
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f96d0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff810f96d0-ffffffff810f9713: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810e98b0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff810e98b0-ffffffff810e98f3: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f68f0)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff810f68f0-ffffffff810f6933: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cpufreq_this_cpu_can_update(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81101950)
Location: kernel/sched/cpufreq.c:72
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
**Symbols:**

```
ffffffff81101950-ffffffff81101993: cpufreq_this_cpu_can_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
