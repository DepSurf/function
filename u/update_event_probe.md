# Function: <code>update_event_probe</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81177fa0)
Location: kernel/trace/trace_events.c:2503
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff81177fa0-ffffffff81177fb7: update_event_probe.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81185720)
Location: kernel/trace/trace_events.c:2516
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff81185720-ffffffff81185737: update_event_probe.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811947b0)
Location: kernel/trace/trace_events.c:2528
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811947b0-ffffffff811947c7: update_event_probe.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a29e0)
Location: kernel/trace/trace_events.c:2529
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811a29e0-ffffffff811a29f7: update_event_probe.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b08f0)
Location: kernel/trace/trace_events.c:2519
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811b08f0-ffffffff811b0901: update_event_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811bbd90)
Location: kernel/trace/trace_events.c:2518
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811bbd90-ffffffff811bbda1: update_event_probe.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811d53fe)
Location: kernel/trace/trace_events.c:2808
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
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
In kernel/trace/trace_events.c (ffffffff811d258e)
Location: kernel/trace/trace_events.c:2824
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
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
In kernel/trace/trace_events.c (ffffffff811d305e)
Location: kernel/trace/trace_events.c:3035
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_event_probe(struct event_probe_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811ffd02)
Location: kernel/trace/trace_events.c:3052
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811ffce0-ffffffff811ffd16: update_event_probe (STB_LOCAL)
ffffffff81cb637c-ffffffff81cb6391: update_event_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_event_probe(struct event_probe_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8123a3d2)
Location: kernel/trace/trace_events.c:3155
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff8123a3b0-ffffffff8123a3fa: update_event_probe (STB_LOCAL)
ffffffff81e672c3-ffffffff81e672d8: update_event_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_event_probe(struct event_probe_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81287552)
Location: kernel/trace/trace_events.c:3246
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff81287530-ffffffff8128757a: update_event_probe (STB_LOCAL)
ffffffff8205df68-ffffffff8205df7d: update_event_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_event_probe(struct event_probe_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a4242)
Location: kernel/trace/trace_events.c:3240
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff812a4220-ffffffff812a426a: update_event_probe (STB_LOCAL)
ffffffff820dca07-ffffffff820dca1c: update_event_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_event_probe(struct event_probe_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812bfba2)
Location: kernel/trace/trace_events.c:3432
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff812bfb80-ffffffff812bfbca: update_event_probe (STB_LOCAL)
ffffffff821b8809-ffffffff821b881e: update_event_probe.cold (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffff80001023b208)
Location: kernel/trace/trace_events.c:2518
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void update_event_probe(struct event_probe_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0475df4)
Location: kernel/trace/trace_events.c:2518
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
c0475df4-c0475e28: update_event_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c8764)
Location: kernel/trace/trace_events.c:2518
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe0001912e4)
Location: kernel/trace/trace_events.c:2518
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b43b0)
Location: kernel/trace/trace_events.c:2518
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811b43b0-ffffffff811b43c1: update_event_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a71b0)
Location: kernel/trace/trace_events.c:2518
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811a71b0-ffffffff811a71c1: update_event_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b2180)
Location: kernel/trace/trace_events.c:2518
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811b2180-ffffffff811b2191: update_event_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811c0220)
Location: kernel/trace/trace_events.c:2518
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
```
**Symbols:**

```
ffffffff811c0220-ffffffff811c0231: update_event_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
