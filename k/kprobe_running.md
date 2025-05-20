# Function: <code>kprobe_running</code>

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
In arch/x86/kernel/kprobes/core.c (ffffffff8105edec)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8105ff81)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106085f)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8106b407)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/kprobes/core.c (ffffffff8105ed5f)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8105fd81)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106066f)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8106b21b)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/kprobes/core.c (ffffffff81061d6f)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062e21)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106370f)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8106ee2b)
Location: include/linux/kprobes.h:351
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/kprobes/core.c (ffffffff81060d0f)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81061d92)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:optimized_callback
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106267f)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8106e59b)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/kprobes/core.c (ffffffff81064d70)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106617f)
Location: include/linux/kprobes.h:372
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810667ba)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8107364a)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106794f)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_exceptions_notify
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81068d3f)
Location: include/linux/kprobes.h:372
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106936a)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff81075f9a)
Location: include/linux/kprobes.h:372
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/traps.c (ffffffff8102f8ca)
Location: include/linux/kprobes.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106d885)
Location: include/linux/kprobes.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106eb4f)
Location: include/linux/kprobes.h:350
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106f10a)
Location: include/linux/kprobes.h:350
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8107c377)
Location: include/linux/kprobes.h:350
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/traps.c (ffffffff810316ba)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810718c5)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072bef)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810731ea)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8107f960)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/kernel/traps.c (ffffffff81031f7a)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072905)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073bdf)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810741aa)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff810809f0)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/kernel/traps.c (ffffffff81bbd23c)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079985)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107aaaf)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b2ca)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff810878a7)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_kern_addr_fault
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
In arch/x86/kernel/traps.c (ffffffff81c358fd)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810799a5)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107a83f)
Location: include/linux/kprobes.h:373
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b1c3)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff81088003)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/kprobes.c (ffffffff8119364a)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - kernel/kprobes.c:__kretprobe_trampoline_handler
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
In arch/x86/kernel/traps.c (ffffffff81c27d8d)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107acf5)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107ba42)
Location: include/linux/kprobes.h:373
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c3cf)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff81088ac3)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/kprobes.c (ffffffff811945fa)
Location: include/linux/kprobes.h:373
Inline: True
Inline callers:
  - kernel/kprobes.c:__kretprobe_trampoline_handler
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
In arch/x86/kernel/traps.c (ffffffff81d45e2d)
Location: include/linux/kprobes.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81088eb5)
Location: include/linux/kprobes.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81089baf)
Location: include/linux/kprobes.h:367
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a4fc)
Location: include/linux/kprobes.h:367
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff81097ef3)
Location: include/linux/kprobes.h:367
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/kprobes.c (ffffffff811bd49a)
Location: include/linux/kprobes.h:367
Inline: True
Inline callers:
  - kernel/kprobes.c:__kretprobe_trampoline_handler
```
```
In kernel/trace/bpf_trace.c (ffffffff81217e10)
Location: include/linux/kprobes.h:367
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_func_ip_kprobe
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
In arch/x86/kernel/traps.c (ffffffff81042612)
Location: include/linux/kprobes.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81099165)
Location: include/linux/kprobes.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a25a)
Location: include/linux/kprobes.h:399
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109aa74)
Location: include/linux/kprobes.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff810aab45)
Location: include/linux/kprobes.h:399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/trace/bpf_trace.c (ffffffff81255c50)
Location: include/linux/kprobes.h:399
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_func_ip_kprobe
```
```
In kernel/trace/fprobe.c (ffffffff81268b74)
Location: include/linux/kprobes.h:399
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff8104bf92)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810af945)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b0bfa)
Location: include/linux/kprobes.h:402
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b14b4)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff810c4835)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/trace/bpf_trace.c (ffffffff812a5190)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_func_ip_kprobe
```
```
In kernel/trace/fprobe.c (ffffffff812bae14)
Location: include/linux/kprobes.h:402
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff8104c803)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2965)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b399a)
Location: include/linux/kprobes.h:402
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b4476)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff810c8035)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/trace/bpf_trace.c (ffffffff812c7640)
Location: include/linux/kprobes.h:402
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_func_ip_kprobe
```
```
In kernel/trace/fprobe.c (ffffffff812ddf60)
Location: include/linux/kprobes.h:402
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff81053a83)
Location: include/linux/kprobes.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:gp_try_fixup_and_notify
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9dc5)
Location: include/linux/kprobes.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810badfa)
Location: include/linux/kprobes.h:392
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb8d6)
Location: include/linux/kprobes.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff810d0509)
Location: include/linux/kprobes.h:392
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5917)
Location: include/linux/kprobes.h:392
Inline: True
```
```
In kernel/trace/fprobe.c (ffffffff812fc050)
Location: include/linux/kprobes.h:392
Inline: True
```
</details>
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
In arch/arm64/kernel/probes/kprobes.c (ffff800010da8074)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler
```
```
In arch/arm64/mm/fault.c (ffff800010da8ff8)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
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
In arch/arm/mm/fault.c (c0e9f858)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
```
In arch/arm/probes/kprobes/core.c (c0ea082c)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:kprobe_fault_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
```
```
In arch/arm/probes/kprobes/opt-arm.c (c032845c)
Location: include/linux/kprobes.h:338
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
In arch/powerpc/kernel/kprobes.c (c000000000056b60)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_fault_handler
  - arch/powerpc/kernel/kprobes.c:kprobe_post_handler
  - arch/powerpc/kernel/kprobes.c:kprobe_handler
  - arch/powerpc/kernel/kprobes.c:kprobe_handler
```
```
In arch/powerpc/kernel/optprobes.c (c0000000000575f0)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/powerpc/kernel/kprobes-ftrace.c (c000000000068170)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes-ftrace.c:kprobe_ftrace_handler
```
```
In arch/powerpc/mm/fault.c (c0000000000863a0)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
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
In arch/x86/kernel/traps.c (ffffffff810320da)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071905)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072bdf)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810731aa)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8107f9f0)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/kernel/traps.c (ffffffff810217b7)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061915)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062c5f)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106322a)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8106ea5f)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/kernel/traps.c (ffffffff81031f3a)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810718b5)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072b8f)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107315a)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff8107f9a0)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/kernel/traps.c (ffffffff81032e1c)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073915)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:kprobe_debug_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074be6)
Location: include/linux/kprobes.h:338
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810751ba)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/mm/fault.c (ffffffff81081981)
Location: include/linux/kprobes.h:338
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
</ul>

## Differences
