# Function: <code>do_set_cpus_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab030)
Location: kernel/sched/core.c:1167
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810ab030-ffffffff810ab115: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810adc80)
Location: kernel/sched/core.c:1085
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810adc80-ffffffff810add65: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3da0)
Location: kernel/sched/core.c:1096
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810b3da0-ffffffff810b3edc: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afd70)
Location: kernel/sched/core.c:1021
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810afd70-ffffffff810afe74: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7140)
Location: kernel/sched/core.c:1036
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810b7140-ffffffff810b7283: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bed10)
Location: kernel/sched/core.c:1033
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810bed10-ffffffff810bee36: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7fb0)
Location: kernel/sched/core.c:1028
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810c7fb0-ffffffff810c80c6: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf240)
Location: kernel/sched/core.c:1471
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810cf240-ffffffff810cf740: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9000)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810d9000-ffffffff810d95de: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2670)
Location: kernel/sched/core.c:1656
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810e2670-ffffffff810e282b: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc76a)
Location: kernel/sched/core.c:2110
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - fs/io-wq.c:io_wq_worker_affinity
```
**Symbols:**

```
ffffffff810dfb00-ffffffff810dfb12: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddc36)
Location: kernel/sched/core.c:2117
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810e18e0-ffffffff810e18f2: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f2431)
Location: kernel/sched/core.c:2495
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810f7a60-ffffffff810f7a72: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110e2ae)
Location: kernel/sched/core.c:2594
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff81113cd0-ffffffff81113cec: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81135025)
Location: kernel/sched/core.c:2600
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff8113af00-ffffffff8113af69: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144225)
Location: kernel/sched/core.c:2776
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff8114a1f0-ffffffff8114a25a: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114f745)
Location: kernel/sched/core.c:2804
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
Direct callers:
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff81155d60-ffffffff81155dca: do_set_cpus_allowed (STB_GLOBAL)
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
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101392b8)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffff8000101392b8-ffff800010139428: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038864c)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
c038864c-c0388c1c: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000185a20)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
c000000000185a20-c0000000001860e8: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e9028)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffe0000e9028-ffffffe0000e912a: do_set_cpus_allowed (STB_GLOBAL)
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
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d34d0)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810d34d0-ffffffff810d3ab0: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1b00)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810c1b00-ffffffff810c20de: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0bb0)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810d0bb0-ffffffff810d0d01: do_set_cpus_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dac70)
Location: kernel/sched/core.c:1591
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
```
**Symbols:**

```
ffffffff810dac70-ffffffff810db250: do_set_cpus_allowed (STB_GLOBAL)
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
