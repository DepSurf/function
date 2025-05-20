# Function: <code>synth_event_add_field_str</code>

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
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dec60)
Location: kernel/trace/trace_events_synth.c:775
Inline: True
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff811dec60-ffffffff811dece1: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dbf70)
Location: kernel/trace/trace_events_synth.c:964
Inline: True
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff811dbf70-ffffffff811dbff1: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd460)
Location: kernel/trace/trace_events_synth.c:982
Inline: True
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff811dd460-ffffffff811dd4e1: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120cca0)
Location: kernel/trace/trace_events_synth.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff8120cca0-ffffffff8120cd21: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81247ea0)
Location: kernel/trace/trace_events_synth.c:988
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff81247ea0-ffffffff81247f3d: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812964d0)
Location: kernel/trace/trace_events_synth.c:998
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff812964d0-ffffffff8129656d: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b3480)
Location: kernel/trace/trace_events_synth.c:1070
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff812b3480-ffffffff812b351d: synth_event_add_field_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int synth_event_add_field_str(struct dynevent_cmd *cmd, const char *type_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812cfa30)
Location: kernel/trace/trace_events_synth.c:1071
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
```
**Symbols:**

```
ffffffff812cfa30-ffffffff812cfacd: synth_event_add_field_str (STB_GLOBAL)
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
