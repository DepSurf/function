# Function: <code>make_bpfptr</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81231a1e)
Location: include/linux/bpfptr.h:25
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff8124d896)
Location: include/linux/bpfptr.h:25
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251fcd)
Location: include/linux/bpfptr.h:25
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff8126a5b5)
Location: include/linux/bpfptr.h:25
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/syscall.c (ffffffff81274cf1)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff81294808)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299ca6)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff812b73d5)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/syscall.c (ffffffff812ca131)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff812ef3c0)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5b40)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff8131ab75)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/syscall.c (ffffffff812f1bcb)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff8131bd9b)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff813238e0)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff81349dbb)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/syscall.c (ffffffff81310a3d)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff8133e136)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347840)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff8137050b)
Location: include/linux/bpfptr.h:26
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
