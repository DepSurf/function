# Function: <code>__arm_gen_branch</code>

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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __arm_gen_branch(long unsigned int pc, long unsigned int addr, bool link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/insn.c (c0315004)
Location: arch/arm/kernel/insn.c:57
Inline: False
Direct callers:
  - arch/arm/kernel/ftrace.c:__ftrace_modify_caller
  - arch/arm/kernel/ftrace.c:ftrace_make_nop
  - arch/arm/kernel/ftrace.c:ftrace_modify_call
  - arch/arm/kernel/ftrace.c:ftrace_modify_call
  - arch/arm/kernel/ftrace.c:ftrace_make_call
  - arch/arm/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/arm/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/arm/probes/kprobes/opt-arm.c:arch_optimize_kprobes
  - arch/arm/probes/kprobes/opt-arm.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
c0315004-c0315084: __arm_gen_branch (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
