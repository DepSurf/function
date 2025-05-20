# Function: <code>bind_evtchn_to_irq_chip</code>

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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734b70)
Location: drivers/xen/events/events_base.c:1165
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff81734b70-ffffffff81734cbb: bind_evtchn_to_irq_chip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip, struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718160)
Location: drivers/xen/events/events_base.c:1202
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff81718160-ffffffff817182c8: bind_evtchn_to_irq_chip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip, struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795b90)
Location: drivers/xen/events/events_base.c:1202
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff81795b90-ffffffff81795d34: bind_evtchn_to_irq_chip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip, struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818ce930)
Location: drivers/xen/events/events_base.c:1202
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff818ce930-ffffffff818ceada: bind_evtchn_to_irq_chip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip, struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1ff50)
Location: drivers/xen/events/events_base.c:1204
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff81a1ff50-ffffffff81a200fa: bind_evtchn_to_irq_chip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip, struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a692e0)
Location: drivers/xen/events/events_base.c:1197
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff81a692e0-ffffffff81a6948a: bind_evtchn_to_irq_chip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip *chip, struct xenbus_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abb340)
Location: drivers/xen/events/events_base.c:1192
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
```
**Symbols:**

```
ffffffff81abb340-ffffffff81abb454: bind_evtchn_to_irq_chip (STB_LOCAL)
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
