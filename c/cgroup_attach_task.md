# Function: <code>cgroup_attach_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81116d60)
Location: kernel/cgroup.c:2749
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff81116d60-ffffffff81116e4d: cgroup_attach_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111e090)
Location: kernel/cgroup.c:2804
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8111e090-ffffffff8111e1ae: cgroup_attach_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811263c0)
Location: kernel/cgroup.c:2809
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811263c0-ffffffff8112653e: cgroup_attach_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811253c0)
Location: kernel/cgroup/cgroup.c:2383
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811253c0-ffffffff811255ad: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131690)
Location: kernel/cgroup/cgroup.c:2592
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81131690-ffffffff8113186b: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113fde0)
Location: kernel/cgroup/cgroup.c:2610
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8113fde0-ffffffff8113ff9e: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114b800)
Location: kernel/cgroup/cgroup.c:2651
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8114b800-ffffffff8114ba02: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811570e0)
Location: kernel/cgroup/cgroup.c:2791
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811570e0-ffffffff811572eb: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162d50)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81162d50-ffffffff81162f5b: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174360)
Location: kernel/cgroup/cgroup.c:2718
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81174360-ffffffff8117455e: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171040)
Location: kernel/cgroup/cgroup.c:2714
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81171040-ffffffff8117122c: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171cc0)
Location: kernel/cgroup/cgroup.c:2727
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81171cc0-ffffffff81171e9a: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81198780)
Location: kernel/cgroup/cgroup.c:2782
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81198780-ffffffff8119894b: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c8870)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811c8870-ffffffff811c8a67: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120b870)
Location: kernel/cgroup/cgroup.c:2888
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8120b870-ffffffff8120ba67: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81220e70)
Location: kernel/cgroup/cgroup.c:2857
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81220e70-ffffffff81221067: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81238b10)
Location: kernel/cgroup/cgroup.c:2866
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81238b10-ffffffff81238d44: cgroup_attach_task (STB_GLOBAL)
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
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d4340)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffff8000101d4340-ffff8000101d45c4: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0416f84)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
c0416f84-c04171d4: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023f890)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
c00000000023f890-c00000000023fb80: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014d8a6)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffe00014d8a6-ffffffe00014dac2: cgroup_attach_task (STB_GLOBAL)
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
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b370)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8115b370-ffffffff8115b57b: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e660)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff8114e660-ffffffff8114e865: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159140)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff81159140-ffffffff8115934b: cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup *dst_cgrp, struct task_struct *leader, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811661a0)
Location: kernel/cgroup/cgroup.c:2792
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
**Symbols:**

```
ffffffff811661a0-ffffffff811663c1: cgroup_attach_task (STB_GLOBAL)
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
