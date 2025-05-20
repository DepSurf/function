# Function: <code>USER_BPFPTR</code>

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
In kernel/bpf/syscall.c (ffffffff812344f1)
Location: include/linux/bpfptr.h:20
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:20
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251fd6)
Location: include/linux/bpfptr.h:20
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:20
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81b2a3f3)
Location: include/linux/bpfptr.h:20
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_init
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
In kernel/bpf/syscall.c (ffffffff81277a41)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299caf)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81cb373f)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_init
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
In kernel/bpf/syscall.c (ffffffff812cdde1)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5b49)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81e7197f)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_init
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
In kernel/bpf/syscall.c (ffffffff812f5371)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff813238e9)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81ecdc7f)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_init
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
In kernel/bpf/syscall.c (ffffffff81314171)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347849)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/bpfptr.h:21
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81f914af)
Location: include/linux/bpfptr.h:21
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_init
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
