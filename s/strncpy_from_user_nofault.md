# Function: <code>strncpy_from_user_nofault</code>

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
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81258310)
Location: mm/maccess.c:270
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81258310-ffffffff812583d6: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81262b40)
Location: mm/maccess.c:268
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81262b40-ffffffff81262ba3: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81267560)
Location: mm/maccess.c:268
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff81267560-ffffffff812675c3: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812a3fa0)
Location: mm/maccess.c:284
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:filter_pred_pchar_user
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff812a3fa0-ffffffff812a4003: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812fc040)
Location: mm/maccess.c:171
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:filter_pred_pchar_user
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff812fc040-ffffffff812fc0c1: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81366280)
Location: mm/maccess.c:171
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff81366280-ffffffff81366301: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81398720)
Location: mm/maccess.c:177
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff81398720-ffffffff813987a1: strncpy_from_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int strncpy_from_user_nofault(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813c2520)
Location: mm/maccess.c:177
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_user_str
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff813c2520-ffffffff813c25a1: strncpy_from_user_nofault (STB_GLOBAL)
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
