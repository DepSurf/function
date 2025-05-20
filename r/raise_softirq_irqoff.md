# Function: <code>raise_softirq_irqoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810854a7)
Location: kernel/softirq.c:401
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - block/blk-softirq.c:trigger_softirq
  - block/blk-softirq.c:__blk_complete_request
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:dev_cpu_callback
```
**Symbols:**

```
ffffffff81085cb0-ffffffff81085d43: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810887ff)
Location: kernel/softirq.c:401
Inline: True
Inline callers:
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
**Symbols:**

```
ffffffff81088b00-ffffffff81088b8c: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d75d)
Location: kernel/softirq.c:415
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
**Symbols:**

```
ffffffff8108da50-ffffffff8108dadd: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108a78c)
Location: kernel/softirq.c:415
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
**Symbols:**

```
ffffffff8108aa80-ffffffff8108ab0d: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109133c)
Location: kernel/softirq.c:415
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
```
**Symbols:**

```
ffffffff81091750-ffffffff810917e0: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094dcc)
Location: kernel/softirq.c:422
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81095220-ffffffff810952b1: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d2ac)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff8109d5a0-ffffffff8109d631: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a188c)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810a1b60-ffffffff810a1bf1: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a7e4c)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810a8120-ffffffff810a81b1: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af22c)
Location: kernel/softirq.c:450
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810afa20-ffffffff810afaae: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aa9fa)
Location: kernel/softirq.c:453
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-mq.c:blk_softirq_cpu_dead
  - block/blk-mq.c:blk_mq_trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810ab1b0-ffffffff810ab22f: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810abd4a)
Location: kernel/softirq.c:670
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810ac3a0-ffffffff810ac41f: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bde29)
Location: kernel/softirq.c:669
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810bda50-ffffffff810bda7d: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4e37)
Location: kernel/softirq.c:683
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_reschedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810d4a70-ffffffff810d4aad: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3e87)
Location: kernel/softirq.c:683
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - lib/irq_poll.c:irq_poll_sched
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_reschedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810f3a10-ffffffff810f3a4d: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811002b7)
Location: kernel/softirq.c:665
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - lib/irq_poll.c:irq_poll_sched
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_kfree_skb_irq_reason
  - net/core/dev.c:__netif_reschedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810ffd60-ffffffff810ffd9d: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811099d7)
Location: kernel/softirq.c:665
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - lib/irq_poll.c:irq_poll_sched
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_kfree_skb_irq_reason
  - net/core/dev.c:__netif_reschedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81109480-ffffffff811094bd: raise_softirq_irqoff (STB_GLOBAL)
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
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff72c)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffff8000100ff2e8-ffff8000100ff318: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035c324)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
c035c000-c035c03c: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000146ae0)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
c000000000146670-c0000000001466c0: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c7404)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_reschedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffe0000c71de-ffffffe0000c7218: raise_softirq_irqoff (STB_GLOBAL)
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
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a176c)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810a1a40-ffffffff810a1ad1: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81090146)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff81090440-ffffffff810904d1: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a171c)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810a19f0-ffffffff810a1a81: raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a96dc)
Location: kernel/softirq.c:423
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
Direct callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
**Symbols:**

```
ffffffff810a99e0-ffffffff810a9a8d: raise_softirq_irqoff (STB_GLOBAL)
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
