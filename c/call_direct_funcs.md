# Function: <code>call_direct_funcs</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af680)
Location: kernel/trace/ftrace.c:2371
Inline: False
```
**Symbols:**

```
ffffffff811af680-ffffffff811af697: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad030)
Location: kernel/trace/ftrace.c:2391
Inline: False
```
**Symbols:**

```
ffffffff811ad030-ffffffff811ad05d: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811adad0)
Location: kernel/trace/ftrace.c:2397
Inline: False
```
**Symbols:**

```
ffffffff811adad0-ffffffff811adafa: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d7880)
Location: kernel/trace/ftrace.c:2398
Inline: False
```
**Symbols:**

```
ffffffff811d7880-ffffffff811d78af: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120cee0)
Location: kernel/trace/ftrace.c:2442
Inline: False
```
**Symbols:**

```
ffffffff8120cee0-ffffffff8120cf19: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81255a80)
Location: kernel/trace/ftrace.c:2493
Inline: False
```
**Symbols:**

```
ffffffff81255a80-ffffffff81255aa6: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812686d0)
Location: kernel/trace/ftrace.c:2591
Inline: False
```
**Symbols:**

```
ffffffff812686d0-ffffffff812686eb: call_direct_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void call_direct_funcs(long unsigned int ip, long unsigned int pip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81282940)
Location: kernel/trace/ftrace.c:2557
Inline: False
```
**Symbols:**

```
ffffffff81282940-ffffffff8128295b: call_direct_funcs (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ftrace_regs *fregs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs *regs</code>
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
