# Function: <code>perf_event_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117e810)
Location: kernel/events/core.c:7855
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8117e810-ffffffff8117eed2: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811902d0)
Location: kernel/events/core.c:8956
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811902d0-ffffffff81190bfe: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119f190)
Location: kernel/events/core.c:9150
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8119f190-ffffffff8119fb0d: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811a5c20)
Location: kernel/events/core.c:9370
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811a5c20-ffffffff811a6538: perf_event_alloc.part.85 (STB_LOCAL)
ffffffff811a6540-ffffffff811a656e: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811b9810)
Location: kernel/events/core.c:9397
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811b9810-ffffffff811ba13d: perf_event_alloc.part.86 (STB_LOCAL)
ffffffff811ba140-ffffffff811ba16e: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d8b50)
Location: kernel/events/core.c:9919
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811d8b50-ffffffff811d94a6: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e9050)
Location: kernel/events/core.c:9962
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811e9050-ffffffff811e99db: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202340)
Location: kernel/events/core.c:10294
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81202340-ffffffff81202e03: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f170)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8120f170-ffffffff8120fcb6: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a350)
Location: kernel/events/core.c:10991
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8123a350-ffffffff8123ac6c: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243760)
Location: kernel/events/core.c:11275
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81243760-ffffffff812440a7: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248720)
Location: kernel/events/core.c:11420
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81248720-ffffffff8124907a: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81283520)
Location: kernel/events/core.c:11532
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81283520-ffffffff81283e98: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d6520)
Location: kernel/events/core.c:11468
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812d6520-ffffffff812d70d6: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133f300)
Location: kernel/events/core.c:11769
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8133f300-ffffffff8133fe78: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813704d0)
Location: kernel/events/core.c:11809
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff813704d0-ffffffff81370e07: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813997d0)
Location: kernel/events/core.c:11893
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff813997d0-ffffffff8139a107: perf_event_alloc (STB_LOCAL)
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
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010297200)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffff800010297200-ffff800010297b10: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c73a8)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
c04c73a8-c04c7c68: perf_event_alloc (STB_LOCAL)
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
In kernel/events/core.c (c00000000034e0b4)
Location: kernel/events/core.c:10410
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
c000000000346ae0-c000000000347800: perf_event_alloc.part.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffe0001cb72a)
Location: kernel/events/core.c:10410
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffe0001c9d40-ffffffe0001ca6aa: perf_event_alloc.part.0 (STB_LOCAL)
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
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207790)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81207790-ffffffff812082d6: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa8c0)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811fa8c0-ffffffff811fb462: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205560)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81205560-ffffffff812060a6: perf_event_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct perf_event *perf_event_alloc(struct perf_event_attr *attr, int cpu, struct task_struct *task, struct perf_event *group_leader, struct perf_event *parent_event, perf_overflow_handler_t overflow_handler, void *context, int cgroup_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812143d0)
Location: kernel/events/core.c:10410
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812143d0-ffffffff81214f5d: perf_event_alloc (STB_LOCAL)
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
