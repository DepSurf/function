# Function: <code>bpf_map_is_offloaded</code>

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
In kernel/bpf/syscall.c (ffffffff812eedfa)
Location: include/linux/bpf.h:2684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_update_value
```
```
In kernel/bpf/verifier.c (ffffffff81303148)
Location: include/linux/bpf.h:2684
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff81352cd5)
Location: include/linux/bpf.h:2684
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
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
In kernel/bpf/syscall.c (ffffffff8130dbba)
Location: include/linux/bpf.h:2855
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/syscall.c:bpf_map_update_value
```
```
In kernel/bpf/verifier.c (ffffffff81322c47)
Location: include/linux/bpf.h:2855
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff8137a1b5)
Location: include/linux/bpf.h:2855
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
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
