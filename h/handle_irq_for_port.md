# Function: <code>handle_irq_for_port</code>

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
In drivers/xen/events/events_fifo.c (ffffffff814caa6a)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff8151b5cc)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff81547a9c)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff8155b84c)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff815bfb6f)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff815f8254)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff81613323)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff81647105)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff816695a5)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff81719aaa)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:consume_one_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735b80)
Location: drivers/xen/events/events_base.c:1619
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:consume_one_event
```
**Symbols:**

```
ffffffff81735b80-ffffffff81735c68: handle_irq_for_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81719360)
Location: drivers/xen/events/events_base.c:1656
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81719360-ffffffff81719477: handle_irq_for_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1662
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81cf5907-ffffffff81cf5938: handle_irq_for_port.cold (STB_LOCAL)
ffffffff817971d0-ffffffff81797328: handle_irq_for_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1662
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81ebda4f-ffffffff81ebda81: handle_irq_for_port.cold (STB_LOCAL)
ffffffff818d0190-ffffffff818d0305: handle_irq_for_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1664
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff82094765-ffffffff82094797: handle_irq_for_port.cold (STB_LOCAL)
ffffffff81a21930-ffffffff81a21aa5: handle_irq_for_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1658
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8211553b-ffffffff8211556d: handle_irq_for_port.cold (STB_LOCAL)
ffffffff81a6acc0-ffffffff81a6ae35: handle_irq_for_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void handle_irq_for_port(evtchn_port_t port, struct evtchn_loop_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1648
Inline: False
Direct callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff821f31c9-ffffffff821f31f3: handle_irq_for_port.cold (STB_LOCAL)
ffffffff81abcf30-ffffffff81abd042: handle_irq_for_port (STB_GLOBAL)
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
In drivers/xen/events/events_fifo.c (ffff800010833ed8)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8162f415)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8165d3e5)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
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
In drivers/xen/events/events_fifo.c (ffffffff816779f5)
Location: drivers/xen/events/events_fifo.c:273
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
</details>
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
