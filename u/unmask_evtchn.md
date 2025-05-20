# Function: <code>unmask_evtchn</code>

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
In drivers/xen/events/events_base.c (ffffffff814c81ee)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81518c8e)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff8154517e)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff8155909a)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff815bd486)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff815f5b41)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff81610c01)
Location: drivers/xen/events/events_internal.h:132
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff81644862)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff81666e12)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff81716c22)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff817339c6)
Location: drivers/xen/events/events_internal.h:91
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81717476)
Location: drivers/xen/events/events_internal.h:91
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81794611)
Location: drivers/xen/events/events_internal.h:91
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff818cd24b)
Location: drivers/xen/events/events_internal.h:91
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81a1e80b)
Location: drivers/xen/events/events_internal.h:91
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81a67a0b)
Location: drivers/xen/events/events_internal.h:91
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81abb0db)
Location: drivers/xen/events/events_internal.h:90
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffff800010830adc)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff8162cb42)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff8165ac52)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
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
In drivers/xen/events/events_base.c (ffffffff81675242)
Location: drivers/xen/events/events_internal.h:130
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:enable_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
</details>
</li>
</ul>

## Differences
