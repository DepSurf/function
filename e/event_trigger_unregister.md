# Function: <code>event_trigger_unregister</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void event_trigger_unregister(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81244788)
Location: kernel/trace/trace_events_trigger.c:949
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff81244ba0-ffffffff81244bcf: event_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void event_trigger_unregister(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81292488)
Location: kernel/trace/trace_events_trigger.c:950
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812928f0-ffffffff8129291f: event_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void event_trigger_unregister(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812af6e8)
Location: kernel/trace/trace_events_trigger.c:952
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812afb50-ffffffff812afb7f: event_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void event_trigger_unregister(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, struct event_trigger_data *trigger_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cbc57)
Location: kernel/trace/trace_events_trigger.c:952
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812cc0c0-ffffffff812cc0ef: event_trigger_unregister (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
