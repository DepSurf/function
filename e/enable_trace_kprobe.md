# Function: <code>enable_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81168942)
Location: kernel/trace/trace_kprobe.c:350
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81175fd2)
Location: kernel/trace/trace_kprobe.c:356
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81181a62)
Location: kernel/trace/trace_kprobe.c:371
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
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
In kernel/trace/trace_kprobe.c (ffffffff81184812)
Location: kernel/trace/trace_kprobe.c:377
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
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
In kernel/trace/trace_kprobe.c (ffffffff811924e2)
Location: kernel/trace/trace_kprobe.c:377
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_kprobe *tk, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a6aa0)
Location: kernel/trace/trace_kprobe.c:401
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff811a6aa0-ffffffff811a6ba6: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int enable_trace_kprobe(struct trace_kprobe *tk, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b4f00)
Location: kernel/trace/trace_kprobe.c:303
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff811b4f00-ffffffff811b501b: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c4991)
Location: kernel/trace/trace_kprobe.c:299
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff811c3cc0-ffffffff811c3d38: enable_trace_kprobe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cf030)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
ffffffff811cf030-ffffffff811cf156: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb2e0)
Location: kernel/trace/trace_kprobe.c:350
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff811eb2e0-ffffffff811eb403: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811e9430)
Location: kernel/trace/trace_kprobe.c:352
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff811e9430-ffffffff811e9553: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ea2c0)
Location: kernel/trace/trace_kprobe.c:352
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff811ea2c0-ffffffff811ea3e3: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121b100)
Location: kernel/trace/trace_kprobe.c:348
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff8121b100-ffffffff8121b223: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125a350)
Location: kernel/trace/trace_kprobe.c:347
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff8125a350-ffffffff8125a4b3: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812aa770)
Location: kernel/trace/trace_kprobe.c:349
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff812aa770-ffffffff812aa8d3: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ccf20)
Location: kernel/trace/trace_kprobe.c:349
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff812ccf20-ffffffff812cd094: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ea910)
Location: kernel/trace/trace_kprobe.c:349
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
**Symbols:**

```
ffffffff812ea910-ffffffff812eaa84: enable_trace_kprobe (STB_LOCAL)
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
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024f8a0)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
ffff80001024f8a0-ffff80001024f9ec: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c04828e0)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
c04828e0-c0482a28: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ecfb0)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
c0000000002ecfb0-c0000000002ed194: enable_trace_kprobe (STB_LOCAL)
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
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c7650)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
ffffffff811c7650-ffffffff811c7776: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ba430)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
ffffffff811ba430-ffffffff811ba556: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c5420)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
ffffffff811c5420-ffffffff811c5546: enable_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_event_call *call, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d3680)
Location: kernel/trace/trace_kprobe.c:351
Inline: False
```
**Symbols:**

```
ffffffff811d3680-ffffffff811d37a6: enable_trace_kprobe (STB_LOCAL)
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
