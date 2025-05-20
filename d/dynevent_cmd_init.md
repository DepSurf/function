# Function: <code>dynevent_cmd_init</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1d90)
Location: kernel/trace/trace_dynevent.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff811f1d90-ffffffff811f1dd0: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f07c0)
Location: kernel/trace/trace_dynevent.c:358
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff811f07c0-ffffffff811f0800: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1720)
Location: kernel/trace/trace_dynevent.c:369
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff811f1720-ffffffff811f1760: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812228c0)
Location: kernel/trace/trace_dynevent.c:407
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff812228c0-ffffffff81222900: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff81262700)
Location: kernel/trace/trace_dynevent.c:402
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff81262700-ffffffff8126275b: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3f90)
Location: kernel/trace/trace_dynevent.c:404
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff812b3f90-ffffffff812b3feb: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6890)
Location: kernel/trace/trace_dynevent.c:404
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff812d6890-ffffffff812d68eb: dynevent_cmd_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dynevent_cmd_init(struct dynevent_cmd *cmd, char *buf, int maxlen, enum dynevent_type type, dynevent_create_fn_t run_command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f43a0)
Location: kernel/trace/trace_dynevent.c:404
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_cmd_init
```
**Symbols:**

```
ffffffff812f43a0-ffffffff812f43f2: dynevent_cmd_init (STB_GLOBAL)
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
