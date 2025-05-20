# Function: <code>trace_event_raw_event_cgroup_migrate</code>

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
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122820)
Location: include/trace/events/cgroup.h:111
Inline: False
```
**Symbols:**

```
ffffffff81122820-ffffffff811229ea: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81122830)
Location: include/trace/events/cgroup.h:107
Inline: False
```
**Symbols:**

```
ffffffff81122830-ffffffff811229c5: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112e2e0)
Location: include/trace/events/cgroup.h:108
Inline: False
```
**Symbols:**

```
ffffffff8112e2e0-ffffffff8112e475: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113c990)
Location: include/trace/events/cgroup.h:108
Inline: False
```
**Symbols:**

```
ffffffff8113c990-ffffffff8113cb0a: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81148050)
Location: include/trace/events/cgroup.h:106
Inline: False
```
**Symbols:**

```
ffffffff81148050-ffffffff811481ed: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811533b0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff811533b0-ffffffff81153563: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f000)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8115f000-ffffffff8115f1b3: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f280)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8116f280-ffffffff8116f42c: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
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
ffffffff8116bca0-ffffffff8116befb: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
ffffffff81be46be-ffffffff81be46d6: trace_event_raw_event_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
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
ffffffff8116c750-ffffffff8116c9b4: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
ffffffff81bd64df-ffffffff81bd64f7: trace_event_raw_event_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
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
ffffffff81192350-ffffffff811925b4: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
ffffffff81cb2dcc-ffffffff81cb2de4: trace_event_raw_event_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
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
ffffffff811c51a0-ffffffff811c53f3: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
ffffffff81e63c9a-ffffffff81e63cb2: trace_event_raw_event_cgroup_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81207930)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81207930-ffffffff81207b9a: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121a050)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8121a050-ffffffff8121a26f: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81231b80)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81231b80-ffffffff81231d9f: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
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
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101cf548)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffff8000101cf548-ffff8000101cf6d4: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04135d4)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
c04135d4-c0413758: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000239910)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
c000000000239910-c000000000239b4c: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000149e44)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffe000149e44-ffffffe000149f8e: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
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
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157620)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81157620-ffffffff811577d3: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a940)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff8114a940-ffffffff8114aaf3: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811553f0)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff811553f0-ffffffff811555a3: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_cgroup_migrate(void *__data, struct cgroup *dst_cgrp, const char *path, struct task_struct *task, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162930)
Location: include/trace/events/cgroup.h:120
Inline: False
```
**Symbols:**

```
ffffffff81162930-ffffffff81162ae3: trace_event_raw_event_cgroup_migrate (STB_LOCAL)
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
