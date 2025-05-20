# Function: <code>tracing_set_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114e260)
Location: kernel/trace/trace.c:5212
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_init
```
**Symbols:**

```
ffffffff8114e260-ffffffff8114e33b: tracing_set_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156ec0)
Location: kernel/trace/trace.c:5613
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:tracing_clock_write
```
**Symbols:**

```
ffffffff81156ec0-ffffffff81156f9b: tracing_set_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162000)
Location: kernel/trace/trace.c:5889
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:tracing_clock_write
```
**Symbols:**

```
ffffffff81162000-ffffffff811620db: tracing_set_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165420)
Location: kernel/trace/trace.c:6205
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracing_clock_write
```
**Symbols:**

```
ffffffff81165420-ffffffff811654e3: tracing_set_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172360)
Location: kernel/trace/trace.c:6216
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracing_clock_write
```
**Symbols:**

```
ffffffff81172360-ffffffff81172423: tracing_set_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811853d0)
Location: kernel/trace/trace.c:6232
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811853d0-ffffffff81185493: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192d00)
Location: kernel/trace/trace.c:6254
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff81192d00-ffffffff81192dc3: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0690)
Location: kernel/trace/trace.c:6483
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811a0690-ffffffff811a074e: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac0c0)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811ac0c0-ffffffff811ac17e: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c4860)
Location: kernel/trace/trace.c:6731
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c4860-ffffffff811c4922: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2460)
Location: kernel/trace/trace.c:6805
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c2460-ffffffff811c2522: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c34e0)
Location: kernel/trace/trace.c:7138
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c34e0-ffffffff811c35a2: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ee650)
Location: kernel/trace/trace.c:7216
Inline: False
Direct callers:
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811ee650-ffffffff811ee75c: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81226970)
Location: kernel/trace/trace.c:7221
Inline: False
Direct callers:
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81226970-ffffffff81226a8c: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81271be0)
Location: kernel/trace/trace.c:7272
Inline: False
Direct callers:
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81271be0-ffffffff81271cfc: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81288ee0)
Location: kernel/trace/trace.c:7428
Inline: False
Direct callers:
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81288ee0-ffffffff81288ffc: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a4230)
Location: kernel/trace/trace.c:7461
Inline: False
Direct callers:
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff812a4230-ffffffff812a434c: tracing_set_clock (STB_GLOBAL)
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
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010229048)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffff800010229048-ffff800010229128: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0466644)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
```
**Symbols:**

```
c0466644-c0466708: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b0240)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
c0000000002b0240-c0000000002b04f8: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018382e)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
```
**Symbols:**

```
ffffffe00018382e-ffffffe000183902: tracing_set_clock (STB_GLOBAL)
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
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a46e0)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811a46e0-ffffffff811a479e: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197690)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff81197690-ffffffff8119774e: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a24b0)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811a24b0-ffffffff811a256e: tracing_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array *tr, const char *clockstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b0240)
Location: kernel/trace/trace.c:6535
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811b0240-ffffffff811b02fe: tracing_set_clock (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
