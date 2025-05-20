# Function: <code>trace_parse_run_command</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811773b0)
Location: kernel/trace/trace.c:8295
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811773b0-ffffffff81177507: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8400
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81186708-ffffffff81186725: trace_parse_run_command.cold.85 (STB_LOCAL)
ffffffff811863c0-ffffffff8118650a: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8474
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81194076-ffffffff81194093: trace_parse_run_command.cold.85 (STB_LOCAL)
ffffffff81193d50-ffffffff81193e9a: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8979
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811a1d5c-ffffffff811a1d79: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811a1880-ffffffff811a19c9: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811ad747-ffffffff811ad764: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811ad330-ffffffff811ad479: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9321
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811c5775-ffffffff811c5792: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811c5040-ffffffff811c5183: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9454
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81be5a92-ffffffff81be5aaf: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811c2c80-ffffffff811c2dc3: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9776
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81bd7948-ffffffff81bd7965: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811c3c90-ffffffff811c3dcd: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9938
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81cb5872-ffffffff81cb588f: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811eef00-ffffffff811ef03d: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9984
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81e66874-ffffffff81e66891: trace_parse_run_command.cold (STB_LOCAL)
ffffffff812273a0-ffffffff812274f2: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81272820)
Location: kernel/trace/trace.c:10079
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81272820-ffffffff81272988: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81289b20)
Location: kernel/trace/trace.c:10244
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81289b20-ffffffff81289cfa: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a4ea0)
Location: kernel/trace/trace.c:10439
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff812a4ea0-ffffffff812a50a9: trace_parse_run_command (STB_GLOBAL)
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
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001022a598)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffff80001022a598-ffff80001022a714: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0467c3c)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
c0467c3c-c0467e14: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b2270)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
c0000000002b2270-c0000000002b2490: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000184b38)
Location: kernel/trace/trace.c:9035
Inline: False
```
**Symbols:**

```
ffffffe000184b38-ffffffe000184c6a: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811a5d67-ffffffff811a5d84: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811a5950-ffffffff811a5a99: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81198cf1-ffffffff81198d0e: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811988e0-ffffffff81198a29: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811a3b37-ffffffff811a3b54: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811a3720-ffffffff811a3869: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t trace_parse_run_command(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_events_write
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_dynevent.c:dyn_event_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff811b18c7-ffffffff811b18e4: trace_parse_run_command.cold (STB_LOCAL)
ffffffff811b14b0-ffffffff811b15f9: trace_parse_run_command (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<b>Param type changed. </b>
<code>int (*createfn)(int, char **)</code> ➡️ <code>int (*createfn)(const char *)</code>
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
