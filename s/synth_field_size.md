# Function: <code>synth_field_size</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a3dd4)
Location: kernel/trace/trace_events_hist.c:504
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811af4ae)
Location: kernel/trace/trace_events_hist.c:567
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811becc1)
Location: kernel/trace/trace_events_hist.c:721
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ca4eb)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de860)
Location: kernel/trace/trace_events_synth.c:155
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_check_arg_fn
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff811de860-ffffffff811dea43: synth_field_size.part.0 (STB_LOCAL)
ffffffff811dea50-ffffffff811deabf: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dbcb0)
Location: kernel/trace/trace_events_synth.c:200
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_check_arg_fn
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff811dbcb0-ffffffff811dbeb2: synth_field_size.part.0 (STB_LOCAL)
ffffffff811dbec0-ffffffff811dbf2f: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd200)
Location: kernel/trace/trace_events_synth.c:201
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_check_arg_fn
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff811dd200-ffffffff811dd3ae: synth_field_size.part.0 (STB_LOCAL)
ffffffff811dd3b0-ffffffff811dd411: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120ca40)
Location: kernel/trace/trace_events_synth.c:201
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_check_arg_fn
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff8120ca40-ffffffff8120cbee: synth_field_size.part.0 (STB_LOCAL)
ffffffff8120cbf0-ffffffff8120cc51: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81249080)
Location: kernel/trace/trace_events_synth.c:209
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff81249080-ffffffff8124922a: synth_field_size.part.0 (STB_LOCAL)
ffffffff81249230-ffffffff81249297: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812971f0)
Location: kernel/trace/trace_events_synth.c:211
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff812971f0-ffffffff8129739a: synth_field_size.part.0 (STB_LOCAL)
ffffffff812973b0-ffffffff81297417: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b4270)
Location: kernel/trace/trace_events_synth.c:230
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff812b4270-ffffffff812b441a: synth_field_size.part.0 (STB_LOCAL)
ffffffff812b4430-ffffffff812b4497: synth_field_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int synth_field_size(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d0820)
Location: kernel/trace/trace_events_synth.c:230
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
**Symbols:**

```
ffffffff812d0820-ffffffff812d09ca: synth_field_size.part.0 (STB_LOCAL)
ffffffff812d09e0-ffffffff812d0a47: synth_field_size (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff80001024ba7c)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e39a4)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c2b0b)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b58eb)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c08db)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ce97b)
Location: kernel/trace/trace_events_hist.c:730
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
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
