# Function: <code>check_preempt_curr_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/stop_task.c:21
Inline: False
```
**Symbols:**

```
ffffffff810c6b60-ffffffff810c6b6b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/stop_task.c:21
Inline: False
```
**Symbols:**

```
ffffffff810ccb40-ffffffff810ccb4b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810cd790)
Location: kernel/sched/stop_task.c:21
Inline: True
```
**Symbols:**

```
ffffffff810cd790-ffffffff810cd79b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810d4fe0)
Location: kernel/sched/stop_task.c:22
Inline: True
```
**Symbols:**

```
ffffffff810d4fe0-ffffffff810d4feb: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810dcfb0)
Location: kernel/sched/stop_task.c:21
Inline: True
```
**Symbols:**

```
ffffffff810dcfb0-ffffffff810dcfbb: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810e6c10)
Location: kernel/sched/stop_task.c:21
Inline: True
```
**Symbols:**

```
ffffffff810e6c10-ffffffff810e6c1b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810ed8a0)
Location: kernel/sched/stop_task.c:21
Inline: False
```
**Symbols:**

```
ffffffff810ed8a0-ffffffff810ed8ab: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810f9470)
Location: kernel/sched/stop_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810f9470-ffffffff810f947b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81103590)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
ffffffff81103590-ffffffff8110359b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81101c80)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
ffffffff81101c80-ffffffff81101c8b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81103ff0)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
ffffffff81103ff0-ffffffff81103ffb: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff811210b0)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
ffffffff811210b0-ffffffff811210bb: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113bf60)
Location: kernel/sched/stop_task.c:26
Inline: True
```
**Symbols:**

```
ffffffff8113bf60-ffffffff8113bf6f: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166ab0)
Location: kernel/sched/stop_task.c:26
Inline: True
```
**Symbols:**

```
ffffffff81166ab0-ffffffff81166abf: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176f20)
Location: kernel/sched/stop_task.c:26
Inline: True
```
**Symbols:**

```
ffffffff81176f20-ffffffff81176f2f: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffff80001015dd70)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
ffff80001015dd70-ffff80001015dd88: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (c03a9bd0)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
c03a9bd0-c03a9be8: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (c0000000001b29a0)
Location: kernel/sched/stop_task.c:27
Inline: False
```
**Symbols:**

```
c0000000001b29a0-c0000000001b29ac: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffe0001022ae)
Location: kernel/sched/stop_task.c:27
Inline: True
```
**Symbols:**

```
ffffffe0001022ae-ffffffe0001022c8: check_preempt_curr_stop (STB_LOCAL)
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
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810f2870)
Location: kernel/sched/stop_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810f2870-ffffffff810f287b: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810e28e0)
Location: kernel/sched/stop_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810e28e0-ffffffff810e28eb: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810ef9a0)
Location: kernel/sched/stop_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810ef9a0-ffffffff810ef9ab: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void check_preempt_curr_stop(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810fa9f0)
Location: kernel/sched/stop_task.c:27
Inline: False
```
**Symbols:**

```
ffffffff810fa9f0-ffffffff810fa9fb: check_preempt_curr_stop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
