# Function: <code>strncpy_from_kernel_nofault</code>

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
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81258260)
Location: mm/maccess.c:65
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81258260-ffffffff81258310: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81262a90)
Location: mm/maccess.c:65
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81262a90-ffffffff81262b40: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812674b0)
Location: mm/maccess.c:65
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff812674b0-ffffffff8126755e: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812a3ef0)
Location: mm/maccess.c:81
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_filter.c:filter_pred_pchar
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff812a3ef0-ffffffff812a3f9e: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812fbf60)
Location: mm/maccess.c:79
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_filter.c:filter_pred_pchar
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff812fbf60-ffffffff812fc036: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81366190)
Location: mm/maccess.c:79
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff81366190-ffffffff81366265: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81398630)
Location: mm/maccess.c:80
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff81398630-ffffffff81398707: strncpy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int strncpy_from_kernel_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813c2430)
Location: mm/maccess.c:80
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff813c2430-ffffffff813c2507: strncpy_from_kernel_nofault (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
