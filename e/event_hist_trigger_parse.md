# Function: <code>event_hist_trigger_parse</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int event_hist_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81254c30)
Location: kernel/trace/trace_events_hist.c:6204
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff81254c30-ffffffff81255304: event_hist_trigger_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_hist_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a40c0)
Location: kernel/trace/trace_events_hist.c:6438
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff812a40c0-ffffffff812a479a: event_hist_trigger_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_hist_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c1f80)
Location: kernel/trace/trace_events_hist.c:6543
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff812c1f80-ffffffff812c2679: event_hist_trigger_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_hist_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812de3c0)
Location: kernel/trace/trace_events_hist.c:6539
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_free
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff812de3c0-ffffffff812def2f: event_hist_trigger_parse (STB_LOCAL)
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
