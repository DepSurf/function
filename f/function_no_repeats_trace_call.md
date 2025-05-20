# Function: <code>function_no_repeats_trace_call</code>

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
void function_no_repeats_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811c9420)
Location: kernel/trace/trace_functions.c:282
Inline: False
```
**Symbols:**

```
ffffffff811c9420-ffffffff811c95d9: function_no_repeats_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void function_no_repeats_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811f4e80)
Location: kernel/trace/trace_functions.c:282
Inline: False
```
**Symbols:**

```
ffffffff811f4e80-ffffffff811f5065: function_no_repeats_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void function_no_repeats_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8122e020)
Location: kernel/trace/trace_functions.c:280
Inline: False
```
**Symbols:**

```
ffffffff8122e020-ffffffff8122e213: function_no_repeats_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void function_no_repeats_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81279ee0)
Location: kernel/trace/trace_functions.c:280
Inline: False
```
**Symbols:**

```
ffffffff81279ee0-ffffffff8127a0d3: function_no_repeats_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void function_no_repeats_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (0)
Location: kernel/trace/trace_functions.c:280
Inline: False
```
**Symbols:**

```
ffffffff81291920-ffffffff81291b8a: function_no_repeats_trace_call (STB_LOCAL)
ffffffff820dc690-ffffffff820dc6a5: function_no_repeats_trace_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void function_no_repeats_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (0)
Location: kernel/trace/trace_functions.c:280
Inline: False
```
**Symbols:**

```
ffffffff812acf30-ffffffff812ad19a: function_no_repeats_trace_call (STB_LOCAL)
ffffffff821b84c0-ffffffff821b84d5: function_no_repeats_trace_call.cold (STB_LOCAL)
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
