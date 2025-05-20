# Function: <code>sched_cgroup_fork</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_cgroup_fork(struct task_struct *p, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fabf0)
Location: kernel/sched/core.c:4395
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810fabf0-ffffffff810fad22: sched_cgroup_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_cgroup_fork(struct task_struct *p, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81117000)
Location: kernel/sched/core.c:4573
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81117000-ffffffff8111712e: sched_cgroup_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_cgroup_fork(struct task_struct *p, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113e4c0)
Location: kernel/sched/core.c:4712
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8113e4c0-ffffffff8113e60a: sched_cgroup_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_cgroup_fork(struct task_struct *p, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114afc0)
Location: kernel/sched/core.c:4790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8114afc0-ffffffff8114b10a: sched_cgroup_fork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_cgroup_fork(struct task_struct *p, struct kernel_clone_args *kargs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81156bc0)
Location: kernel/sched/core.c:4811
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81156bc0-ffffffff81156d0d: sched_cgroup_fork (STB_GLOBAL)
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
