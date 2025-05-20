# Function: <code>trace_last_func_repeats</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_last_func_repeats(struct trace_array *tr, struct trace_func_repeats *last_info, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfbd0)
Location: kernel/trace/trace.c:3148
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
```
**Symbols:**

```
ffffffff811bfbd0-ffffffff811bfcb5: trace_last_func_repeats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_last_func_repeats(struct trace_array *tr, struct trace_func_repeats *last_info, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ea520)
Location: kernel/trace/trace.c:3208
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
```
**Symbols:**

```
ffffffff811ea520-ffffffff811ea605: trace_last_func_repeats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_last_func_repeats(struct trace_array *tr, struct trace_func_repeats *last_info, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81222420)
Location: kernel/trace/trace.c:3206
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
```
**Symbols:**

```
ffffffff81222420-ffffffff81222519: trace_last_func_repeats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_last_func_repeats(struct trace_array *tr, struct trace_func_repeats *last_info, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126d430)
Location: kernel/trace/trace.c:3230
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
```
**Symbols:**

```
ffffffff8126d430-ffffffff8126d526: trace_last_func_repeats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_last_func_repeats(struct trace_array *tr, struct trace_func_repeats *last_info, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812845a0)
Location: kernel/trace/trace.c:3321
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
```
**Symbols:**

```
ffffffff812845a0-ffffffff81284696: trace_last_func_repeats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_last_func_repeats(struct trace_array *tr, struct trace_func_repeats *last_info, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129f6a0)
Location: kernel/trace/trace.c:3298
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
```
**Symbols:**

```
ffffffff8129f6a0-ffffffff8129f796: trace_last_func_repeats (STB_GLOBAL)
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
