# Function: <code>bpf_bprintf_prepare</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_bprintf_prepare(char *fmt, u32 fmt_size, const u64 *raw_args, u32 **bin_args, u32 num_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812198d0)
Location: kernel/bpf/helpers.c:749
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/helpers.c:bpf_snprintf
```
**Symbols:**

```
ffffffff812198d0-ffffffff81219f0a: bpf_bprintf_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_bprintf_prepare(char *fmt, u32 fmt_size, const u64 *raw_args, u32 **bin_args, u32 num_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812504b0)
Location: kernel/bpf/helpers.c:763
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/helpers.c:bpf_snprintf
```
**Symbols:**

```
ffffffff812504b0-ffffffff81250b15: bpf_bprintf_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_bprintf_prepare(char *fmt, u32 fmt_size, const u64 *raw_args, u32 **bin_args, u32 num_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81297b70)
Location: kernel/bpf/helpers.c:824
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/helpers.c:bpf_snprintf
```
**Symbols:**

```
ffffffff81297b70-ffffffff8129823d: bpf_bprintf_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_bprintf_prepare(char *fmt, u32 fmt_size, const u64 *raw_args, u32 **bin_args, u32 num_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f2d10)
Location: kernel/bpf/helpers.c:809
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/helpers.c:bpf_snprintf
```
**Symbols:**

```
ffffffff812f2d10-ffffffff812f33dc: bpf_bprintf_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_bprintf_prepare(char *fmt, u32 fmt_size, const u64 *raw_args, u32 num_args, struct bpf_bprintf_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:812
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/helpers.c:bpf_snprintf
```
**Symbols:**

```
ffffffff820e08e7-ffffffff820e097a: bpf_bprintf_prepare.cold (STB_LOCAL)
ffffffff8131fa70-ffffffff81320262: bpf_bprintf_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_bprintf_prepare(char *fmt, u32 fmt_size, const u64 *raw_args, u32 num_args, struct bpf_bprintf_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:818
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/helpers.c:bpf_snprintf
```
**Symbols:**

```
ffffffff821bcfe0-ffffffff821bd073: bpf_bprintf_prepare.cold (STB_LOCAL)
ffffffff81341f60-ffffffff81342752: bpf_bprintf_prepare (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_bprintf_data *data</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 **bin_args</code>
</li>
<li>
<b>Param reordered. </b>
<code>fmt, fmt_size, raw_args, bin_args, num_args</code> ➡️ <code>fmt, fmt_size, raw_args, num_args, data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
