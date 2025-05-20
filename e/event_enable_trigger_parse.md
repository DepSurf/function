# Function: <code>event_enable_trigger_parse</code>

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
int event_enable_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812445f0)
Location: kernel/trace/trace_events_trigger.c:1718
Inline: False
```
**Symbols:**

```
ffffffff812445f0-ffffffff8124494e: event_enable_trigger_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_enable_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812922f0)
Location: kernel/trace/trace_events_trigger.c:1732
Inline: False
```
**Symbols:**

```
ffffffff812922f0-ffffffff8129264e: event_enable_trigger_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_enable_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812af550)
Location: kernel/trace/trace_events_trigger.c:1734
Inline: False
```
**Symbols:**

```
ffffffff812af550-ffffffff812af8ae: event_enable_trigger_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_enable_trigger_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cba90)
Location: kernel/trace/trace_events_trigger.c:1736
Inline: False
```
**Symbols:**

```
ffffffff812cba90-ffffffff812cbe1d: event_enable_trigger_parse (STB_GLOBAL)
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
