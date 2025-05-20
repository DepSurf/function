# Function: <code>ppc_function_entry</code>

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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c0000000000221d4)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:copy_thread_tls
```
```
In arch/powerpc/kernel/setup_64.c (c000000000031208)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:smp_release_cpus
```
```
In arch/powerpc/kernel/kprobes.c (c0000000000574f0)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_lookup_name
```
```
In arch/powerpc/kernel/optprobes.c (c000000000057af4)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
```
```
In arch/powerpc/kernel/trace/ftrace.c (c000000000074000)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/kernel/trace/ftrace.c:prepare_ftrace_return
  - arch/powerpc/kernel/trace/ftrace.c:test_24bit_addr
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_call_replace
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000ce2f8)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_kick_cpu
```
```
In arch/powerpc/platforms/pseries/smp.c (c0000000000f8690)
Location: arch/powerpc/include/asm/code-patching.h:79
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
```
</details>
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
