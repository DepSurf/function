# Function: <code>sched_setaffinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810addf0)
Location: kernel/sched/core.c:4399
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
```
**Symbols:**

```
ffffffff810addf0-ffffffff810adfcb: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b07f0)
Location: kernel/sched/core.c:4649
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
```
**Symbols:**

```
ffffffff810b07f0-ffffffff810b09cd: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6980)
Location: kernel/sched/core.c:4686
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810b6980-ffffffff810b6b92: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2bd0)
Location: kernel/sched/core.c:4583
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810b2bd0-ffffffff810b2de3: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9fd0)
Location: kernel/sched/core.c:4627
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810b9fd0-ffffffff810ba1e3: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1570)
Location: kernel/sched/core.c:4762
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810c1570-ffffffff810c1799: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca8a0)
Location: kernel/sched/core.c:4747
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810ca8a0-ffffffff810caac9: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2550)
Location: kernel/sched/core.c:5200
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810d2550-ffffffff810d278c: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc9c0)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810dc9c0-ffffffff810dcbfc: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5540)
Location: kernel/sched/core.c:5624
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
**Symbols:**

```
ffffffff810e5540-ffffffff810e57da: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3130)
Location: kernel/sched/core.c:6448
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
**Symbols:**

```
ffffffff810e3130-ffffffff810e33f2: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e52d0)
Location: kernel/sched/core.c:6749
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
**Symbols:**

```
ffffffff810e52d0-ffffffff810e558e: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fc4e0)
Location: kernel/sched/core.c:7989
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x64_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
**Symbols:**

```
ffffffff810fc4e0-ffffffff810fc664: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81118ad0)
Location: kernel/sched/core.c:8097
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
**Symbols:**

```
ffffffff81118ad0-ffffffff81118c7a: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81140220)
Location: kernel/sched/core.c:8259
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
**Symbols:**

```
ffffffff81140220-ffffffff8114044c: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8368
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff820d52f4-ffffffff820d530f: sched_setaffinity.cold (STB_LOCAL)
ffffffff8114f580-ffffffff8114f800: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8397
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
```
**Symbols:**

```
ffffffff821b026c-ffffffff821b0287: sched_setaffinity.cold (STB_LOCAL)
ffffffff8115b420-ffffffff8115b6ae: sched_setaffinity (STB_GLOBAL)
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
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c568)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_setaffinity
  - kernel/compat.c:__arm64_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffff80001013c568-ffff80001013c74c: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c908)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
c038c908-c038caf0: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018aba0)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__do_sys_sched_setaffinity
  - kernel/compat.c:__do_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
c00000000018aba0-c00000000018ae24: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ebda6)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffe0000ebda6-ffffffe0000ebf1c: sched_setaffinity (STB_GLOBAL)
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
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6bd0)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810d6bd0-ffffffff810d6e0c: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c54c0)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/rcu/tree.c:rcu_bind_current_to_nocb
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810c54c0-ffffffff810c56fc: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3810)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810d3810-ffffffff810d3a4c: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int sched_setaffinity(pid_t pid, const struct cpumask *in_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de790)
Location: kernel/sched/core.c:5391
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
  - kernel/compat.c:__x32_compat_sys_sched_setaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff810de790-ffffffff810de9ee: sched_setaffinity (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
