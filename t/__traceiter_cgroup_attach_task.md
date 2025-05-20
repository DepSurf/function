# Function: <code>__traceiter_cgroup_attach_task</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116aab0)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff8116aab0-ffffffff8116ab0c: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116b710)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff8116b710-ffffffff8116b76a: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81191310)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff81191310-ffffffff8119136a: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c0a40)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff811c0a40-ffffffff811c0aa9: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81202ef0)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff81202ef0-ffffffff81202f59: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812182f0)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff812182f0-ffffffff81218359: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cgroup_attach_task(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8122feb0)
Location: include/trace/events/cgroup.h:150
Inline: False
```
**Symbols:**

```
ffffffff8122feb0-ffffffff8122ff19: __traceiter_cgroup_attach_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
