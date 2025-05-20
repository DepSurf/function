# Function: <code>channels_on_cpu_inc</code>

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
void channels_on_cpu_inc(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817324c0)
Location: drivers/xen/events/events_base.c:285
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
**Symbols:**

```
ffffffff817324c0-ffffffff81732505: channels_on_cpu_inc (STB_LOCAL)
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
In drivers/xen/events/events_base.c (ffffffff81717afe)
Location: drivers/xen/events/events_base.c:295
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
In drivers/xen/events/events_base.c (ffffffff8179530c)
Location: drivers/xen/events/events_base.c:295
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
In drivers/xen/events/events_base.c (ffffffff818ce032)
Location: drivers/xen/events/events_base.c:295
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
In drivers/xen/events/events_base.c (ffffffff81a1f695)
Location: drivers/xen/events/events_base.c:296
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
In drivers/xen/events/events_base.c (ffffffff81a68895)
Location: drivers/xen/events/events_base.c:297
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
In drivers/xen/events/events_base.c (ffffffff81ab9bb6)
Location: drivers/xen/events/events_base.c:294
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
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
</ul>
