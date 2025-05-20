# Function: <code>set_synth_event_print_fmt</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a42d9)
Location: kernel/trace/trace_events_hist.c:723
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811af9c5)
Location: kernel/trace/trace_events_hist.c:786
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811c0b1f)
Location: kernel/trace/trace_events_hist.c:940
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811cc3cf)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_synth_event_print_fmt(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de520)
Location: kernel/trace/trace_events_synth.c:435
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff811de520-ffffffff811de57c: set_synth_event_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_synth_event_print_fmt(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811db900)
Location: kernel/trace/trace_events_synth.c:555
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff811db900-ffffffff811db95c: set_synth_event_print_fmt (STB_LOCAL)
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
In kernel/trace/trace_events_synth.c (ffffffff811ddc1c)
Location: kernel/trace/trace_events_synth.c:556
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
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
In kernel/trace/trace_events_synth.c (ffffffff8120d44c)
Location: kernel/trace/trace_events_synth.c:556
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
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
In kernel/trace/trace_events_synth.c (ffffffff812497d3)
Location: kernel/trace/trace_events_synth.c:564
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
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
In kernel/trace/trace_events_synth.c (ffffffff812979bb)
Location: kernel/trace/trace_events_synth.c:575
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
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
In kernel/trace/trace_events_synth.c (ffffffff812b4b2b)
Location: kernel/trace/trace_events_synth.c:644
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
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
In kernel/trace/trace_events_synth.c (ffffffff812d1239)
Location: kernel/trace/trace_events_synth.c:645
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
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
In kernel/trace/trace_events_hist.c (ffff80001024c0ac)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e73a8)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c49ef)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b77cf)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c27bf)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811d085f)
Location: kernel/trace/trace_events_hist.c:1010
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
