# Function: <code>KERNEL_BPFPTR</code>

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
In kernel/bpf/syscall.c (ffffffff812344bd)
Location: include/linux/bpfptr.h:15
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_sys_bpf
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:15
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff812520e9)
Location: include/linux/bpfptr.h:15
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:15
Inline: True
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
In kernel/bpf/syscall.c (ffffffff812778d4)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299dd5)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
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
In kernel/bpf/syscall.c (ffffffff812cdc64)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5c9a)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
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
In kernel/bpf/syscall.c (ffffffff812f51c5)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323a3a)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
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
In kernel/bpf/syscall.c (ffffffff81313fc5)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_sys_bpf
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff813479c9)
Location: include/linux/bpfptr.h:16
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:16
Inline: True
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
