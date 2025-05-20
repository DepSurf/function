# Function: <code>sched_core_clone_cookie</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sched_core_clone_cookie(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core_sched.c (ffffffff8112c30a)
Location: kernel/sched/core_sched.c:96
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_fork
Direct callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff8112bfd0-ffffffff8112c04c: sched_core_clone_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sched_core_clone_cookie(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114b51a)
Location: kernel/sched/core_sched.c:98
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_fork
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff81143510-ffffffff81143590: sched_core_clone_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sched_core_clone_cookie(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179f8a)
Location: kernel/sched/core_sched.c:99
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_fork
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff8116ff60-ffffffff8116ffe0: sched_core_clone_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sched_core_clone_cookie(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118aaea)
Location: kernel/sched/core_sched.c:99
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_fork
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff8117fc20-ffffffff8117fca0: sched_core_clone_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int sched_core_clone_cookie(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811993fa)
Location: kernel/sched/core_sched.c:99
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_fork
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff8118d6a0-ffffffff8118d720: sched_core_clone_cookie (STB_LOCAL)
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
