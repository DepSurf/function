# Function: <code>schedutil_cpu_util</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f5050)
Location: kernel/sched/cpufreq_schedutil.c:203
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff810f5050-ffffffff810f5150: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100cd0)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff81100cd0-ffffffff81100dd0: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b460)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff8110b460-ffffffff8110b5d4: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108320)
Location: kernel/sched/cpufreq_schedutil.c:194
Inline: False
Direct callers:
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff81108320-ffffffff81108494: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010165558)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffff800010165558-ffff800010165688: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b1ac0)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
c03b1ac0-c03b1bc0: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc7d0)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
c0000000001bc7d0-c0000000001bc9c8: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:2416
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9fe0)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff810f9fe0-ffffffff810fa0e0: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea1c0)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff810ea1c0-ffffffff810ea2c0: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f7200)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff810f7200-ffffffff810f729e: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int schedutil_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum schedutil_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81102280)
Location: kernel/sched/cpufreq_schedutil.c:206
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff81102280-ffffffff81102380: schedutil_cpu_util (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
