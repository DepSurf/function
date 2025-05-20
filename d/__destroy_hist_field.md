# Function: <code>__destroy_hist_field</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __destroy_hist_field(struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa590)
Location: kernel/trace/trace_events_hist.c:2227
Inline: False
```
**Symbols:**

```
ffffffff811aa590-ffffffff811aa5be: __destroy_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __destroy_hist_field(struct hist_field *hist_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b84c0)
Location: kernel/trace/trace_events_hist.c:2381
Inline: False
```
**Symbols:**

```
ffffffff811b84c0-ffffffff811b84f2: __destroy_hist_field (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c5a70)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
ffffffff811c5a70-ffffffff811c5aa2: __destroy_hist_field.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e4d18)
Location: kernel/trace/trace_events_hist.c:1552
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811e2748)
Location: kernel/trace/trace_events_hist.c:1562
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811e37c7)
Location: kernel/trace/trace_events_hist.c:1586
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff81213998)
Location: kernel/trace/trace_events_hist.c:1622
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff8124f559)
Location: kernel/trace/trace_events_hist.c:1866
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff8129e6d9)
Location: kernel/trace/trace_events_hist.c:1902
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff812bc359)
Location: kernel/trace/trace_events_hist.c:1909
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff812d8849)
Location: kernel/trace/trace_events_hist.c:1902
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010245e18)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
ffff800010245e18-ffff800010245e54: __destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d9d10)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
c0000000002d9d10-c0000000002d9d70: __destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/trace/trace_events_hist.c (ffffffff811be090)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
ffffffff811be090-ffffffff811be0c2: __destroy_hist_field.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b0e70)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
ffffffff811b0e70-ffffffff811b0ea2: __destroy_hist_field.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811bbe60)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
ffffffff811bbe60-ffffffff811bbe92: __destroy_hist_field.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c9f00)
Location: kernel/trace/trace_events_hist.c:2460
Inline: True
```
**Symbols:**

```
ffffffff811c9f00-ffffffff811c9f32: __destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
