# Function: <code>__dequeue_task_dl</code>

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
In kernel/sched/deadline.c (ffffffff810c22c5)
Location: kernel/sched/deadline.c:996
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dequeue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c5e77)
Location: kernel/sched/deadline.c:976
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810cbe37)
Location: kernel/sched/deadline.c:965
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810c838e)
Location: kernel/sched/deadline.c:1455
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810cfabe)
Location: kernel/sched/deadline.c:1448
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810d7c90)
Location: kernel/sched/deadline.c:1507
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810e1c40)
Location: kernel/sched/deadline.c:1506
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810e8720)
Location: kernel/sched/deadline.c:1505
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810f38e0)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fcff0)
Location: kernel/sched/deadline.c:1540
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb500)
Location: kernel/sched/deadline.c:1628
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fd78c)
Location: kernel/sched/deadline.c:1607
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81119b9c)
Location: kernel/sched/deadline.c:1607
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dequeue_task_dl(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1753
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:update_curr_dl
```
**Symbols:**

```
ffffffff81135f50-ffffffff8113609d: __dequeue_task_dl (STB_LOCAL)
ffffffff81e566e3-ffffffff81e5670d: __dequeue_task_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __dequeue_task_dl(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1754
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:update_curr_dl
```
**Symbols:**

```
ffffffff811603b0-ffffffff8116066c: __dequeue_task_dl (STB_LOCAL)
ffffffff82057904-ffffffff8205792d: __dequeue_task_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __dequeue_task_dl(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1745
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:update_curr_dl
```
**Symbols:**

```
ffffffff81170ad0-ffffffff81170d90: __dequeue_task_dl (STB_LOCAL)
ffffffff820d612a-ffffffff820d6153: __dequeue_task_dl.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010155b84)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (c03a35e4)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (c0000000001a9e5c)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffe0000fd61e)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810ecce0)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810dcd80)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810e9e10)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/deadline.c (ffffffff810f4dd0)
Location: kernel/sched/deadline.c:1538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
