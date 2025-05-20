# Function: <code>task_vruntime_update</code>

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
void task_vruntime_update(struct rq *rq, struct task_struct *p, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81110ad0)
Location: kernel/sched/fair.c:11107
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81110ad0-ffffffff81110b27: task_vruntime_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_vruntime_update(struct rq *rq, struct task_struct *p, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112ccd0)
Location: kernel/sched/fair.c:11225
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff8112ccd0-ffffffff8112cd3a: task_vruntime_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_vruntime_update(struct rq *rq, struct task_struct *p, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811569f0)
Location: kernel/sched/fair.c:11752
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff811569f0-ffffffff81156a5a: task_vruntime_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_vruntime_update(struct rq *rq, struct task_struct *p, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81166a60)
Location: kernel/sched/fair.c:12057
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff81166a60-ffffffff81166ae6: task_vruntime_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_vruntime_update(struct rq *rq, struct task_struct *p, bool in_fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811737a0)
Location: kernel/sched/fair.c:12535
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
**Symbols:**

```
ffffffff811737a0-ffffffff81173832: task_vruntime_update (STB_GLOBAL)
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
