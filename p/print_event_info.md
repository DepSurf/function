# Function: <code>print_event_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114cae0)
Location: kernel/trace/trace.c:2568
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff8114cae0-ffffffff8114cb65: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81155440)
Location: kernel/trace/trace.c:2905
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff81155440-ffffffff811554c5: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160420)
Location: kernel/trace/trace.c:3129
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff81160420-ffffffff811604a6: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116876f)
Location: kernel/trace/trace.c:3341
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811756ff)
Location: kernel/trace/trace.c:3350
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811847b6)
Location: kernel/trace/trace.c:3356
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118d230)
Location: kernel/trace/trace.c:3358
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff8118d230-ffffffff8118d2b6: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119a230)
Location: kernel/trace/trace.c:3568
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff8119a230-ffffffff8119a2a3: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a52a0)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff811a52a0-ffffffff811a5312: print_event_info (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811c36e2)
Location: kernel/trace/trace.c:3758
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_func_help_header_irq
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
In kernel/trace/trace.c (ffffffff811c12f2)
Location: kernel/trace/trace.c:3826
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_func_help_header_irq
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
In kernel/trace/trace.c (ffffffff811c2323)
Location: kernel/trace/trace.c:4153
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
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
In kernel/trace/trace.c (ffffffff811ecf63)
Location: kernel/trace/trace.c:4226
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_event_info(struct array_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81219bf0)
Location: kernel/trace/trace.c:4229
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff81219bf0-ffffffff81219c80: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_event_info(struct array_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81266250)
Location: kernel/trace/trace.c:4253
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff81266250-ffffffff812662e0: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_event_info(struct array_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127d290)
Location: kernel/trace/trace.c:4354
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff8127d290-ffffffff8127d320: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_event_info(struct array_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81297b40)
Location: kernel/trace/trace.c:4316
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff81297b40-ffffffff81297bd0: print_event_info (STB_LOCAL)
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
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010220448)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffff800010220448-ffff8000102204c0: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045cc68)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
c045cc68-c045ccf8: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a4340)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
c0000000002a4340-c0000000002a43e4: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017cdc6)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffe00017cdc6-ffffffe00017ce20: print_event_info (STB_LOCAL)
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
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d8c0)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff8119d8c0-ffffffff8119d932: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190920)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff81190920-ffffffff81190992: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b690)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff8119b690-ffffffff8119b702: print_event_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_event_info(struct trace_buffer *buf, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9330)
Location: kernel/trace/trace.c:3594
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
```
**Symbols:**

```
ffffffff811a9330-ffffffff811a93a2: print_event_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
