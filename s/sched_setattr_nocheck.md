# Function: <code>sched_setattr_nocheck</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1550)
Location: kernel/sched/core.c:4427
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810c1550-ffffffff810c1567: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca880)
Location: kernel/sched/core.c:4412
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810ca880-ffffffff810ca897: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2530)
Location: kernel/sched/core.c:4849
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810d2530-ffffffff810d2547: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc9a0)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810dc9a0-ffffffff810dc9b7: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5520)
Location: kernel/sched/core.c:5297
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810e5520-ffffffff810e5537: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de820)
Location: kernel/sched/core.c:6072
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810e3080-ffffffff810e3097: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0410)
Location: kernel/sched/core.c:6373
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810e5220-ffffffff810e5237: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5490)
Location: kernel/sched/core.c:7536
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_normal
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810f5440-ffffffff810f5457: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81111ed0)
Location: kernel/sched/core.c:7644
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_normal
Direct callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff81111e70-ffffffff81111e93: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81138eb0)
Location: kernel/sched/core.c:7786
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_normal
Direct callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff81138e40-ffffffff81138e63: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148120)
Location: kernel/sched/core.c:7895
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_normal
Direct callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff811480b0-ffffffff811480d3: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81153950)
Location: kernel/sched/core.c:7956
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_normal
Direct callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff811538e0-ffffffff81153903: sched_setattr_nocheck (STB_GLOBAL)
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
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c528)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffff80001013c528-ffff80001013c564: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c224)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c038c224-c038c248: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018ab80)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c00000000018ab80-c00000000018ab9c: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eb89c)
Location: kernel/sched/core.c:5064
Inline: False
```
**Symbols:**

```
ffffffe0000eb89c-ffffffe0000eb8d2: sched_setattr_nocheck (STB_GLOBAL)
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
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6bb0)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810d6bb0-ffffffff810d6bc7: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c54a0)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810c54a0-ffffffff810c54b7: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d37f0)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810d37f0-ffffffff810d3807: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct *p, const struct sched_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de770)
Location: kernel/sched/core.c:5064
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810de770-ffffffff810de787: sched_setattr_nocheck (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
