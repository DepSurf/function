# Function: <code>__traceiter_cgroup_unfreeze</code>

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
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116aa60)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff8116aa60-ffffffff8116aaa7: __traceiter_cgroup_unfreeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116b6c0)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff8116b6c0-ffffffff8116b705: __traceiter_cgroup_unfreeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811912c0)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff811912c0-ffffffff81191305: __traceiter_cgroup_unfreeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c09f0)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff811c09f0-ffffffff811c0a3f: __traceiter_cgroup_unfreeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81202e90)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff81202e90-ffffffff81202edf: __traceiter_cgroup_unfreeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81218290)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff81218290-ffffffff812182df: __traceiter_cgroup_unfreeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cgroup_unfreeze(void *__data, struct cgroup *cgrp, const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8122fe50)
Location: include/trace/events/cgroup.h:113
Inline: False
```
**Symbols:**

```
ffffffff8122fe50-ffffffff8122fe9f: __traceiter_cgroup_unfreeze (STB_GLOBAL)
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
