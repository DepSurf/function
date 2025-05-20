# Function: <code>perf_event_text_poke</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124cc60)
Location: kernel/events/core.c:8870
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff8124cc60-ffffffff8124cced: perf_event_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812512c0)
Location: kernel/events/core.c:8999
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff812512c0-ffffffff8125134e: perf_event_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c0c0)
Location: kernel/events/core.c:9118
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff8128c0c0-ffffffff8128c14e: perf_event_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0a70)
Location: kernel/events/core.c:9023
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff812e0a70-ffffffff812e0b33: perf_event_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81348ef0)
Location: kernel/events/core.c:9300
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff81348ef0-ffffffff81348fb3: perf_event_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137a030)
Location: kernel/events/core.c:9328
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff8137a030-ffffffff8137a0f3: perf_event_text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_text_poke(const void *addr, const void *old_bytes, size_t old_len, const void *new_bytes, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a32f0)
Location: kernel/events/core.c:9398
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - kernel/trace/ftrace.c:ftrace_trampoline_free
```
**Symbols:**

```
ffffffff813a32f0-ffffffff813a33b3: perf_event_text_poke (STB_GLOBAL)
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
