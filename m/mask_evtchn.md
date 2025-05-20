# Function: <code>mask_evtchn</code>

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
In drivers/xen/events/events_base.c (ffffffff814c8347)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:disable_dynirq
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_init_IRQ
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
In drivers/xen/events/events_base.c (ffffffff81fd0f53)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff8200e8cb)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff820f037b)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff826f9b82)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff82723f1f)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff828dc0f8)
Location: drivers/xen/events/events_internal.h:127
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff828f69f1)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff828ffa48)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff82d16dcb)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff830049bb)
Location: drivers/xen/events/events_internal.h:86
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8320f473)
Location: drivers/xen/events/events_internal.h:86
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff832f841a)
Location: drivers/xen/events/events_internal.h:86
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff834b0c52)
Location: drivers/xen/events/events_internal.h:86
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff83eeaa75)
Location: drivers/xen/events/events_internal.h:86
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff83710465)
Location: drivers/xen/events/events_internal.h:86
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
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
In drivers/xen/events/events_base.c (ffffffff83943de5)
Location: drivers/xen/events/events_internal.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
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
In drivers/xen/events/events_base.c (ffff8000114919f4)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff828e7265)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff828fad6b)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
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
In drivers/xen/events/events_base.c (ffffffff82900a9c)
Location: drivers/xen/events/events_internal.h:125
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:disable_dynirq
```
</details>
</li>
</ul>

## Differences
