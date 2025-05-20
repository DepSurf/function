# Function: <code>bpf_type_has_unsafe_modifiers</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e9da1)
Location: include/linux/bpf_verifier.h:686
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f2cb63)
Location: include/linux/bpf_verifier.h:686
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
In kernel/bpf/verifier.c (ffffffff8131596b)
Location: include/linux/bpf_verifier.h:750
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f8c803)
Location: include/linux/bpf_verifier.h:750
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
In kernel/bpf/verifier.c (ffffffff8132f8c1)
Location: include/linux/bpf_verifier.h:852
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff8205a003)
Location: include/linux/bpf_verifier.h:852
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
