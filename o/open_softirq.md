# Function: <code>open_softirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085e80)
Location: kernel/softirq.c:433
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-iopoll.c:blk_iopoll_setup
```
**Symbols:**

```
ffffffff81085e80-ffffffff81085e96: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81fa47cf)
Location: kernel/softirq.c:433
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
```
**Symbols:**

```
ffffffff81088cb0-ffffffff81088cc6: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81fe0194)
Location: kernel/softirq.c:447
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
```
**Symbols:**

```
ffffffff8108dc00-ffffffff8108dc16: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff820c0fac)
Location: kernel/softirq.c:447
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
```
**Symbols:**

```
ffffffff8108ac30-ffffffff8108ac46: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff826c91a3)
Location: kernel/softirq.c:447
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
```
**Symbols:**

```
ffffffff81091910-ffffffff81091926: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff826f3346)
Location: kernel/softirq.c:454
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810953f0-ffffffff81095406: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828aa12e)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff8109d770-ffffffff8109d786: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828c2923)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810a1d30-ffffffff810a1d46: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828caf2c)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810a82f0-ffffffff810a8306: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff82ced258)
Location: kernel/softirq.c:482
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810afbe0-ffffffff810afbf6: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff82fd98b2)
Location: kernel/softirq.c:486
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810ab330-ffffffff810ab346: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff831e420c)
Location: kernel/softirq.c:703
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810ac530-ffffffff810ac546: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff832c7e96)
Location: kernel/softirq.c:702
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810be090-ffffffff810be0c6: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8347aec4)
Location: kernel/softirq.c:716
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810d50a0-ffffffff810d50de: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff83ea5a80)
Location: kernel/softirq.c:716
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810f4100-ffffffff810f413e: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff836ca150)
Location: kernel/softirq.c:698
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff81100530-ffffffff8110056e: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff838fae00)
Location: kernel/softirq.c:698
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff81109c50-ffffffff81109c8e: open_softirq (STB_GLOBAL)
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
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000114424ec)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffff8000100ff7e8-ffff8000100ff81c: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c151c4f8)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
c035c400-c035c424: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c0000000013661b8)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
c000000000146be0-c000000000146c04: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe000004a1a)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffe0000c74b6-ffffffe0000c74ec: open_softirq (STB_GLOBAL)
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
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828b3d1f)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810a1c10-ffffffff810a1c26: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828abea0)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810905f0-ffffffff81090606: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828c6c1e)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810a1bc0-ffffffff810a1bd6: open_softirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void open_softirq(int nr, void (*action)(struct softirq_action *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff828cbf69)
Location: kernel/softirq.c:455
Inline: True
Inline callers:
  - kernel/softirq.c:softirq_init
  - kernel/softirq.c:softirq_init
Direct callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - block/blk-softirq.c:blk_softirq_init
  - lib/irq_poll.c:irq_poll_setup
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
```
**Symbols:**

```
ffffffff810a9be0-ffffffff810a9bf6: open_softirq (STB_GLOBAL)
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
