# Function: <code>pick_task_rt</code>

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
struct task_struct *pick_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff811136a5)
Location: kernel/sched/rt.c:1644
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81112110-ffffffff81112172: pick_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811383e5)
Location: kernel/sched/rt.c:1803
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff8112ee00-ffffffff8112ee71: pick_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1802
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81158b70-ffffffff81158c28: pick_task_rt (STB_LOCAL)
ffffffff820572aa-ffffffff820572be: pick_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1802
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81168e50-ffffffff81168f0b: pick_task_rt (STB_LOCAL)
ffffffff820d5ad2-ffffffff820d5aee: pick_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct task_struct *pick_task_rt(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1747
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff811761a0-ffffffff8117625b: pick_task_rt (STB_LOCAL)
ffffffff821b0b4b-ffffffff821b0b67: pick_task_rt.cold (STB_LOCAL)
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
