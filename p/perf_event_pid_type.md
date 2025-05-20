# Function: <code>perf_event_pid_type</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3c00)
Location: kernel/events/core.c:1300
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
**Symbols:**

```
ffffffff811b3c00-ffffffff811b3c3d: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3110)
Location: kernel/events/core.c:1323
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff811d3110-ffffffff811d314d: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3400)
Location: kernel/events/core.c:1323
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff811e3400-ffffffff811e343d: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa5d0)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff811fa5d0-ffffffff811fa60d: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812076a0)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff812076a0-ffffffff812076dd: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237d2d)
Location: kernel/events/core.c:1387
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241afd)
Location: kernel/events/core.c:1405
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812455ad)
Location: kernel/events/core.c:1403
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128055d)
Location: kernel/events/core.c:1434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d5320)
Location: kernel/events/core.c:1343
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133df20)
Location: kernel/events/core.c:1316
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136f100)
Location: kernel/events/core.c:1316
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813983a0)
Location: kernel/events/core.c:1327
Inline: True
Inline callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
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
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102910c8)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffff8000102910c8-ffff800010291114: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1108)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
```
**Symbols:**

```
c04c1108-c04c1150: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033ee20)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
c00000000033ee20-c00000000033ee98: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c3caa)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffe0001c3caa-ffffffe0001c3cea: perf_event_pid_type (STB_LOCAL)
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
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffcc0)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff811ffcc0-ffffffff811ffcfd: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2a10)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff811f2a10-ffffffff811f2a4d: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fda90)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff811fda90-ffffffff811fdacd: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 perf_event_pid_type(struct perf_event *event, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120caf0)
Location: kernel/events/core.c:1325
Inline: False
Direct callers:
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_switch_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_namespaces_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_read_event
  - kernel/events/core.c:perf_event_read_event
```
**Symbols:**

```
ffffffff8120caf0-ffffffff8120cb2d: perf_event_pid_type (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
