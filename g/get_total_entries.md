# Function: <code>get_total_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114ca20)
Location: kernel/trace/trace.c:2529
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:print_trace_header
```
**Symbols:**

```
ffffffff8114ca20-ffffffff8114cadb: get_total_entries.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81155380)
Location: kernel/trace/trace.c:2866
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
**Symbols:**

```
ffffffff81155380-ffffffff8115543b: get_total_entries.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115f850)
Location: kernel/trace/trace.c:3090
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
**Symbols:**

```
ffffffff8115f850-ffffffff8115f90d: get_total_entries.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162c40)
Location: kernel/trace/trace.c:3302
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
**Symbols:**

```
ffffffff81162c40-ffffffff81162cfc: get_total_entries.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116fb50)
Location: kernel/trace/trace.c:3311
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
**Symbols:**

```
ffffffff8116fb50-ffffffff8116fbfa: get_total_entries.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117ea30)
Location: kernel/trace/trace.c:3317
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
**Symbols:**

```
ffffffff8117ea30-ffffffff8117eada: get_total_entries.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118c330)
Location: kernel/trace/trace.c:3319
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
**Symbols:**

```
ffffffff8118c330-ffffffff8118c3da: get_total_entries.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199900)
Location: kernel/trace/trace.c:3516
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff81199900-ffffffff8119999f: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5200)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff811a5200-ffffffff811a529f: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9fb0)
Location: kernel/trace/trace.c:3706
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_func_help_header_irq
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff811b9fb0-ffffffff811ba04a: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b7b80)
Location: kernel/trace/trace.c:3774
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_func_help_header_irq
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff811b7b80-ffffffff811b7c1a: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b86c0)
Location: kernel/trace/trace.c:4101
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff811b86c0-ffffffff811b8757: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e2be0)
Location: kernel/trace/trace.c:4173
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff811e2be0-ffffffff811e2c77: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81219b30)
Location: kernel/trace/trace.c:4176
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff81219b30-ffffffff81219be2: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81266180)
Location: kernel/trace/trace.c:4200
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff81266180-ffffffff8126623a: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127d1d0)
Location: kernel/trace/trace.c:4301
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff8127d1d0-ffffffff8127d27a: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_total_entries(struct array_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81297a80)
Location: kernel/trace/trace.c:4263
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff81297a80-ffffffff81297b2a: get_total_entries (STB_LOCAL)
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
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010220368)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffff800010220368-ffff800010220444: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045cba0)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
c045cba0-c045cc68: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a4230)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
c0000000002a4230-c0000000002a4340: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017cd24)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffe00017cd24-ffffffe00017cdc6: get_total_entries (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d820)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff8119d820-ffffffff8119d8bf: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190880)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff81190880-ffffffff8119091f: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b5f0)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff8119b5f0-ffffffff8119b68f: get_total_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_total_entries(struct trace_buffer *buf, long unsigned int *total, long unsigned int *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9290)
Location: kernel/trace/trace.c:3542
Inline: False
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_total_entries
```
**Symbols:**

```
ffffffff811a9290-ffffffff811a932f: get_total_entries (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct trace_buffer *buf</code> ➡️ <code>struct array_buffer *buf</code>
</li>
</ul>
</details>
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
