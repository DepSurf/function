# Function: <code>__raise_softirq_irqoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810851da)
Location: kernel/softirq.c:427
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:raise_softirq
Direct callers:
  - block/blk-iopoll.c:blk_iopoll_softirq
  - block/blk-iopoll.c:blk_iopoll_sched
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:net_rx_action
```
**Symbols:**

```
ffffffff81085e10-ffffffff81085e7b: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810887ff)
Location: kernel/softirq.c:427
Inline: True
Inline callers:
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff81088c40-ffffffff81088ca4: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d75d)
Location: kernel/softirq.c:441
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff8108db90-ffffffff8108dbf4: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108a78c)
Location: kernel/softirq.c:441
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff8108abc0-ffffffff8108ac24: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109133c)
Location: kernel/softirq.c:441
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810918a0-ffffffff81091907: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094dcc)
Location: kernel/softirq.c:448
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff81095380-ffffffff810953e8: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d2ac)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff8109d700-ffffffff8109d768: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a188c)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810a1cc0-ffffffff810a1d28: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a7e4c)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810a8280-ffffffff810a82e8: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af22c)
Location: kernel/softirq.c:476
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810afb70-ffffffff810afbd8: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aa9fa)
Location: kernel/softirq.c:479
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810ab2d0-ffffffff810ab329: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810abd4a)
Location: kernel/softirq.c:696
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
Direct callers:
  - block/blk-mq.c:__blk_mq_complete_request_remote
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810ac4d0-ffffffff810ac529: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:695
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - block/blk-mq.c:__blk_mq_complete_request_remote
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff81ca42a5-ffffffff81ca42be: __raise_softirq_irqoff.cold (STB_LOCAL)
ffffffff810bd9f0-ffffffff810bda50: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:709
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - block/blk-mq.c:__blk_mq_complete_request_remote
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:trigger_rx_softirq
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff81e53b37-ffffffff81e53b4f: __raise_softirq_irqoff.cold (STB_LOCAL)
ffffffff810d49f0-ffffffff810d4a6e: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:709
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - block/blk-mq.c:__blk_mq_complete_request_remote
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:trigger_rx_softirq
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff82055d22-ffffffff82055d3a: __raise_softirq_irqoff.cold (STB_LOCAL)
ffffffff810f3980-ffffffff810f39fe: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:691
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - block/blk-mq.c:__blk_mq_complete_request_remote
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:trigger_rx_softirq
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff820d4312-ffffffff820d432a: __raise_softirq_irqoff.cold (STB_LOCAL)
ffffffff810ffcd0-ffffffff810ffd4e: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:691
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - block/blk-mq.c:__blk_mq_complete_request_remote
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:trigger_rx_softirq
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff821af20b-ffffffff821af223: __raise_softirq_irqoff.cold (STB_LOCAL)
ffffffff811093f0-ffffffff8110946e: __raise_softirq_irqoff (STB_GLOBAL)
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
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff228)
Location: kernel/softirq.c:449
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:raise_softirq
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffff8000100ff228-ffff8000100ff2e4: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035bf4c)
Location: kernel/softirq.c:449
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
c035bf4c-c035c000: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000146570)
Location: kernel/softirq.c:449
Inline: False
Direct callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
c000000000146570-c00000000014666c: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c713a)
Location: kernel/softirq.c:449
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffe0000c713a-ffffffe0000c71de: __raise_softirq_irqoff (STB_GLOBAL)
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
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a176c)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810a1ba0-ffffffff810a1c08: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81090146)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff81090580-ffffffff810905e8: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a171c)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810a1b50-ffffffff810a1bb8: __raise_softirq_irqoff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __raise_softirq_irqoff(unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a96dc)
Location: kernel/softirq.c:449
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
Direct callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
**Symbols:**

```
ffffffff810a9b60-ffffffff810a9bdd: __raise_softirq_irqoff (STB_GLOBAL)
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
