# Function: <code>__cgroup_procs_start</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81134630)
Location: kernel/cgroup/cgroup.c:4267
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81134630-ffffffff81134706: __cgroup_procs_start.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142d50)
Location: kernel/cgroup/cgroup.c:4304
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81142d50-ffffffff81142e26: __cgroup_procs_start.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e880)
Location: kernel/cgroup/cgroup.c:4373
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8114e880-ffffffff8114e956: __cgroup_procs_start.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a3e0)
Location: kernel/cgroup/cgroup.c:4663
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8115a3e0-ffffffff8115a4b8: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166090)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81166090-ffffffff8116616b: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177220)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81177220-ffffffff811772fb: __cgroup_procs_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173f00)
Location: kernel/cgroup/cgroup.c:4612
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81173f00-ffffffff81173fdc: __cgroup_procs_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174ad0)
Location: kernel/cgroup/cgroup.c:4625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81174ad0-ffffffff81174baf: __cgroup_procs_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4800
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8119bd60-ffffffff8119be72: __cgroup_procs_start (STB_LOCAL)
ffffffff81cb307e-ffffffff81cb30a3: __cgroup_procs_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4811
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff811cbff0-ffffffff811cc11e: __cgroup_procs_start (STB_LOCAL)
ffffffff81e63e6c-ffffffff81e63e91: __cgroup_procs_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5008
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8120f4f0-ffffffff8120f61d: __cgroup_procs_start (STB_LOCAL)
ffffffff8205c30a-ffffffff8205c32f: __cgroup_procs_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:4985
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81224f00-ffffffff8122502d: __cgroup_procs_start (STB_LOCAL)
ffffffff820dab24-ffffffff820dab49: __cgroup_procs_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5021
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8123cbf0-ffffffff8123cd1d: __cgroup_procs_start (STB_LOCAL)
ffffffff821b67b7-ffffffff821b67dc: __cgroup_procs_start.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7d28)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffff8000101d7d28-ffff8000101d7e20: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__cgroup_procs_start(struct seq_file *s, loff_t *pos, unsigned int iter_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a96c)
Location: kernel/cgroup/cgroup.c:4677
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
c041a96c-c041aa80: __cgroup_procs_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000244b30)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
c000000000244b30-c000000000244cac: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150dae)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffe000150dae-ffffffe000150e7e: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e6b0)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8115e6b0-ffffffff8115e78b: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151960)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff81151960-ffffffff81151a3b: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c480)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff8115c480-ffffffff8115c55b: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811695a0)
Location: kernel/cgroup/cgroup.c:4677
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_start
```
**Symbols:**

```
ffffffff811695a0-ffffffff8116967b: __cgroup_procs_start.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
