# Function: <code>dynevent_arg_pair_add</code>

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
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:290
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff811f1e3c-ffffffff811f1e62: dynevent_arg_pair_add.cold (STB_LOCAL)
ffffffff811f1d20-ffffffff811f1d6b: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:290
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff81be649a-ffffffff81be64c0: dynevent_arg_pair_add.cold (STB_LOCAL)
ffffffff811f0750-ffffffff811f079b: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:301
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff81bd8182-ffffffff81bd81a8: dynevent_arg_pair_add.cold (STB_LOCAL)
ffffffff811f16b0-ffffffff811f16fb: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:339
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff81cb7628-ffffffff81cb764e: dynevent_arg_pair_add.cold (STB_LOCAL)
ffffffff81222850-ffffffff8122289b: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_dynevent.c (0)
Location: kernel/trace/trace_dynevent.c:334
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff81e68702-ffffffff81e68728: dynevent_arg_pair_add.cold (STB_LOCAL)
ffffffff81262670-ffffffff812626cd: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b3eb0)
Location: kernel/trace/trace_dynevent.c:336
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff812b3eb0-ffffffff812b3f2b: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d67b0)
Location: kernel/trace/trace_dynevent.c:336
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff812d67b0-ffffffff812d682b: dynevent_arg_pair_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dynevent_arg_pair_add(struct dynevent_cmd *cmd, struct dynevent_arg_pair *arg_pair, dynevent_check_arg_fn_t check_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f42c0)
Location: kernel/trace/trace_dynevent.c:336
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_field
```
**Symbols:**

```
ffffffff812f42c0-ffffffff812f433b: dynevent_arg_pair_add (STB_GLOBAL)
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
