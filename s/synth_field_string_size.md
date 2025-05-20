# Function: <code>synth_field_string_size</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a3fa0)
Location: kernel/trace/trace_events_hist.c:472
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
In kernel/trace/trace_events_hist.c (ffffffff811af688)
Location: kernel/trace/trace_events_hist.c:535
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
In kernel/trace/trace_events_hist.c (ffffffff811bee90)
Location: kernel/trace/trace_events_hist.c:689
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
In kernel/trace/trace_events_hist.c (ffffffff811ca6d1)
Location: kernel/trace/trace_events_hist.c:698
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:123
Inline: False
```
**Symbols:**

```
ffffffff811ddbb0-ffffffff811ddc64: synth_field_string_size (STB_LOCAL)
ffffffff811dffd8-ffffffff811dffe4: synth_field_string_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:165
Inline: False
```
**Symbols:**

```
ffffffff811dacc0-ffffffff811dad9d: synth_field_string_size (STB_LOCAL)
ffffffff81be6317-ffffffff81be6323: synth_field_string_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:166
Inline: False
```
**Symbols:**

```
ffffffff811dc2d0-ffffffff811dc3ad: synth_field_string_size (STB_LOCAL)
ffffffff81bd7fd2-ffffffff81bd7fde: synth_field_string_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:166
Inline: False
```
**Symbols:**

```
ffffffff8120ba00-ffffffff8120baf8: synth_field_string_size (STB_LOCAL)
ffffffff81cb6ab3-ffffffff81cb6abf: synth_field_string_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:174
Inline: False
```
**Symbols:**

```
ffffffff81247b90-ffffffff81247ca0: synth_field_string_size (STB_LOCAL)
ffffffff81e67b04-ffffffff81e67b10: synth_field_string_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81296240)
Location: kernel/trace/trace_events_synth.c:176
Inline: False
```
**Symbols:**

```
ffffffff81296240-ffffffff81296358: synth_field_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b31f0)
Location: kernel/trace/trace_events_synth.c:195
Inline: False
```
**Symbols:**

```
ffffffff812b31f0-ffffffff812b3308: synth_field_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int synth_field_string_size(char *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812cf7a0)
Location: kernel/trace/trace_events_synth.c:195
Inline: False
```
**Symbols:**

```
ffffffff812cf7a0-ffffffff812cf8b8: synth_field_string_size (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024bbf0)
Location: kernel/trace/trace_events_hist.c:698
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
In kernel/trace/trace_events_hist.c (c0000000002e479c)
Location: kernel/trace/trace_events_hist.c:698
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
In kernel/trace/trace_events_hist.c (ffffffff811c2cf1)
Location: kernel/trace/trace_events_hist.c:698
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
In kernel/trace/trace_events_hist.c (ffffffff811b5ad1)
Location: kernel/trace/trace_events_hist.c:698
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
In kernel/trace/trace_events_hist.c (ffffffff811c0ac1)
Location: kernel/trace/trace_events_hist.c:698
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
In kernel/trace/trace_events_hist.c (ffffffff811ceb61)
Location: kernel/trace/trace_events_hist.c:698
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
