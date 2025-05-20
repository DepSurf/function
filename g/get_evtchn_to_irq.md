# Function: <code>get_evtchn_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c7ec0)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff814c7ec0-ffffffff814c7f01: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518940)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81518940-ffffffff81518981: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81544e40)
Location: drivers/xen/events/events_base.c:145
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81544e40-ffffffff81544e81: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558cb0)
Location: drivers/xen/events/events_base.c:145
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81558cb0-ffffffff81558cf1: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd060)
Location: drivers/xen/events/events_base.c:145
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff815bd060-ffffffff815bd0a7: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5710)
Location: drivers/xen/events/events_base.c:145
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff815f5710-ffffffff815f5757: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816107e0)
Location: drivers/xen/events/events_base.c:145
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff816107e0-ffffffff81610827: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81644560)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81644560-ffffffff816445a7: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81666b10)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81666b10-ffffffff81666b57: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716680)
Location: drivers/xen/events/events_base.c:149
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:consume_one_event
```
**Symbols:**

```
ffffffff81716680-ffffffff817166ca: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733f60)
Location: drivers/xen/events/events_base.c:245
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffffffff81733f60-ffffffff81733fad: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717a20)
Location: drivers/xen/events/events_base.c:255
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffffffff81717a20-ffffffff81717a6d: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795220)
Location: drivers/xen/events/events_base.c:255
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffffffff81795220-ffffffff8179526d: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cdf30)
Location: drivers/xen/events/events_base.c:255
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffffffff818cdf30-ffffffff818cdf85: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1f570)
Location: drivers/xen/events/events_base.c:256
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffffffff81a1f570-ffffffff81a1f5c5: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a68770)
Location: drivers/xen/events/events_base.c:257
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
**Symbols:**

```
ffffffff81a68770-ffffffff81a687c5: get_evtchn_to_irq (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108306f8)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffff8000108306f8-ffff800010830758: get_evtchn_to_irq (STB_GLOBAL)
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
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162c840)
Location: drivers/xen/events/events_base.c:150
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8162c840-ffffffff8162c887: get_evtchn_to_irq (STB_GLOBAL)
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
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165a950)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8165a950-ffffffff8165a997: get_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81674f40)
Location: drivers/xen/events/events_base.c:146
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:irq_from_evtchn
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81674f40-ffffffff81674f87: get_evtchn_to_irq (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>unsigned int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
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
