# Function: <code>bpf_get_trace_vprintk_proto</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct bpf_func_proto *bpf_get_trace_vprintk_proto();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81258788)
Location: kernel/trace/bpf_trace.c:465
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
Direct callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
**Symbols:**

```
ffffffff81e6831f-ffffffff81e68330: bpf_get_trace_vprintk_proto.cold (STB_LOCAL)
ffffffff812593c0-ffffffff81259421: bpf_get_trace_vprintk_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_get_trace_vprintk_proto();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a8561)
Location: kernel/trace/bpf_trace.c:468
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
Direct callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
**Symbols:**

```
ffffffff812a93e0-ffffffff812a9449: bpf_get_trace_vprintk_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_get_trace_vprintk_proto();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cae99)
Location: kernel/trace/bpf_trace.c:464
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
Direct callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
**Symbols:**

```
ffffffff812cbbf0-ffffffff812cbc59: bpf_get_trace_vprintk_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_get_trace_vprintk_proto();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e8139)
Location: kernel/trace/bpf_trace.c:464
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
Direct callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
**Symbols:**

```
ffffffff812e8f00-ffffffff812e8f69: bpf_get_trace_vprintk_proto (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
