# Function: <code>trace_event_dyn_busy</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool trace_event_dyn_busy(struct trace_event_call *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff81222410)
Location: kernel/trace/trace_dynevent.c:54
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff81222410-ffffffff81222419: trace_event_dyn_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trace_event_dyn_busy(struct trace_event_call *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812621d0)
Location: kernel/trace/trace_dynevent.c:54
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff812621d0-ffffffff812621df: trace_event_dyn_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_event_dyn_busy(struct trace_event_call *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3980)
Location: kernel/trace/trace_dynevent.c:54
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff812b3980-ffffffff812b398f: trace_event_dyn_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_event_dyn_busy(struct trace_event_call *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6250)
Location: kernel/trace/trace_dynevent.c:54
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff812d6250-ffffffff812d625f: trace_event_dyn_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_event_dyn_busy(struct trace_event_call *call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f3d60)
Location: kernel/trace/trace_dynevent.c:54
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
**Symbols:**

```
ffffffff812f3d60-ffffffff812f3d6f: trace_event_dyn_busy (STB_GLOBAL)
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
