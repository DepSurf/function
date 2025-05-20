# Function: <code>update_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4a40)
Location: kernel/sched/fair.c:701
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810b4a40-ffffffff810b4b9f: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b75a0)
Location: kernel/sched/fair.c:783
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810b75a0-ffffffff810b7710: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf8b0)
Location: kernel/sched/fair.c:842
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810bf8b0-ffffffff810bfa20: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb260)
Location: kernel/sched/fair.c:839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810bb260-ffffffff810bb40d: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2e00)
Location: kernel/sched/fair.c:819
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810c2e00-ffffffff810c2fcd: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c92d0)
Location: kernel/sched/fair.c:806
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810c92d0-ffffffff810c94b1: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d36c0)
Location: kernel/sched/fair.c:802
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810d36c0-ffffffff810d3891: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dabb0)
Location: kernel/sched/fair.c:834
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810dabb0-ffffffff810dad91: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4ad0)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810e4ad0-ffffffff810e4cb0: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee0e0)
Location: kernel/sched/fair.c:844
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810ee0e0-ffffffff810ee2c0: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebf00)
Location: kernel/sched/fair.c:842
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810ebf00-ffffffff810ec0bc: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee8a0)
Location: kernel/sched/fair.c:839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810ee8a0-ffffffff810eea5b: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:825
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff81106ef0-ffffffff811070b1: update_curr (STB_LOCAL)
ffffffff81ca642d-ffffffff81ca6442: update_curr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:888
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff81124050-ffffffff81124256: update_curr (STB_LOCAL)
ffffffff81e55d05-ffffffff81e55d1a: update_curr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:897
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff8114bff0-ffffffff8114c1f3: update_curr (STB_LOCAL)
ffffffff82056f7b-ffffffff82056f90: update_curr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:897
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff8115a280-ffffffff8115a483: update_curr (STB_LOCAL)
ffffffff820d569a-ffffffff820d56af: update_curr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81164a10)
Location: kernel/sched/fair.c:1156
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff81164a10-ffffffff81164c1a: update_curr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010144808)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffff800010144808-ffff800010144a10: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c03920f8)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
c03920f8-c03923b4: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000195a00)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
c000000000195a00-c000000000195ce8: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f141c)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffe0000f141c-ffffffe0000f15cc: update_curr (STB_LOCAL)
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
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dec80)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810dec80-ffffffff810dee60: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cdc90)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810cdc90-ffffffff810cde70: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db000)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810db000-ffffffff810db1e0: update_curr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_curr(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6cc0)
Location: kernel/sched/fair.c:833
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr_fair
```
**Symbols:**

```
ffffffff810e6cc0-ffffffff810e6ec3: update_curr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
