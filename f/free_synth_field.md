# Function: <code>free_synth_field</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c350)
Location: kernel/trace/trace_events_hist.c:743
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
```
**Symbols:**

```
ffffffff8119c350-ffffffff8119c374: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa630)
Location: kernel/trace/trace_events_hist.c:806
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811aa630-ffffffff811aa654: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b8560)
Location: kernel/trace/trace_events_hist.c:960
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffffffff811b8560-ffffffff811b8587: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c3b40)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffffffff811c3b40-ffffffff811c3b67: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dfdc4)
Location: kernel/trace/trace_events_synth.c:455
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd716)
Location: kernel/trace/trace_events_synth.c:575
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811deab5)
Location: kernel/trace/trace_events_synth.c:576
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120e33f)
Location: kernel/trace/trace_events_synth.c:576
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8124a830)
Location: kernel/trace/trace_events_synth.c:584
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8129946b)
Location: kernel/trace/trace_events_synth.c:595
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b67a1)
Location: kernel/trace/trace_events_synth.c:664
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d2df1)
Location: kernel/trace/trace_events_synth.c:665
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
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
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010243710)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffff800010243710-ffff800010243744: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d6440)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
c0000000002d6440-c0000000002d6494: free_synth_field (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc160)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffffffff811bc160-ffffffff811bc187: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aef40)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffffffff811aef40-ffffffff811aef67: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9f30)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffffffff811b9f30-ffffffff811b9f57: free_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_synth_field(struct synth_field *field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c7fd0)
Location: kernel/trace/trace_events_hist.c:1030
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
**Symbols:**

```
ffffffff811c7fd0-ffffffff811c7ff7: free_synth_field (STB_LOCAL)
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
