# Function: <code>dynevent_arg_add</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:245
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff811f1e1f-ffffffff811f1e3c: dynevent_arg_add.cold (STB_LOCAL)
ffffffff811f1cd0-ffffffff811f1d12: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:245
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81be647d-ffffffff81be649a: dynevent_arg_add.cold (STB_LOCAL)
ffffffff811f0700-ffffffff811f0742: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81bd8165-ffffffff81bd8182: dynevent_arg_add.cold (STB_LOCAL)
ffffffff811f1660-ffffffff811f16a2: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:294
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81cb760b-ffffffff81cb7628: dynevent_arg_add.cold (STB_LOCAL)
ffffffff81222800-ffffffff81222842: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:289
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_gen_cmd_array_start
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_events_synth.c:synth_event_add_field_str
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff81e686e5-ffffffff81e68702: dynevent_arg_add.cold (STB_LOCAL)
ffffffff81262620-ffffffff8126266e: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3e30)
Location: kernel/trace/trace_dynevent.c:291
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_gen_cmd_array_start
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_events_synth.c:synth_event_add_field_str
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff812b3e30-ffffffff812b3e93: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6730)
Location: kernel/trace/trace_dynevent.c:291
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_gen_cmd_array_start
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_events_synth.c:synth_event_add_field_str
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff812d6730-ffffffff812d6793: dynevent_arg_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dynevent_arg_add(struct dynevent_cmd *cmd, struct dynevent_arg *arg, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f4240)
Location: kernel/trace/trace_dynevent.c:291
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_gen_cmd_array_start
  - kernel/trace/trace_events_synth.c:__synth_event_gen_cmd_start
  - kernel/trace/trace_events_synth.c:synth_event_add_field_str
  - kernel/trace/trace_kprobe.c:__kprobe_event_add_fields
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
  - kernel/trace/trace_kprobe.c:__kprobe_event_gen_cmd_start
```
**Symbols:**

```
ffffffff812f4240-ffffffff812f42a3: dynevent_arg_add (STB_GLOBAL)
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
