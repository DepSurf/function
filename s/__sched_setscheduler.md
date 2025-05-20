# Function: <code>__sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9630)
Location: kernel/sched/core.c:3784
Inline: False
Direct callers:
  - kernel/sched/core.c:_sched_setscheduler
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:normalize_rt_tasks
```
**Symbols:**

```
ffffffff810a9630-ffffffff810aa021: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac170)
Location: kernel/sched/core.c:4037
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810ac170-ffffffff810accac: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2250)
Location: kernel/sched/core.c:4074
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810b2250-ffffffff810b2d36: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae360)
Location: kernel/sched/core.c:3972
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810ae360-ffffffff810aec53: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5620)
Location: kernel/sched/core.c:4016
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810b5620-ffffffff810b5e96: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bd2d0)
Location: kernel/sched/core.c:4143
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810bd2d0-ffffffff810bdaf2: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6490)
Location: kernel/sched/core.c:4128
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810c6490-ffffffff810c6ca2: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc5b0)
Location: kernel/sched/core.c:4554
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810cc5b0-ffffffff810cd1f0: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d60e0)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810d60e0-ffffffff810d6bd7: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e07b0)
Location: kernel/sched/core.c:4989
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810e07b0-ffffffff810e1343: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddc60)
Location: kernel/sched/core.c:5762
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810ddc60-ffffffff810de678: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df6d0)
Location: kernel/sched/core.c:6062
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810df6d0-ffffffff810e026d: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f47e0)
Location: kernel/sched/core.c:7225
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:sched_set_normal
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff810f47e0-ffffffff810f5436: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81111160)
Location: kernel/sched/core.c:7380
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:sched_set_normal
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff81111160-ffffffff81111e70: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81138120)
Location: kernel/sched/core.c:7522
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:sched_set_normal
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff81138120-ffffffff81138e30: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811472a0)
Location: kernel/sched/core.c:7623
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:sched_set_normal
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff811472a0-ffffffff8114809c: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81152ad0)
Location: kernel/sched/core.c:7684
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_set_normal
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
```
**Symbols:**

```
ffffffff81152ad0-ffffffff811538cc: __sched_setscheduler (STB_LOCAL)
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
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010136ac8)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
```
**Symbols:**

```
ffff800010136ac8-ffff8000101373c0: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0385438)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
c0385438-c0386314: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000181920)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
```
**Symbols:**

```
c000000000181920-c0000000001829bc: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e742c)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
```
**Symbols:**

```
ffffffe0000e742c-ffffffe0000e7b5a: __sched_setscheduler (STB_LOCAL)
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
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d04e0)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810d04e0-ffffffff810d11ae: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be610)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810be610-ffffffff810bf520: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce8e0)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810ce8e0-ffffffff810cf26d: __sched_setscheduler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sched_setscheduler(struct task_struct *p, const struct sched_attr *attr, bool user, bool pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d79c0)
Location: kernel/sched/core.c:4756
Inline: False
Direct callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:sched_setattr_nocheck
  - kernel/sched/core.c:_sched_setscheduler
```
**Symbols:**

```
ffffffff810d79c0-ffffffff810d8889: __sched_setscheduler (STB_LOCAL)
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
