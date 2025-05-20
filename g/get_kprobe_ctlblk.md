# Function: <code>get_kprobe_ctlblk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105ecc6)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:jprobe_return
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8105ff55)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81060850)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105ed9e)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:jprobe_return
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8105fd55)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81060660)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061e4e)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:jprobe_return
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062df5)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81063700)
Location: include/linux/kprobes.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81060dee)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:jprobe_return
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81061d65)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81062670)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81064e3e)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:jprobe_return
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81066195)
Location: include/linux/kprobes.h:382
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810667ab)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81067a15)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:jprobe_return
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81068d54)
Location: include/linux/kprobes.h:382
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106935b)
Location: include/linux/kprobes.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106d896)
Location: include/linux/kprobes.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106eb64)
Location: include/linux/kprobes.h:360
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106f0fb)
Location: include/linux/kprobes.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810718d5)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072c04)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810731db)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107291c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073bf4)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107419b)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107999c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107aac4)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b2bb)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81194e07)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810799c2)
Location: include/linux/kprobes.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107a853)
Location: include/linux/kprobes.h:383
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b1b4)
Location: include/linux/kprobes.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81192e48)
Location: include/linux/kprobes.h:383
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107ad0c)
Location: include/linux/kprobes.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107ba56)
Location: include/linux/kprobes.h:383
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c3c0)
Location: include/linux/kprobes.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81193ce8)
Location: include/linux/kprobes.h:383
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81088ec5)
Location: include/linux/kprobes.h:377
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81089bc3)
Location: include/linux/kprobes.h:377
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a4ed)
Location: include/linux/kprobes.h:377
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff811bcba8)
Location: include/linux/kprobes.h:377
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8109917c)
Location: include/linux/kprobes.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a267)
Location: include/linux/kprobes.h:409
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109aa5d)
Location: include/linux/kprobes.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff811eeffa)
Location: include/linux/kprobes.h:409
Inline: True
Inline callers:
  - kernel/kprobes.c:kretprobe_rethook_handler
  - kernel/kprobes.c:kprobe_busy_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810af95c)
Location: include/linux/kprobes.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b0c07)
Location: include/linux/kprobes.h:412
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b149d)
Location: include/linux/kprobes.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8123579a)
Location: include/linux/kprobes.h:412
Inline: True
Inline callers:
  - kernel/kprobes.c:kretprobe_rethook_handler
  - kernel/kprobes.c:kprobe_busy_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b297c)
Location: include/linux/kprobes.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b39a7)
Location: include/linux/kprobes.h:412
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b445f)
Location: include/linux/kprobes.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8124c46a)
Location: include/linux/kprobes.h:412
Inline: True
Inline callers:
  - kernel/kprobes.c:kretprobe_rethook_handler
  - kernel/kprobes.c:kprobe_busy_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9ddc)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bae07)
Location: include/linux/kprobes.h:402
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb8bf)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8126636a)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - kernel/kprobes.c:kretprobe_rethook_handler
  - kernel/kprobes.c:kprobe_busy_begin
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/probes/kprobes.c (ffff800010da8054)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_single_step_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/kernel/probes/kprobes.c:arch_simulate_insn
  - arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/probes/kprobes/core.c (c0ea0ab8)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:trampoline_handler
  - arch/arm/probes/kprobes/core.c:kprobe_fault_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
```
```
In arch/arm/probes/kprobes/opt-arm.c (c0328440)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/opt-arm.c:optimized_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kprobes.c (c000000000056b8c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_fault_handler
  - arch/powerpc/kernel/kprobes.c:kprobe_post_handler
  - arch/powerpc/kernel/kprobes.c:kprobe_handler
```
```
In arch/powerpc/kernel/optprobes.c (c000000000057648)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/powerpc/kernel/kprobes-ftrace.c (c00000000006815c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes-ftrace.c:kprobe_ftrace_handler
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107191c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072bf4)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107319b)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106192c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062c74)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106321b)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810718cc)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072ba4)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107314b)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107392c)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074c04)
Location: include/linux/kprobes.h:348
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810751ab)
Location: include/linux/kprobes.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
</details>
</li>
</ul>

## Differences
