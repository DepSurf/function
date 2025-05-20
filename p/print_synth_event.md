# Function: <code>print_synth_event</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119f050)
Location: kernel/trace/trace_events_hist.c:584
Inline: False
```
**Symbols:**

```
ffffffff8119f050-ffffffff8119f229: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811acf10)
Location: kernel/trace/trace_events_hist.c:647
Inline: False
```
**Symbols:**

```
ffffffff811acf10-ffffffff811ad0e9: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bb1d0)
Location: kernel/trace/trace_events_hist.c:801
Inline: False
```
**Symbols:**

```
ffffffff811bb1d0-ffffffff811bb37d: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c6900)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffffffff811c6900-ffffffff811c6bc4: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de580)
Location: kernel/trace/trace_events_synth.c:262
Inline: False
```
**Symbols:**

```
ffffffff811de580-ffffffff811de851: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811db960)
Location: kernel/trace/trace_events_synth.c:311
Inline: False
```
**Symbols:**

```
ffffffff811db960-ffffffff811dbca1: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dcec0)
Location: kernel/trace/trace_events_synth.c:312
Inline: False
```
**Symbols:**

```
ffffffff811dcec0-ffffffff811dd1f9: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:312
Inline: False
```
**Symbols:**

```
ffffffff8120c6e0-ffffffff8120ca39: print_synth_event (STB_LOCAL)
ffffffff81cb6c7d-ffffffff81cb6cc4: print_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:320
Inline: False
```
**Symbols:**

```
ffffffff81248cb0-ffffffff81249073: print_synth_event (STB_LOCAL)
ffffffff81e67d30-ffffffff81e67d86: print_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:322
Inline: False
```
**Symbols:**

```
ffffffff81296e10-ffffffff812971d3: print_synth_event (STB_LOCAL)
ffffffff8205e636-ffffffff8205e68c: print_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:345
Inline: False
```
**Symbols:**

```
ffffffff812b3dc0-ffffffff812b4252: print_synth_event (STB_LOCAL)
ffffffff820dd0ec-ffffffff820dd156: print_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:345
Inline: False
```
**Symbols:**

```
ffffffff812d0370-ffffffff812d0802: print_synth_event (STB_LOCAL)
ffffffff821b8ef0-ffffffff821b8f5a: print_synth_event.cold (STB_LOCAL)
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
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010246c08)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffff800010246c08-ffff800010246eb8: print_synth_event (STB_LOCAL)
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
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002db4a0)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
c0000000002db4a0-c0000000002db9c0: print_synth_event (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bef20)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffffffff811bef20-ffffffff811bf1e4: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b1d00)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffffffff811b1d00-ffffffff811b1fc4: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bccf0)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffffffff811bccf0-ffffffff811bcfb4: print_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum print_line_t print_synth_event(struct trace_iterator *iter, int flags, struct trace_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cad90)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffffffff811cad90-ffffffff811cb054: print_synth_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
