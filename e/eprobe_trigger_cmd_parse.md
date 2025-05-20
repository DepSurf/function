# Function: <code>eprobe_trigger_cmd_parse</code>

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
int eprobe_trigger_cmd_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81244df0)
Location: kernel/trace/trace_eprobe.c:622
Inline: False
```
**Symbols:**

```
ffffffff81244df0-ffffffff81244dfa: eprobe_trigger_cmd_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int eprobe_trigger_cmd_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81292c10)
Location: kernel/trace/trace_eprobe.c:580
Inline: False
```
**Symbols:**

```
ffffffff81292c10-ffffffff81292c1a: eprobe_trigger_cmd_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int eprobe_trigger_cmd_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812afe70)
Location: kernel/trace/trace_eprobe.c:484
Inline: False
```
**Symbols:**

```
ffffffff812afe70-ffffffff812afe7a: eprobe_trigger_cmd_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int eprobe_trigger_cmd_parse(struct event_command *cmd_ops, struct trace_event_file *file, char *glob, char *cmd, char *param_and_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812cc3e0)
Location: kernel/trace/trace_eprobe.c:488
Inline: False
```
**Symbols:**

```
ffffffff812cc3e0-ffffffff812cc3ea: eprobe_trigger_cmd_parse (STB_LOCAL)
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
