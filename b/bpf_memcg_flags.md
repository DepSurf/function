# Function: <code>bpf_memcg_flags</code>

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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e87a5)
Location: include/linux/bpf.h:3073
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffffffff812ebaa5)
Location: include/linux/bpf.h:3073
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
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
In kernel/bpf/core.c (ffffffff81306b15)
Location: include/linux/bpf.h:3263
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_jited_linfo
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffffffff81309ff5)
Location: include/linux/bpf.h:3263
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
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
