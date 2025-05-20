# Function: <code>pick_task_stop</code>

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
struct task_struct *pick_task_stop(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81121235)
Location: kernel/sched/stop_task.c:37
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff811210c0-ffffffff811210e1: pick_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_stop(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811443b5)
Location: kernel/sched/stop_task.c:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff8113bf70-ffffffff8113bf95: pick_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_stop(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811701b5)
Location: kernel/sched/stop_task.c:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff81166ad0-ffffffff81166af5: pick_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_stop(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117eda5)
Location: kernel/sched/stop_task.c:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff81176f40-ffffffff81176f65: pick_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pick_task_stop(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c425)
Location: kernel/sched/stop_task.c:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff81184f00-ffffffff81184f25: pick_task_stop (STB_LOCAL)
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
