# Function: <code>event_enable_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81165870)
Location: kernel/trace/trace_events_trigger.c:1061
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff81165870-ffffffff8116588f: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8116ffd0)
Location: kernel/trace/trace_events_trigger.c:1209
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff8116ffd0-ffffffff8116ffef: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117b740)
Location: kernel/trace/trace_events_trigger.c:1210
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff8117b740-ffffffff8117b75f: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117e420)
Location: kernel/trace/trace_events_trigger.c:1211
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff8117e420-ffffffff8117e43f: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8118bcb0)
Location: kernel/trace/trace_events_trigger.c:1220
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff8118bcb0-ffffffff8118bccf: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8119a6f0)
Location: kernel/trace/trace_events_trigger.c:1244
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff8119a6f0-ffffffff8119a70f: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811a88e0)
Location: kernel/trace/trace_events_trigger.c:1235
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811a88e0-ffffffff811a88ff: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b6820)
Location: kernel/trace/trace_events_trigger.c:1236
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811b6820-ffffffff811b6839: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c1e60)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811c1e60-ffffffff811c1e79: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811dc2ed)
Location: kernel/trace/trace_events_trigger.c:1257
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811dc250-ffffffff811dc269: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811d941d)
Location: kernel/trace/trace_events_trigger.c:1257
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811d9380-ffffffff811d9399: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811da98d)
Location: kernel/trace/trace_events_trigger.c:1266
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811da930-ffffffff811da94b: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81207f31)
Location: kernel/trace/trace_events_trigger.c:1324
Inline: True
```
**Symbols:**

```
ffffffff81207ea0-ffffffff81207ed7: event_enable_trigger (STB_LOCAL)
ffffffff81cb679f-ffffffff81cb67b3: event_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:1616
Inline: False
```
**Symbols:**

```
ffffffff81243340-ffffffff8124338b: event_enable_trigger (STB_LOCAL)
ffffffff81e676d1-ffffffff81e676e5: event_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:1630
Inline: False
```
**Symbols:**

```
ffffffff81290e50-ffffffff81290e9b: event_enable_trigger (STB_LOCAL)
ffffffff8205e135-ffffffff8205e149: event_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:1632
Inline: False
```
**Symbols:**

```
ffffffff812ae0c0-ffffffff812ae10b: event_enable_trigger (STB_LOCAL)
ffffffff820dcb78-ffffffff820dcb8c: event_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:1634
Inline: False
```
**Symbols:**

```
ffffffff812ca5e0-ffffffff812ca62b: event_enable_trigger (STB_LOCAL)
ffffffff821b897c-ffffffff821b8990: event_enable_trigger.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffff8000102421e0)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffff8000102421e0-ffff80001024223c: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c047d5fc)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
c047d5fc-c047d634: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c0000000002d29c8)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
c0000000002d2930-c0000000002d2974: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffe0001965ac)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffe000196548-ffffffe00019657c: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ba480)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811ba480-ffffffff811ba499: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ad260)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811ad260-ffffffff811ad279: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b8250)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811b8250-ffffffff811b8269: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void event_enable_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c62f0)
Location: kernel/trace/trace_events_trigger.c:1249
Inline: False
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_count_trigger
```
**Symbols:**

```
ffffffff811c62f0-ffffffff811c6309: event_enable_trigger (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *rec</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
