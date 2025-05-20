# Function: <code>bind_interdomain_evtchn_to_irq_lateeoi</code>

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
int bind_interdomain_evtchn_to_irq_lateeoi(unsigned int remote_domain, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734e40)
Location: drivers/xen/events/events_base.c:1278
Inline: False
```
**Symbols:**

```
ffffffff81734e40-ffffffff81734ea2: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irq_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817184e0)
Location: drivers/xen/events/events_base.c:1316
Inline: False
```
**Symbols:**

```
ffffffff817184e0-ffffffff81718549: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irq_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795f70)
Location: drivers/xen/events/events_base.c:1322
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81795f70-ffffffff81795fd9: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irq_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818ceda0)
Location: drivers/xen/events/events_base.c:1322
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff818ceda0-ffffffff818cee29: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irq_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20420)
Location: drivers/xen/events/events_base.c:1324
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81a20420-ffffffff81a204a9: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irq_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a697b0)
Location: drivers/xen/events/events_base.c:1317
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81a697b0-ffffffff81a69839: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_interdomain_evtchn_to_irq_lateeoi(struct xenbus_device *dev, evtchn_port_t remote_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abb640)
Location: drivers/xen/events/events_base.c:1313
Inline: False
```
**Symbols:**

```
ffffffff81abb640-ffffffff81abb6c9: bind_interdomain_evtchn_to_irq_lateeoi (STB_GLOBAL)
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
