# Function: <code>__bpf_dynptr_size</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 __bpf_dynptr_size(const struct bpf_dynptr_kern *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff813219af)
Location: kernel/bpf/helpers.c:1446
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_size
  - kernel/bpf/helpers.c:bpf_dynptr_adjust
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - kernel/bpf/helpers.c:bpf_dynptr_data
  - kernel/bpf/helpers.c:bpf_dynptr_write
  - kernel/bpf/helpers.c:bpf_dynptr_read
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81320470-ffffffff81320489: __bpf_dynptr_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 __bpf_dynptr_size(const struct bpf_dynptr_kern *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8134415f)
Location: kernel/bpf/helpers.c:1465
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_size
  - kernel/bpf/helpers.c:bpf_dynptr_adjust
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - kernel/bpf/helpers.c:bpf_dynptr_data
  - kernel/bpf/helpers.c:bpf_dynptr_write
  - kernel/bpf/helpers.c:bpf_dynptr_read
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/verity/measure.c:bpf_get_fsverity_digest
```
**Symbols:**

```
ffffffff81342970-ffffffff81342989: __bpf_dynptr_size (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
