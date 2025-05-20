# Function: <code>synth_field_fmt</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119ee10)
Location: kernel/trace/trace_events_hist.c:544
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff8119ee10-ffffffff8119f04c: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811accd0)
Location: kernel/trace/trace_events_hist.c:607
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811accd0-ffffffff811acf0c: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bafa0)
Location: kernel/trace/trace_events_hist.c:761
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811bafa0-ffffffff811bb1c8: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c66b0)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811c66b0-ffffffff811c68f6: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de150)
Location: kernel/trace/trace_events_synth.c:197
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff811de150-ffffffff811de347: synth_field_fmt.part.0 (STB_LOCAL)
ffffffff811de350-ffffffff811de3c8: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811db4f0)
Location: kernel/trace/trace_events_synth.c:244
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff811db4f0-ffffffff811db700: synth_field_fmt.part.0 (STB_LOCAL)
ffffffff811db700-ffffffff811db778: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dcb00)
Location: kernel/trace/trace_events_synth.c:245
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff811dcb00-ffffffff811dccd5: synth_field_fmt.part.0 (STB_LOCAL)
ffffffff811dcce0-ffffffff811dcd54: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120c2f0)
Location: kernel/trace/trace_events_synth.c:245
Inline: True
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff8120c2f0-ffffffff8120c4c5: synth_field_fmt.part.0 (STB_LOCAL)
ffffffff8120c4d0-ffffffff8120c544: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812493e8)
Location: kernel/trace/trace_events_synth.c:253
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff81248ab0-ffffffff81248cb0: synth_field_fmt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812975a8)
Location: kernel/trace/trace_events_synth.c:255
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff81296c00-ffffffff81296e00: synth_field_fmt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b46e8)
Location: kernel/trace/trace_events_synth.c:276
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff812b3b90-ffffffff812b3daf: synth_field_fmt.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d0c98)
Location: kernel/trace/trace_events_synth.c:276
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
Direct callers:
  - kernel/trace/trace_events_synth.c:__set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:print_synth_event
```
**Symbols:**

```
ffffffff812d0140-ffffffff812d035f: synth_field_fmt.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff8000102469f8)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffff8000102469f8-ffff800010246c04: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002da7c0)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
c0000000002da7c0-c0000000002db49c: synth_field_fmt (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811becd0)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811becd0-ffffffff811bef16: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b1ab0)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811b1ab0-ffffffff811b1cf6: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bcaa0)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811bcaa0-ffffffff811bcce6: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *synth_field_fmt(char *type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cab40)
Location: kernel/trace/trace_events_hist.c:772
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:print_synth_event
```
**Symbols:**

```
ffffffff811cab40-ffffffff811cad86: synth_field_fmt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
