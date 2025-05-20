# Function: <code>hist_enable_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81171840)
Location: kernel/trace/trace_events_hist.c:1627
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff81171840-ffffffff81171893: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117cfb0)
Location: kernel/trace/trace_events_hist.c:1627
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff8117cfb0-ffffffff8117d003: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117fc00)
Location: kernel/trace/trace_events_hist.c:1628
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff8117fc00-ffffffff8117fc53: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118d500)
Location: kernel/trace/trace_events_hist.c:1672
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff8118d500-ffffffff8118d553: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c140)
Location: kernel/trace/trace_events_hist.c:5666
Inline: True
```
**Symbols:**

```
ffffffff8119c140-ffffffff8119c18e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa430)
Location: kernel/trace/trace_events_hist.c:5747
Inline: True
```
**Symbols:**

```
ffffffff811aa430-ffffffff811aa47e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b8250)
Location: kernel/trace/trace_events_hist.c:6267
Inline: True
```
**Symbols:**

```
ffffffff811b8250-ffffffff811b829e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c38c0)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
ffffffff811c38c0-ffffffff811c390e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3a15)
Location: kernel/trace/trace_events_hist.c:5774
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff811e01f0-ffffffff811e023e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1335)
Location: kernel/trace/trace_events_hist.c:5815
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff811ddbb0-ffffffff811ddbfe: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2695)
Location: kernel/trace/trace_events_hist.c:5884
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff811df260-ffffffff811df2ae: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5990
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff8120fbd0-ffffffff8120fc3f: hist_enable_trigger (STB_LOCAL)
ffffffff81cb6e5a-ffffffff81cb6e6f: hist_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:6387
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff8124c7e0-ffffffff8124c85d: hist_enable_trigger (STB_LOCAL)
ffffffff81e67ef8-ffffffff81e67f0d: hist_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:6621
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff8129ab70-ffffffff8129abed: hist_enable_trigger (STB_LOCAL)
ffffffff8205e888-ffffffff8205e89d: hist_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:6729
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff812b82e0-ffffffff812b835d: hist_enable_trigger (STB_LOCAL)
ffffffff820dd3cc-ffffffff820dd3e1: hist_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:6725
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_enable_count_trigger
```
**Symbols:**

```
ffffffff812d4930-ffffffff812d49ad: hist_enable_trigger (STB_LOCAL)
ffffffff821b91d0-ffffffff821b91e5: hist_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102433e8)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
ffff8000102433e8-ffff800010243464: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d6010)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
c0000000002d6010-c0000000002d60b0: hist_enable_trigger (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bbee0)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
ffffffff811bbee0-ffffffff811bbf2e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aecc0)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
ffffffff811aecc0-ffffffff811aed0e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9cb0)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
ffffffff811b9cb0-ffffffff811b9cfe: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hist_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c7d50)
Location: kernel/trace/trace_events_hist.c:6393
Inline: True
```
**Symbols:**

```
ffffffff811c7d50-ffffffff811c7d9e: hist_enable_trigger (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ring_buffer_event *event</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_buffer *buffer</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, rec, event</code> ➡️ <code>data, buffer, rec, event</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
