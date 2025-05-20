# Function: <code>evtchn_fifo_is_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff814ca8b0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff814ca8b0-ffffffff814ca8f6: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8151b410)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff8151b410-ffffffff8151b452: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff815478e0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff815478e0-ffffffff81547922: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8155b690)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff8155b690-ffffffff8155b6d1: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff815bf9c0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff815bf9c0-ffffffff815bfa01: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff815f80b0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff815f80b0-ffffffff815f80f1: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81613170)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff81613170-ffffffff816131b1: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff816470aa)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff81646f80-ffffffff81646fc2: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8166954a)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff81669420-ffffffff81669462: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81719960)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:consume_one_event
  - drivers/xen/events/events_fifo.c:consume_one_event
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff81719960-ffffffff817199a2: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81736bb0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:consume_one_event
  - drivers/xen/events/events_fifo.c:consume_one_event
```
**Symbols:**

```
ffffffff81736bb0-ffffffff81736bf2: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8171a5f0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff8171a5f0-ffffffff8171a632: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81798d60)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81798d60-ffffffff81798dc3: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff818d20a5)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff818d1890-ffffffff818d18fd: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a23660)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81a23660-ffffffff81a236cd: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a6cb10)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81a6cb10-ffffffff81a6cb80: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool evtchn_fifo_is_pending(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81abebd0)
Location: drivers/xen/events/events_fifo.c:206
Inline: False
Direct callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffffffff81abebd0-ffffffff81abec40: evtchn_fifo_is_pending (STB_LOCAL)
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
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffff800010833eac)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
**Symbols:**

```
ffff8000108336d0-ffff800010833730: evtchn_fifo_is_pending (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8162f3ba)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff8162f290-ffffffff8162f2d2: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8165d38a)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff8165d260-ffffffff8165d2a2: evtchn_fifo_is_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool evtchn_fifo_is_pending(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8167799a)
Location: drivers/xen/events/events_fifo.c:206
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
```
**Symbols:**

```
ffffffff81677870-ffffffff816778b2: evtchn_fifo_is_pending (STB_LOCAL)
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
<code>unsigned int port</code> ➡️ <code>evtchn_port_t port</code>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
