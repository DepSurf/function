# Function: <code>bpf_bprintf_cleanup</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_bprintf_cleanup();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81219fa2)
Location: kernel/bpf/helpers.c:727
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
**Symbols:**

```
ffffffff812198b0-ffffffff812198cd: bpf_bprintf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_bprintf_cleanup();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81250bb2)
Location: kernel/bpf/helpers.c:741
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
**Symbols:**

```
ffffffff81250490-ffffffff812504ad: bpf_bprintf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_bprintf_cleanup();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812982ed)
Location: kernel/bpf/helpers.c:802
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
**Symbols:**

```
ffffffff81297b30-ffffffff81297b68: bpf_bprintf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_bprintf_cleanup();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f349d)
Location: kernel/bpf/helpers.c:787
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
**Symbols:**

```
ffffffff812f2cc0-ffffffff812f2cf8: bpf_bprintf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_bprintf_cleanup(struct bpf_bprintf_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131fa00)
Location: kernel/bpf/helpers.c:788
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff8131fa00-ffffffff8131fa5d: bpf_bprintf_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_bprintf_cleanup(struct bpf_bprintf_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81341ef0)
Location: kernel/bpf/helpers.c:794
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
**Symbols:**

```
ffffffff81341ef0-ffffffff81341f4d: bpf_bprintf_cleanup (STB_GLOBAL)
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
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
