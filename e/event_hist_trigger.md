# Function: <code>event_hist_trigger</code>

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
void event_hist_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81171b50)
Location: kernel/trace/trace_events_hist.c:879
Inline: False
```
**Symbols:**

```
ffffffff81171b50-ffffffff81171db1: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117d2c0)
Location: kernel/trace/trace_events_hist.c:879
Inline: False
```
**Symbols:**

```
ffffffff8117d2c0-ffffffff8117d521: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117fea0)
Location: kernel/trace/trace_events_hist.c:880
Inline: False
```
**Symbols:**

```
ffffffff8117fea0-ffffffff811800f0: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118d730)
Location: kernel/trace/trace_events_hist.c:923
Inline: False
```
**Symbols:**

```
ffffffff8118d730-ffffffff8118d987: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4632
Inline: False
```
**Symbols:**

```
ffffffff8119c610-ffffffff8119caaa: event_hist_trigger (STB_LOCAL)
ffffffff811a44da-ffffffff811a44e6: event_hist_trigger.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4718
Inline: False
```
**Symbols:**

```
ffffffff811aa9d0-ffffffff811aae86: event_hist_trigger (STB_LOCAL)
ffffffff811b260c-ffffffff811b2618: event_hist_trigger.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5235
Inline: False
```
**Symbols:**

```
ffffffff811b8a30-ffffffff811b8efe: event_hist_trigger (STB_LOCAL)
ffffffff811c0e28-ffffffff811c0e34: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
ffffffff811c4010-ffffffff811c44de: event_hist_trigger (STB_LOCAL)
ffffffff811cc693-ffffffff811cc69f: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4453
Inline: False
```
**Symbols:**

```
ffffffff811e0d40-ffffffff811e0f3e: event_hist_trigger (STB_LOCAL)
ffffffff811e8084-ffffffff811e8090: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4494
Inline: False
```
**Symbols:**

```
ffffffff811de700-ffffffff811de8fe: event_hist_trigger (STB_LOCAL)
ffffffff81be634c-ffffffff81be6358: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4562
Inline: False
```
**Symbols:**

```
ffffffff811dfab0-ffffffff811dfd99: event_hist_trigger (STB_LOCAL)
ffffffff81bd8007-ffffffff81bd8013: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4660
Inline: False
```
**Symbols:**

```
ffffffff8120ff10-ffffffff81210242: event_hist_trigger (STB_LOCAL)
ffffffff81cb6ebb-ffffffff81cb6ec7: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5040
Inline: False
```
**Symbols:**

```
ffffffff8124cb70-ffffffff8124cf02: event_hist_trigger (STB_LOCAL)
ffffffff81e67f58-ffffffff81e67f64: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129da40)
Location: kernel/trace/trace_events_hist.c:5171
Inline: False
```
**Symbols:**

```
ffffffff8129da40-ffffffff8129dd46: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bb470)
Location: kernel/trace/trace_events_hist.c:5260
Inline: False
```
**Symbols:**

```
ffffffff812bb470-ffffffff812bb7e2: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d7ac0)
Location: kernel/trace/trace_events_hist.c:5252
Inline: False
```
**Symbols:**

```
ffffffff812d7ac0-ffffffff812d7e32: event_hist_trigger (STB_LOCAL)
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
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010243c38)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
ffff800010243c38-ffff800010244054: event_hist_trigger (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d6c60)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
c0000000002d6c60-c0000000002d71e8: event_hist_trigger (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
ffffffff811bc630-ffffffff811bcafe: event_hist_trigger (STB_LOCAL)
ffffffff811c4cb3-ffffffff811c4cbf: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
ffffffff811af410-ffffffff811af8de: event_hist_trigger (STB_LOCAL)
ffffffff811b7a93-ffffffff811b7a9f: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
ffffffff811ba400-ffffffff811ba8ce: event_hist_trigger (STB_LOCAL)
ffffffff811c2a83-ffffffff811c2a8f: event_hist_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void event_hist_trigger(struct event_trigger_data *data, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:5345
Inline: False
```
**Symbols:**

```
ffffffff811c84a0-ffffffff811c896e: event_hist_trigger (STB_LOCAL)
ffffffff811d0b23-ffffffff811d0b2f: event_hist_trigger.cold (STB_LOCAL)
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
<code>struct ring_buffer_event *rbe</code>
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
<code>data, rec, rbe</code> ➡️ <code>data, buffer, rec, rbe</code>
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
