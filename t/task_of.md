# Function: <code>task_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b2340)
Location: kernel/sched/fair.c:257
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
**Symbols:**

```
ffffffff810b2340-ffffffff810b237c: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c13e3)
Location: kernel/sched/fair.c:257
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
**Symbols:**

```
ffffffff810b4e50-ffffffff810b4e99: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c73e0)
Location: kernel/sched/fair.c:272
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bb310-ffffffff810bb360: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0fb4)
Location: kernel/sched/fair.c:274
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
```
**Symbols:**

```
ffffffff810b5c50-ffffffff810b5c8c: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c8860)
Location: kernel/sched/fair.c:276
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bcf30-ffffffff810bcf7a: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1082)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810c4b20-ffffffff810c4b66: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da763)
Location: kernel/sched/fair.c:258
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810cdd10-ffffffff810cdd56: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1a53)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d60c0-ffffffff810d6106: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec5a7)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e0740-ffffffff810e0786: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f61a2)
Location: kernel/sched/fair.c:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e8c30-ffffffff810e8c76: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f42f8)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e69c0-ffffffff810e6a0a: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5c58)
Location: kernel/sched/fair.c:271
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e8af0-ffffffff810e8b3a: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110f986)
Location: kernel/sched/sched.h:1374
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff811006e0-ffffffff81100741: task_of (STB_LOCAL)
ffffffff81ca6257-ffffffff81ca6274: task_of.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1360
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8112b97d)
Location: kernel/sched/sched.h:1360
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1360
Inline: True
```
**Symbols:**

```
ffffffff8111b7f0-ffffffff8111b853: task_of (STB_LOCAL)
ffffffff81e55b35-ffffffff81e55b4a: task_of.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1406
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81155355)
Location: kernel/sched/sched.h:1406
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1406
Inline: True
```
**Symbols:**

```
ffffffff81143310-ffffffff81143373: task_of (STB_LOCAL)
ffffffff82056d9a-ffffffff82056daf: task_of.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1414
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81165505)
Location: kernel/sched/sched.h:1414
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1414
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1433
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8117224e)
Location: kernel/sched/sched.h:1433
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1433
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014ca94)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffff800010140600-ffff800010140650: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039a788)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
c0390648-c03906a8: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019f628)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
c00000000018fb20-c00000000018fb94: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f5f8a)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffe0000ee6fa-ffffffe0000ee742: task_of (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6707)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810da8f0-ffffffff810da936: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d58a7)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810c9900-ffffffff810c9946: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2ad7)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d6c70-ffffffff810d6cb6: task_of (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *task_of(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee6a7)
Location: kernel/sched/fair.c:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
Direct callers:
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e2580-ffffffff810e25c6: task_of (STB_LOCAL)
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
