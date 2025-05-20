# Function: <code>evtchn_from_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c80e0)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff814c80e0-ffffffff814c812a: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518b80)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81518b80-ffffffff81518bca: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545070)
Location: drivers/xen/events/events_base.c:247
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81545070-ffffffff815450ba: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558fb0)
Location: drivers/xen/events/events_base.c:247
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81558fb0-ffffffff81558fec: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd390)
Location: drivers/xen/events/events_base.c:247
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff815bd390-ffffffff815bd3cc: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5a40)
Location: drivers/xen/events/events_base.c:247
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff815f5a40-ffffffff815f5a7c: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610b00)
Location: drivers/xen/events/events_base.c:247
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81610b00-ffffffff81610b3c: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81644780)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81644780-ffffffff816447bc: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81666d30)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81666d30-ffffffff81666d6c: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8171880c)
Location: drivers/xen/events/events_base.c:262
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
Direct callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81716b80-ffffffff81716bcf: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735e7c)
Location: drivers/xen/events/events_base.c:388
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81734f90-ffffffff81734fde: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817196ac)
Location: drivers/xen/events/events_base.c:405
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff817185a0-ffffffff817185ee: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817975bd)
Location: drivers/xen/events/events_base.c:405
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81796030-ffffffff81796099: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818d05fd)
Location: drivers/xen/events/events_base.c:405
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff818cee90-ffffffff818cef11: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a21ded)
Location: drivers/xen/events/events_base.c:406
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81a20530-ffffffff81a205b1: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6b17d)
Location: drivers/xen/events/events_base.c:407
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81a698c0-ffffffff81a69941: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abd24d)
Location: drivers/xen/events/events_base.c:410
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:irq_evtchn_from_virq
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
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108309a0)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffff8000108309a0-ffff800010830a10: evtchn_from_irq (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162ca60)
Location: drivers/xen/events/events_base.c:252
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff8162ca60-ffffffff8162ca9c: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165ab70)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff8165ab70-ffffffff8165abac: evtchn_from_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675160)
Location: drivers/xen/events/events_base.c:248
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81675160-ffffffff8167519c: evtchn_from_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>evtchn_port_t</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
