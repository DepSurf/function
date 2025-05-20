# Function: <code>ftrace_graph_ret_addr</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8116f0f0)
Location: kernel/trace/trace_functions_graph.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:unwind_get_return_address
```
**Symbols:**

```
ffffffff8116f0f0-ffffffff8116f146: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff811722e0)
Location: kernel/trace/trace_functions_graph.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811722e0-ffffffff81172336: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8117f480)
Location: kernel/trace/trace_functions_graph.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff8117f480-ffffffff8117f4d6: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8118e580)
Location: kernel/trace/trace_functions_graph.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff8118e580-ffffffff8118e5ce: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a0680)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811a0680-ffffffff811a06bf: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ae4e0)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811ae4e0-ffffffff811ae51b: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b9c70)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811b9c70-ffffffff811b9cab: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d2c00)
Location: kernel/trace/fgraph.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811d2c00-ffffffff811d2c42: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811cfd70)
Location: kernel/trace/fgraph.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811cfd70-ffffffff811cfdb2: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d0f00)
Location: kernel/trace/fgraph.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811d0f00-ffffffff811d0f3b: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811fdb80)
Location: kernel/trace/fgraph.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811fdb80-ffffffff811fdbbb: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812384d0)
Location: kernel/trace/fgraph.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff812384d0-ffffffff8123852f: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff81285320)
Location: kernel/trace/fgraph.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff81285320-ffffffff8128537f: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812a1fd0)
Location: kernel/trace/fgraph.c:332
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff812a1fd0-ffffffff812a202f: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812bd700)
Location: kernel/trace/fgraph.c:332
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff812bd700-ffffffff812bd75f: ftrace_graph_ret_addr (STB_GLOBAL)
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
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffff8000102383e0)
Location: kernel/trace/fgraph.c:292
Inline: False
```
**Symbols:**

```
ffff8000102383e0-ffff80001023842c: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0473fb4)
Location: kernel/trace/fgraph.c:292
Inline: False
```
**Symbols:**

```
c0473fb4-c0474010: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0000000002c46f0)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:show_stack
  - arch/powerpc/kernel/process.c:show_stack
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable
```
**Symbols:**

```
c0000000002c46f0-c0000000002c475c: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffe00018f2f6)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/riscv/kernel/stacktrace.c:walk_stackframe
```
**Symbols:**

```
ffffffe00018f2f6-ffffffe00018f342: ftrace_graph_ret_addr (STB_GLOBAL)
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
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b2290)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811b2290-ffffffff811b22cb: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a50a0)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811a50a0-ffffffff811a50db: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b0060)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811b0060-ffffffff811b009b: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int ftrace_graph_ret_addr(struct task_struct *task, int *idx, long unsigned int ret, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811be0d0)
Location: kernel/trace/fgraph.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
**Symbols:**

```
ffffffff811be0d0-ffffffff811be10b: ftrace_graph_ret_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
