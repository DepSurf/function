# Function: <code>stack_trace_call</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811584a0)
Location: kernel/trace/trace_stack.c:201
Inline: False
```
**Symbols:**

```
ffffffff811584a0-ffffffff8115851a: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81162d30)
Location: kernel/trace/trace_stack.c:205
Inline: False
```
**Symbols:**

```
ffffffff81162d30-ffffffff81162daa: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8116e060)
Location: kernel/trace/trace_stack.c:205
Inline: False
```
**Symbols:**

```
ffffffff8116e060-ffffffff8116e0da: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811713a0)
Location: kernel/trace/trace_stack.c:214
Inline: False
```
**Symbols:**

```
ffffffff811713a0-ffffffff811713f6: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8117e520)
Location: kernel/trace/trace_stack.c:200
Inline: False
```
**Symbols:**

```
ffffffff8117e520-ffffffff8117e587: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8118d5c0)
Location: kernel/trace/trace_stack.c:200
Inline: False
```
**Symbols:**

```
ffffffff8118d5c0-ffffffff8118d628: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8119af40)
Location: kernel/trace/trace_stack.c:200
Inline: False
```
**Symbols:**

```
ffffffff8119af40-ffffffff8119afa8: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:174
Inline: False
```
**Symbols:**

```
ffffffff811a87f0-ffffffff811a8acc: stack_trace_call (STB_LOCAL)
ffffffff811a8c3c-ffffffff811a8c8e: stack_trace_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811b4010-ffffffff811b42ec: stack_trace_call (STB_LOCAL)
ffffffff811b445c-ffffffff811b44ae: stack_trace_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811ccae0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811ccae0-ffffffff811ccb47: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811ca020)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811ca020-ffffffff811ca087: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811cb3e0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811cb3e0-ffffffff811cb447: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811f7870)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811f7870-ffffffff811f78d7: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81231410)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff81231410-ffffffff812314a0: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8127d980)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff8127d980-ffffffff8127da10: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8129a400)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff8129a400-ffffffff8129a490: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff812b5a80)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff812b5a80-ffffffff812b5b10: stack_trace_call (STB_LOCAL)
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
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffff8000102323d0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffff8000102323d0-ffff8000102327b8: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (c046e07c)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
c046e07c-c046e410: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (c0000000002bcc70)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
c0000000002bcc70-c0000000002bd178: stack_trace_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffe000189b3e)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffe000189b3e-ffffffe000189e0c: stack_trace_call (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811ac630-ffffffff811ac90c: stack_trace_call (STB_LOCAL)
ffffffff811aca7c-ffffffff811acace: stack_trace_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff8119f380-ffffffff8119f63c: stack_trace_call (STB_LOCAL)
ffffffff8119f90c-ffffffff8119f95e: stack_trace_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811aa400-ffffffff811aa6dc: stack_trace_call (STB_LOCAL)
ffffffff811aa84c-ffffffff811aa89e: stack_trace_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void stack_trace_call(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *op, struct pt_regs *pt_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_stack.c (0)
Location: kernel/trace/trace_stack.c:292
Inline: False
```
**Symbols:**

```
ffffffff811b8240-ffffffff811b853e: stack_trace_call (STB_LOCAL)
ffffffff811b86ac-ffffffff811b86fe: stack_trace_call.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ftrace_regs *fregs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs *pt_regs</code>
</li>
</ul>
</details>
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
