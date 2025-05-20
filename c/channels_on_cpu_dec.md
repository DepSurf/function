# Function: <code>channels_on_cpu_dec</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735f39)
Location: drivers/xen/events/events_base.c:272
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff81732760-ffffffff817327a2: channels_on_cpu_dec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81719783)
Location: drivers/xen/events/events_base.c:282
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff81716100-ffffffff81716142: channels_on_cpu_dec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817976b3)
Location: drivers/xen/events/events_base.c:282
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff81793380-ffffffff817933dd: channels_on_cpu_dec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818d0713)
Location: drivers/xen/events/events_base.c:282
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff818cbe60-ffffffff818cbed9: channels_on_cpu_dec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a21f13)
Location: drivers/xen/events/events_base.c:283
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff81a1d2c0-ffffffff81a1d339: channels_on_cpu_dec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6b2a3)
Location: drivers/xen/events/events_base.c:284
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff81a664d0-ffffffff81a66549: channels_on_cpu_dec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abd373)
Location: drivers/xen/events/events_base.c:281
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_irq_info_cleanup
```
**Symbols:**

```
ffffffff81ab9000-ffffffff81ab9079: channels_on_cpu_dec.part.0 (STB_LOCAL)
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
