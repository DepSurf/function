# Function: <code>bind_interdomain_evtchn_to_irqhandler_lateeoi</code>

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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(unsigned int remote_domain, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734d70)
Location: drivers/xen/events/events_base.c:1449
Inline: False
```
**Symbols:**

```
ffffffff81734d70-ffffffff81734e38: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718380)
Location: drivers/xen/events/events_base.c:1486
Inline: False
```
**Symbols:**

```
ffffffff81718380-ffffffff8171844f: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795e10)
Location: drivers/xen/events/events_base.c:1492
Inline: False
```
**Symbols:**

```
ffffffff81795e10-ffffffff81795edf: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cebf0)
Location: drivers/xen/events/events_base.c:1492
Inline: False
```
**Symbols:**

```
ffffffff818cebf0-ffffffff818cece3: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20250)
Location: drivers/xen/events/events_base.c:1494
Inline: False
```
**Symbols:**

```
ffffffff81a20250-ffffffff81a20343: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a695e0)
Location: drivers/xen/events/events_base.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81a695e0-ffffffff81a696d3: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abb4f0)
Location: drivers/xen/events/events_base.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81abb4f0-ffffffff81abb62b: bind_interdomain_evtchn_to_irqhandler_lateeoi (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xenbus_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int remote_domain</code>
</li>
</ul>
</details>
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
