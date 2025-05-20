# Function: <code>bind_evtchn_to_irqhandler_lateeoi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734ce0)
Location: drivers/xen/events/events_base.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81734ce0-ffffffff81734d6b: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817182f0)
Location: drivers/xen/events/events_base.c:1455
Inline: False
```
**Symbols:**

```
ffffffff817182f0-ffffffff8171837d: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795ee0)
Location: drivers/xen/events/events_base.c:1461
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81795ee0-ffffffff81795f6d: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818ceb40)
Location: drivers/xen/events/events_base.c:1461
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff818ceb40-ffffffff818cebee: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20360)
Location: drivers/xen/events/events_base.c:1463
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81a20360-ffffffff81a2040e: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a696f0)
Location: drivers/xen/events/events_base.c:1456
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81a696f0-ffffffff81a6979e: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler_lateeoi(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abbbb0)
Location: drivers/xen/events/events_base.c:1456
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81abbbb0-ffffffff81abbc9f: bind_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
