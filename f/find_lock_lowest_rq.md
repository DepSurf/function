# Function: <code>find_lock_lowest_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c0a12)
Location: kernel/sched/rt.c:1634
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c44a2)
Location: kernel/sched/rt.c:1696
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca502)
Location: kernel/sched/rt.c:1695
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4012)
Location: kernel/sched/rt.c:1707
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cba49)
Location: kernel/sched/rt.c:1697
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d41bc)
Location: kernel/sched/rt.c:1708
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dd6cc)
Location: kernel/sched/rt.c:1721
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e46b1)
Location: kernel/sched/rt.c:1721
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9130)
Location: kernel/sched/rt.c:1781
Inline: False
Direct callers:
  - kernel/sched/rt.c:push_rt_task
```
**Symbols:**

```
ffffffff810f9130-ffffffff810f925c: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7320)
Location: kernel/sched/rt.c:1783
Inline: False
```
**Symbols:**

```
ffffffff810f7320-ffffffff810f7449: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8970)
Location: kernel/sched/rt.c:1783
Inline: False
```
**Symbols:**

```
ffffffff810f8970-ffffffff810f8a99: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81112630)
Location: kernel/sched/rt.c:1808
Inline: False
```
**Symbols:**

```
ffffffff81112630-ffffffff81112870: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f520)
Location: kernel/sched/rt.c:1973
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8112f520-ffffffff8112f6f5: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811593b0)
Location: kernel/sched/rt.c:1972
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff811593b0-ffffffff81159585: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811695b0)
Location: kernel/sched/rt.c:1972
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff811695b0-ffffffff81169799: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rq *find_lock_lowest_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176770)
Location: kernel/sched/rt.c:1917
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff81176770-ffffffff81176959: find_lock_lowest_rq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010150b08)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039bee0)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a23b8)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f91a4)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1711
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
