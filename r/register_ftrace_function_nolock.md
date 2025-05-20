# Function: <code>register_ftrace_function_nolock</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125c095)
Location: kernel/trace/ftrace.c:8214
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi_nolock
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff8125afa0-ffffffff8125b00a: register_ftrace_function_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81272c76)
Location: kernel/trace/ftrace.c:8029
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct_nolock
  - kernel/trace/ftrace.c:register_ftrace_direct
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
```
**Symbols:**

```
ffffffff81272440-ffffffff812724aa: register_ftrace_function_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int register_ftrace_function_nolock(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128d4fe)
Location: kernel/trace/ftrace.c:8029
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct_nolock
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff8128c930-ffffffff8128c99a: register_ftrace_function_nolock (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
