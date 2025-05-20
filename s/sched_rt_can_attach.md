# Function: <code>sched_rt_can_attach</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f04a0)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
ffffffff810f04a0-ffffffff810f04c5: sched_rt_can_attach (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010151b50)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
ffff800010151b50-ffff800010151ba0: sched_rt_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039ee08)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
c039ee08-c039ee48: sched_rt_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a5470)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
c0000000001a5470-c0000000001a54a0: sched_rt_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9d36)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
ffffffe0000f9d36-ffffffe0000f9d7e: sched_rt_can_attach (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d9860)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
ffffffff810d9860-ffffffff810d9885: sched_rt_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_rt_can_attach(struct task_group *tg, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e69d0)
Location: kernel/sched/rt.c:2602
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
```
**Symbols:**

```
ffffffff810e69d0-ffffffff810e69f5: sched_rt_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
