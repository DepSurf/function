# Function: <code>perf_trace_cgroup_migrate</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122d00)
Location: include/trace/events/cgroup.h:111
Inline: False
```
**Symbols:**

```
ffffffff81122d00-ffffffff81122f1e: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81122f60)
Location: include/trace/events/cgroup.h:107
Inline: False
```
**Symbols:**

```
ffffffff81122f60-ffffffff8112311f: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112ebe0)
Location: include/trace/events/cgroup.h:108
Inline: False
```
**Symbols:**

```
ffffffff8112ebe0-ffffffff8112eda3: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113cee0)
Location: include/trace/events/cgroup.h:108
Inline: False
```
**Symbols:**

```
ffffffff8113cee0-ffffffff8113d0a3: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81148810)
Location: include/trace/events/cgroup.h:106
Inline: False
```
**Symbols:**

```
ffffffff81148810-ffffffff811489e5: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81153d10)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81153d10-ffffffff81153ee7: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f960)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8115f960-ffffffff8115fb37: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170c40)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81170c40-ffffffff81170e19: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8116d750-ffffffff8116d9ce: perf_trace_cgroup_migrate (STB_LOCAL)
ffffffff81be46d6-ffffffff81be46ee: perf_trace_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8116e3d0-ffffffff8116e659: perf_trace_cgroup_migrate (STB_LOCAL)
ffffffff81bd64f7-ffffffff81bd650f: perf_trace_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81194560-ffffffff811947e9: perf_trace_cgroup_migrate (STB_LOCAL)
ffffffff81cb2e30-ffffffff81cb2e48: perf_trace_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff811c2610-ffffffff811c28be: perf_trace_cgroup_migrate (STB_LOCAL)
ffffffff81e63be5-ffffffff81e63bfd: perf_trace_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81204990)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81204990-ffffffff81204c53: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121a280)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8121a280-ffffffff8121a4e8: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81231db0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81231db0-ffffffff81232018: perf_trace_cgroup_migrate (STB_LOCAL)
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
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d0860)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffff8000101d0860-ffff8000101d0a10: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041410c)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
c041410c-c04142e8: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023abe0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
c00000000023abe0-c00000000023ae38: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014a322)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffe00014a322-ffffffe00014a482: perf_trace_cgroup_migrate (STB_LOCAL)
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
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157f80)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81157f80-ffffffff81158157: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114b2a0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8114b2a0-ffffffff8114b477: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155d50)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81155d50-ffffffff81155f27: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811634c0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff811634c0-ffffffff81163697: perf_trace_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *path</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, dst_cgrp, task, threadgroup</code> ➡️ <code>__data, dst_cgrp, path, task, threadgroup</code>
</li>
</ul>
</details>
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
