# Function: <code>copy_from_bpfptr_offset</code>

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
In kernel/bpf/syscall.c (ffffffff8123373c)
Location: include/linux/bpfptr.h:48
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff8123bc8f)
Location: include/linux/bpfptr.h:48
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_btf_line
```
```
In kernel/bpf/bpf_iter.c (ffffffff81252120)
Location: include/linux/bpfptr.h:48
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff8126868b)
Location: include/linux/bpfptr.h:48
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/syscall.c (ffffffff81276aa0)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff812817a7)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299e09)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff812b58e6)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/syscall.c (ffffffff812ccc42)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff812d9510)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5cce)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff8131a81a)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/syscall.c (ffffffff812f466a)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff81303500)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323a6e)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff81349ec2)
Location: include/linux/bpfptr.h:49
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
In kernel/bpf/syscall.c (ffffffff813135aa)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff81322fd3)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff813479fd)
Location: include/linux/bpfptr.h:49
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
```
```
In kernel/bpf/btf.c (ffffffff81370670)
Location: include/linux/bpfptr.h:49
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
