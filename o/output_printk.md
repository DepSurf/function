# Function: <code>output_printk</code>

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
In kernel/trace/trace_events.c (ffffffff8115ff2c)
Location: kernel/trace/trace_events.c:263
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
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
In kernel/trace/trace_events.c (ffffffff8116a50d)
Location: kernel/trace/trace_events.c:288
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8116328c)
Location: kernel/trace/trace.c:2125
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81166787)
Location: kernel/trace/trace.c:2302
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81173717)
Location: kernel/trace/trace.c:2305
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff811826b4)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81190014)
Location: kernel/trace/trace.c:2318
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8119d7b3)
Location: kernel/trace/trace.c:2502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff811a9183)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void output_printk(struct trace_event_buffer *fbuffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9bb0)
Location: kernel/trace/trace.c:2632
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff811b9bb0-ffffffff811b9cf5: output_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void output_printk(struct trace_event_buffer *fbuffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b7710)
Location: kernel/trace/trace.c:2776
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff811b7710-ffffffff811b7855: output_printk (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811bf855)
Location: kernel/trace/trace.c:2786
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff811ea196)
Location: kernel/trace/trace.c:2846
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81222037)
Location: kernel/trace/trace.c:2844
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8126cff7)
Location: kernel/trace/trace.c:2868
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81284187)
Location: kernel/trace/trace.c:2939
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8129f287)
Location: kernel/trace/trace.c:2933
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffff800010225e40)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04633f8)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (c0000000002ab780)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffe000180d20)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
```
</details>
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
In kernel/trace/trace.c (ffffffff811a17a3)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff81194773)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff8119f573)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
In kernel/trace/trace.c (ffffffff811ad2f3)
Location: kernel/trace/trace.c:2528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
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
