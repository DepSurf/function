# Function: <code>__sched_core_set</code>

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
void __sched_core_set(struct task_struct *p, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core_sched.c (ffffffff8112c794)
Location: kernel/sched/core_sched.c:118
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
Direct callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff8112c270-ffffffff8112c2d3: __sched_core_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __sched_core_set(struct task_struct *p, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:120
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff81144970-ffffffff81144b37: __sched_core_set (STB_LOCAL)
ffffffff81e57f04-ffffffff81e57f19: __sched_core_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __sched_core_set(struct task_struct *p, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:121
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff81170ca0-ffffffff81170ead: __sched_core_set (STB_LOCAL)
ffffffff82057f0a-ffffffff82057f1f: __sched_core_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __sched_core_set(struct task_struct *p, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:121
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff81180f70-ffffffff8118117a: __sched_core_set (STB_LOCAL)
ffffffff820d6699-ffffffff820d66ae: __sched_core_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __sched_core_set(struct task_struct *p, long unsigned int cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:121
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
```
**Symbols:**

```
ffffffff8118f2e0-ffffffff8118f4ea: __sched_core_set (STB_LOCAL)
ffffffff821b18bb-ffffffff821b18d0: __sched_core_set.cold (STB_LOCAL)
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
