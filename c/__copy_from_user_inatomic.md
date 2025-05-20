# Function: <code>__copy_from_user_inatomic</code>

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
In arch/x86/kernel/stacktrace.c (ffffffff8103e707)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/futex.c (ffffffff8110018a)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
```
```
In kernel/trace/trace_kprobe.c (ffffffff811674bb)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff81188d4d)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff8119153b)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (ffffffff811bc8e9)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff813f78ee)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
```
```
In lib/iov_iter.c (ffffffff813fc847)
Location: arch/x86/include/asm/uaccess_64.h:205
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
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
In arch/x86/events/core.c (ffffffff810078a2)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e54f)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174a72)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811a5d05)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811d7657)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e77f)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
```
```
In lib/iov_iter.c (ffffffff81444694)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
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
In arch/x86/events/core.c (ffffffff81007928)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103deaf)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/trace/trace.c (ffffffff8115e79b)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811804f2)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811b6085)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811e735e)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b75f)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
```
```
In lib/iov_iter.c (ffffffff8146280d)
Location: arch/x86/include/asm/uaccess_64.h:248
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
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
In arch/x86/events/core.c (ffffffff810076b8)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf2c)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/trace/trace.c (ffffffff811619cb)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff81182fe8)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811be001)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811f24a0)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff818fd4cb)
Location: include/linux/uaccess.h:61
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81007aee)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb20)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/trace/trace.c (ffffffff8116e24b)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c4d)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811d2cc2)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81209464)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81984fab)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008127)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81040101)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/trace/trace.c (ffffffff8117d260)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6182)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In mm/maccess.c (ffffffff811f4042)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8122a372)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff819e1497)
Location: include/linux/uaccess.h:62
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008007)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810416c1)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In kernel/trace/trace.c (ffffffff8118aad0)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812063d2)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8123d9b6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c447)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008301)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043bc6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In kernel/trace/trace.c (ffffffff81198722)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8121d893)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8124f660)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c0f6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008519)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044316)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In kernel/trace/trace.c (ffffffff811a4012)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8122b333)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8125dbef)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac33b6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In kernel/trace/trace.c (ffffffff811bd442)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81257fe0)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8128d2fd)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff815ff8f9)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In kernel/trace/trace.c (ffffffff811bb052)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81262932)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff812982df)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/insn-eval.c (ffffffff816236a5)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81624829)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In kernel/trace/trace.c (ffffffff811be839)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812672d1)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8129d92f)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606f55)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81608219)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In kernel/trace/trace.c (ffffffff811e90ed)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812a3d11)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff812ddfc4)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/insn-eval.c (ffffffff81675a68)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e59)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In kernel/trace/trace.c (ffffffff81220db8)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812fbc4a)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8133e054)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/insn-eval.c (ffffffff817906e8)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81791dfe)
Location: include/linux/uaccess.h:59
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
In kernel/trace/trace.c (ffffffff8126bc58)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81365e1a)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff813b7170)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204e2f8)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
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
In kernel/trace/trace.c (ffffffff81282fb8)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff813982b9)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff813e98fb)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff820ccb8f)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
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
In kernel/trace/trace.c (ffffffff8129e349)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff813c20e9)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff814148f1)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a73bf)
Location: include/linux/uaccess.h:81
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
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
In arch/arm64/kernel/perf_callchain.c (ffff8000100a3570)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In virt/kvm/kvm_main.c (ffff8000100bde24)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
```
```
In kernel/trace/trace.c (ffff800010221e38)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (ffff800010298550)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In mm/maccess.c (ffff8000102b9a60)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffff8000102f51b8)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffff80001062f9f4)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
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
In arch/arm/kernel/perf_callchain.c (c0317ce4)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
```
```
In kernel/trace/trace.c (c045f8e4)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (c04ceba0)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/maccess.c (c04e5be4)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (c05172f4)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (c07d6410)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
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
In arch/powerpc/kernel/traps.c (c00000000002cd40)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:p9_hmi_special_emu
```
```
In kernel/trace/trace.c (c0000000002a72e0)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (c000000000342838)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In mm/maccess.c (c000000000371958)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (c0000000003bc144)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (c0000000007d834c)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/perf_callchain.c (ffffffe0000b98d4)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_callchain.c:user_backtrace
```
```
In kernel/trace/trace.c (ffffffe00017d658)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (ffffffe0001ce9b6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/maccess.c (ffffffe0001dd020)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffe00020651c)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In lib/iov_iter.c (ffffffe00045edd8)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
```
</details>
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
In arch/x86/events/core.c (ffffffff81008519)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044496)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In kernel/trace/trace.c (ffffffff8119c632)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81223983)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8125623f)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81a62206)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81006d09)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81033ab6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In kernel/trace/trace.c (ffffffff8118f6ac)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81216b33)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff812488d8)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f276)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff810084d9)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810442d6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In kernel/trace/trace.c (ffffffff8119a402)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81221723)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81253fdf)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace5f6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (ffffffff81008639)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810456d6)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In kernel/trace/trace.c (ffffffff811a80a2)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812308e3)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81263a34)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In arch/x86/lib/usercopy.c (ffffffff81adab06)
Location: include/linux/uaccess.h:59
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
</ul>

## Differences
