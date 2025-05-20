# Function: <code>track_data_free</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf257)
Location: kernel/trace/trace_events_hist.c:535
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffffffff811ba850-ffffffff811ba88d: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811caaa7)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffffffff811c5f20-ffffffff811c5f5d: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e7e2d)
Location: kernel/trace/trace_events_hist.c:480
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_alloc
  - kernel/trace/trace_events_hist.c:track_data_alloc
  - kernel/trace/trace_events_hist.c:track_data_alloc
  - kernel/trace/trace_events_hist.c:track_data_alloc
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
In kernel/trace/trace_events_hist.c (ffffffff811e581d)
Location: kernel/trace/trace_events_hist.c:483
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_alloc
  - kernel/trace/trace_events_hist.c:track_data_alloc
  - kernel/trace/trace_events_hist.c:track_data_alloc
  - kernel/trace/trace_events_hist.c:track_data_alloc
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
In kernel/trace/trace_events_hist.c (ffffffff811e6f22)
Location: kernel/trace/trace_events_hist.c:496
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
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
In kernel/trace/trace_events_hist.c (ffffffff81216443)
Location: kernel/trace/trace_events_hist.c:520
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
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
In kernel/trace/trace_events_hist.c (ffffffff81254889)
Location: kernel/trace/trace_events_hist.c:675
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff8124d790-ffffffff8124d7d0: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812a3cf9)
Location: kernel/trace/trace_events_hist.c:708
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff8129b910-ffffffff8129b950: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812c1bad)
Location: kernel/trace/trace_events_hist.c:705
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff812b9080-ffffffff812b90c0: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812ddfea)
Location: kernel/trace/trace_events_hist.c:705
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff812d56d0-ffffffff812d5710: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024b640)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffff800010246308-ffff80001024634c: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (c0000000002e4cb8)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
c0000000002d9e40-c0000000002d9eb4: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c30c7)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffffffff811be540-ffffffff811be57d: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b5ea7)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffffffff811b1320-ffffffff811b135d: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c0e97)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffffffff811bc310-ffffffff811bc34d: track_data_free.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811cef37)
Location: kernel/trace/trace_events_hist.c:542
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:track_data_destroy
```
**Symbols:**

```
ffffffff811ca3b0-ffffffff811ca3ed: track_data_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
