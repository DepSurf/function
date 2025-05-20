# Function: <code>btf_id_set8_contains</code>

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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131ad8f)
Location: include/linux/btf.h:465
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_kfunc_is_modify_return
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
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
In kernel/bpf/btf.c (ffffffff81339117)
Location: include/linux/btf.h:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:__btf_kfunc_id_set_contains
```
```
In net/core/filter.c (ffffffff81e67fc9)
Location: include/linux/btf.h:481
Inline: True
Inline callers:
  - net/core/filter.c:tracing_iter_filter
```
```
In net/core/xdp.c (ffffffff81e79c98)
Location: include/linux/btf.h:481
Inline: True
Inline callers:
  - net/core/xdp.c:bpf_dev_bound_kfunc_id
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
In kernel/trace/bpf_trace.c (ffffffff812e5b64)
Location: include/linux/btf.h:492
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr_filter
```
```
In kernel/bpf/btf.c (ffffffff8135f247)
Location: include/linux/btf.h:492
Inline: True
Inline callers:
  - kernel/bpf/btf.c:__btf_kfunc_id_set_contains
```
```
In fs/verity/measure.c (ffffffff81571bb9)
Location: include/linux/btf.h:492
Inline: True
Inline callers:
  - fs/verity/measure.c:bpf_get_fsverity_digest_filter
```
```
In net/core/filter.c (ffffffff81f27199)
Location: include/linux/btf.h:492
Inline: True
Inline callers:
  - net/core/filter.c:tracing_iter_filter
```
```
In net/core/xdp.c (ffffffff81f39de8)
Location: include/linux/btf.h:492
Inline: True
Inline callers:
  - net/core/xdp.c:bpf_dev_bound_kfunc_id
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
