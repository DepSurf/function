# Function: <code>SYSC_perf_event_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811817c0)
Location: kernel/events/core.c:8246
Inline: False
Direct callers:
  - kernel/events/core.c:SyS_perf_event_open
```
**Symbols:**

```
ffffffff811817c0-ffffffff81182569: SYSC_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811935d0)
Location: kernel/events/core.c:9381
Inline: False
Direct callers:
  - kernel/events/core.c:SyS_perf_event_open
```
**Symbols:**

```
ffffffff811935d0-ffffffff81194400: SYSC_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2db0)
Location: kernel/events/core.c:9619
Inline: False
Direct callers:
  - kernel/events/core.c:SyS_perf_event_open
```
**Symbols:**

```
ffffffff811a2db0-ffffffff811a3dd1: SYSC_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811aa3c0)
Location: kernel/events/core.c:9842
Inline: False
Direct callers:
  - kernel/events/core.c:SyS_perf_event_open
```
**Symbols:**

```
ffffffff811aa3c0-ffffffff811ab3d9: SYSC_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bdcb0)
Location: kernel/events/core.c:9869
Inline: False
Direct callers:
  - kernel/events/core.c:SyS_perf_event_open
```
**Symbols:**

```
ffffffff811bdcb0-ffffffff811becf5: SYSC_perf_event_open (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
