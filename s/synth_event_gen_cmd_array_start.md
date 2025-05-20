# Function: <code>synth_event_gen_cmd_array_start</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811decf0)
Location: kernel/trace/trace_events_synth.c:937
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff811decf0-ffffffff811dedbb: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dc000)
Location: kernel/trace/trace_events_synth.c:1126
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff811dc000-ffffffff811dc0cb: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd4f0)
Location: kernel/trace/trace_events_synth.c:1144
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff811dd4f0-ffffffff811dd5bb: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120cd30)
Location: kernel/trace/trace_events_synth.c:1142
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff8120cd30-ffffffff8120cdfb: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81247f40)
Location: kernel/trace/trace_events_synth.c:1150
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff81247f40-ffffffff8124802b: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81296580)
Location: kernel/trace/trace_events_synth.c:1160
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff81296580-ffffffff8129666b: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b3530)
Location: kernel/trace/trace_events_synth.c:1233
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff812b3530-ffffffff812b361b: synth_event_gen_cmd_array_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int synth_event_gen_cmd_array_start(struct dynevent_cmd *cmd, const char *name, struct module *mod, struct synth_field_desc *fields, unsigned int n_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812cfae0)
Location: kernel/trace/trace_events_synth.c:1234
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
```
**Symbols:**

```
ffffffff812cfae0-ffffffff812cfbcb: synth_event_gen_cmd_array_start (STB_GLOBAL)
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
