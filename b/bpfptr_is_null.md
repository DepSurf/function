# Function: <code>bpfptr_is_null</code>

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
In kernel/bpf/syscall.c (0)
Location: include/linux/bpfptr.h:33
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8123bc78)
Location: include/linux/bpfptr.h:33
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251fdc)
Location: include/linux/bpfptr.h:33
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
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
In kernel/bpf/syscall.c (ffffffff812719c6)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff81281790)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299cb5)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
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
In kernel/bpf/syscall.c (ffffffff812c7571)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff812d94f9)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f5b4f)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
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
In kernel/bpf/syscall.c (ffffffff812eea44)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff813034e9)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff813238ef)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
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
In kernel/bpf/syscall.c (ffffffff8130d7f3)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/verifier.c (ffffffff81322fbc)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
```
In kernel/bpf/bpf_iter.c (ffffffff8134784f)
Location: include/linux/bpfptr.h:34
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
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
