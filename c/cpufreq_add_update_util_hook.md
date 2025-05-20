# Function: <code>cpufreq_add_update_util_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, long unsigned int, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810ce340)
Location: kernel/sched/cpufreq.c:34
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810ce340-ffffffff810ce3a2: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810d4360)
Location: kernel/sched/cpufreq.c:34
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810d4360-ffffffff810d43c2: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810d34f0)
Location: kernel/sched/cpufreq.c:34
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810d34f0-ffffffff810d3534: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810db0c0)
Location: kernel/sched/cpufreq.c:34
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810db0c0-ffffffff810db104: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810e3200)
Location: kernel/sched/cpufreq.c:33
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810e3200-ffffffff810e3244: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810ed930)
Location: kernel/sched/cpufreq.c:30
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810ed930-ffffffff810ed974: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpufreq.c (0)
Location: kernel/sched/cpufreq.c:30
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810f4729-ffffffff810f474f: cpufreq_add_update_util_hook.cold (STB_LOCAL)
ffffffff810f46e0-ffffffff810f4729: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81100370)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81100370-ffffffff811003b4: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff8110aa10)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8110aa10-ffffffff8110aa54: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81107920)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81107920-ffffffff81107964: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff811099f0)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff811099f0-ffffffff81109a34: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81127eb0)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81127eb0-ffffffff81127f4d: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113c240)
Location: kernel/sched/cpufreq.c:29
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff8113c240-ffffffff8113c2f5: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166e90)
Location: kernel/sched/cpufreq.c:29
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81166e90-ffffffff81166f45: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177260)
Location: kernel/sched/cpufreq.c:29
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81177260-ffffffff81177315: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811851d0)
Location: kernel/sched/cpufreq.c:29
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff811851d0-ffffffff81185285: cpufreq_add_update_util_hook (STB_GLOBAL)
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffff800010164a10)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
**Symbols:**

```
ffff800010164a10-ffff800010164a9c: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (c03b1044)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
**Symbols:**

```
c03b1044-c03b10d8: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (c0000000001bb950)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
**Symbols:**

```
c0000000001bb950-c0000000001bb9c8: cpufreq_add_update_util_hook (STB_GLOBAL)
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
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f9680)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810f9680-ffffffff810f96c4: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810e9860)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810e9860-ffffffff810e98a4: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff810f68a0)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff810f68a0-ffffffff810f68e4: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpufreq_add_update_util_hook(int cpu, struct update_util_data *data, void (*func)(struct update_util_data *, u64, unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq.c (ffffffff81101900)
Location: kernel/sched/cpufreq.c:32
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy
```
**Symbols:**

```
ffffffff81101900-ffffffff81101944: cpufreq_add_update_util_hook (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*func)(struct update_util_data *, u64, long unsigned int, long unsigned int)</code> ➡️ <code>void (*func)(struct update_util_data *, u64, unsigned int)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
