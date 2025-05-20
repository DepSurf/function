# Function: <code>__ftrace_modify_call</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/trace/ftrace.c (c000000000073ae0)
Location: arch/powerpc/kernel/trace/ftrace.c:700
Inline: True
Inline callers:
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_call
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ftrace_modify_call(long unsigned int hook_pos, long unsigned int target, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/ftrace.c (ffffffe0000b8f0c)
Location: arch/riscv/kernel/ftrace.c:44
Inline: False
Direct callers:
  - arch/riscv/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/riscv/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/riscv/kernel/ftrace.c:ftrace_modify_call
  - arch/riscv/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/riscv/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/riscv/kernel/ftrace.c:ftrace_make_nop
  - arch/riscv/kernel/ftrace.c:ftrace_make_call
```
**Symbols:**

```
ffffffe0000b8f0c-ffffffe0000b8f8c: __ftrace_modify_call (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
