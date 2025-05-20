# Function: <code>start_backtrace</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089658)
Location: arch/arm64/include/asm/stacktrace.h:162
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:get_wchan
```
```
In arch/arm64/kernel/stacktrace.c (ffff800010093c10)
Location: arch/arm64/include/asm/stacktrace.h:162
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:__save_stack_trace
  - arch/arm64/kernel/stacktrace.c:__save_stack_trace
  - arch/arm64/kernel/stacktrace.c:save_stack_trace_regs
```
```
In arch/arm64/kernel/time.c (ffff800010093d74)
Location: arch/arm64/include/asm/stacktrace.h:162
Inline: True
```
```
In arch/arm64/kernel/traps.c (ffff8000100942f8)
Location: arch/arm64/include/asm/stacktrace.h:162
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:dump_backtrace
  - arch/arm64/kernel/traps.c:dump_backtrace
```
```
In arch/arm64/kernel/return_address.c (0)
Location: arch/arm64/include/asm/stacktrace.h:162
Inline: True
Inline callers:
  - arch/arm64/kernel/return_address.c:return_address
```
```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a397c)
Location: arch/arm64/include/asm/stacktrace.h:162
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_kernel
```
</details>
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
