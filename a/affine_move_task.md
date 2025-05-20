# Function: <code>affine_move_task</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfdb0)
Location: kernel/sched/core.c:2186
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810dfdb0-ffffffff810e0321: affine_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1b90)
Location: kernel/sched/core.c:2198
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810e1b90-ffffffff810e214b: affine_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f7df0)
Location: kernel/sched/core.c:2604
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff810f7df0-ffffffff810f8390: affine_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811140c0)
Location: kernel/sched/core.c:2703
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff811140c0-ffffffff81114652: affine_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113b400)
Location: kernel/sched/core.c:2765
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff8113b400-ffffffff8113b992: affine_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114e820)
Location: kernel/sched/core.c:2941
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff8114e820-ffffffff8114eea6: affine_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int affine_move_task(struct rq *rq, struct task_struct *p, struct rq_flags *rf, int dest_cpu, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115a680)
Location: kernel/sched/core.c:2969
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff8115a680-ffffffff8115ad45: affine_move_task (STB_LOCAL)
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
