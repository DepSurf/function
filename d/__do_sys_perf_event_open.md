# Function: <code>__do_sys_perf_event_open</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ddef0)
Location: kernel/events/core.c:10398
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff811ddef0-ffffffff811dedd7: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ee300)
Location: kernel/events/core.c:10441
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff811ee300-ffffffff811ef202: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205d40)
Location: kernel/events/core.c:10788
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff81205d40-ffffffff81206b2a: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812130d0)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff812130d0-ffffffff81213e97: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f1e0)
Location: kernel/events/core.c:11484
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff8123f1e0-ffffffff812400bd: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812495e0)
Location: kernel/events/core.c:11768
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff812495e0-ffffffff8124a603: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124d7a0)
Location: kernel/events/core.c:11935
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff8124d7a0-ffffffff8124e763: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812884f0)
Location: kernel/events/core.c:12079
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff812884f0-ffffffff812894c0: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dd6a0)
Location: kernel/events/core.c:12035
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff812dd6a0-ffffffff812de59e: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81345a20)
Location: kernel/events/core.c:12301
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff81345a20-ffffffff81346729: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81376ad0)
Location: kernel/events/core.c:12341
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff81376ad0-ffffffff8137782a: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139fd60)
Location: kernel/events/core.c:12425
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff8139fd60-ffffffff813a0b01: __do_sys_perf_event_open (STB_LOCAL)
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
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029d488)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__arm64_sys_perf_event_open
```
**Symbols:**

```
ffff80001029d488-ffff80001029def4: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ccc04)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__se_sys_perf_event_open
```
**Symbols:**

```
c04ccc04-c04cd708: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034df40)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__se_sys_perf_event_open
```
**Symbols:**

```
c00000000034df40-c00000000034ed50: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cb638)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__se_sys_perf_event_open
```
**Symbols:**

```
ffffffe0001cb638-ffffffe0001cbf08: __do_sys_perf_event_open (STB_LOCAL)
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
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b720)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff8120b720-ffffffff8120c4e7: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe4f0)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff811fe4f0-ffffffff811ff2b7: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812094c0)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff812094c0-ffffffff8120a287: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr *attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81218260)
Location: kernel/events/core.c:10889
Inline: False
Direct callers:
  - kernel/events/core.c:__ia32_sys_perf_event_open
  - kernel/events/core.c:__x64_sys_perf_event_open
```
**Symbols:**

```
ffffffff81218260-ffffffff81219055: __do_sys_perf_event_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
