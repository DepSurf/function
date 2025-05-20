# Function: <code>trace_seq_putmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81155550)
Location: kernel/trace/trace_seq.c:261
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:print_one_line
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
```
**Symbols:**

```
ffffffff81155550-ffffffff811555d9: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8115e880)
Location: kernel/trace/trace_seq.c:261
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff8115e880-ffffffff8115e908: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811692f0)
Location: kernel/trace/trace_seq.c:261
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811692f0-ffffffff81169378: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8116c2c0)
Location: kernel/trace/trace_seq.c:261
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff8116c2c0-ffffffff8116c33f: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81179350)
Location: kernel/trace/trace_seq.c:261
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff81179350-ffffffff811793cf: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81188530)
Location: kernel/trace/trace_seq.c:261
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff81188530-ffffffff811885ae: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81195de0)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff81195de0-ffffffff81195e5e: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a3c80)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811a3c80-ffffffff811a3cfd: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811af480)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811af480-ffffffff811af4fd: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c7560)
Location: kernel/trace/trace_seq.c:259
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811c7560-ffffffff811c75de: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c4c60)
Location: kernel/trace/trace_seq.c:259
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_bin_fmt
  - kernel/trace/trace.c:print_hex_fmt
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811c4c60-ffffffff811c4cde: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c5e50)
Location: kernel/trace/trace_seq.c:259
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811c5e50-ffffffff811c5ece: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811f1440)
Location: kernel/trace/trace_seq.c:259
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811f1440-ffffffff811f14be: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81229d20)
Location: kernel/trace/trace_seq.c:259
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff81229d20-ffffffff81229dd4: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812754b0)
Location: kernel/trace/trace_seq.c:259
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff812754b0-ffffffff81275564: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8128ce70)
Location: kernel/trace/trace_seq.c:260
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff8128ce70-ffffffff8128cf24: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812a8250)
Location: kernel/trace/trace_seq.c:257
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff812a8250-ffffffff812a8307: trace_seq_putmem (STB_GLOBAL)
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
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffff80001022ca78)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffff80001022ca78-ffff80001022caec: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (c046a278)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
c046a278-c046a2f4: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (c0000000002b5250)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
c0000000002b5250-c0000000002b52f0: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffe0001867b0)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffe0001867b0-ffffffe000186810: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a7aa0)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811a7aa0-ffffffff811a7b1d: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8119aa20)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff8119aa20-ffffffff8119aa9d: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811a5870)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811a5870-ffffffff811a58ed: trace_seq_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_seq_putmem(struct trace_seq *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811b3610)
Location: kernel/trace/trace_seq.c:262
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_ctxwake_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/trace_output.c:trace_fn_bin
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:blk_trace_event_print_binary
  - kernel/trace/blktrace.c:print_one_line
```
**Symbols:**

```
ffffffff811b3610-ffffffff811b368d: trace_seq_putmem (STB_GLOBAL)
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
