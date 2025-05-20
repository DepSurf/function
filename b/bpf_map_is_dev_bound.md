# Function: <code>bpf_map_is_dev_bound</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4d13)
Location: include/linux/bpf.h:661
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811bebec)
Location: include/linux/bpf.h:661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/offload.c (ffffffff811cc20a)
Location: include/linux/bpf.h:661
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c4d06)
Location: include/linux/bpf.h:744
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
```
In kernel/bpf/verifier.c (ffffffff811cf8af)
Location: include/linux/bpf.h:744
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/offload.c (ffffffff811e0325)
Location: include/linux/bpf.h:744
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6317)
Location: include/linux/bpf.h:922
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811d94e1)
Location: include/linux/bpf.h:922
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffffffff811f5ee5)
Location: include/linux/bpf.h:922
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e29f3)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811e5be1)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffffffff81202ef5)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff5c8)
Location: include/linux/bpf.h:1511
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81205401)
Location: include/linux/bpf.h:1511
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff8122a4d5)
Location: include/linux/bpf.h:1511
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe968)
Location: include/linux/bpf.h:1733
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff8120607b)
Location: include/linux/bpf.h:1733
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff81232065)
Location: include/linux/bpf.h:1733
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fded6)
Location: include/linux/bpf.h:1823
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81207fae)
Location: include/linux/bpf.h:1823
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff812361e5)
Location: include/linux/bpf.h:1823
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122ee70)
Location: include/linux/bpf.h:1949
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff8123b894)
Location: include/linux/bpf.h:1949
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff81270435)
Location: include/linux/bpf.h:1949
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
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
In kernel/bpf/syscall.c (ffffffff812717ff)
Location: include/linux/bpf.h:2088
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff812813cb)
Location: include/linux/bpf.h:2088
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff812bf525)
Location: include/linux/bpf.h:2088
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
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
In kernel/bpf/syscall.c (ffffffff812c7a26)
Location: include/linux/bpf.h:2496
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
In kernel/bpf/verifier.c (ffffffff812d91a0)
Location: include/linux/bpf.h:2496
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
```
In kernel/bpf/offload.c (ffffffff81322c45)
Location: include/linux/bpf.h:2496
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010265138)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffff800010268f3c)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffff80001028b4e4)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0497b9c)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (c049b2c4)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (c04bacb0)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c00000000030aa1c)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (c00000000030eb84)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (c000000000337448)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:924
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:924
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:924
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811db013)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811de201)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffffffff811fb515)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cddd3)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811d0fc1)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffffffff811ee265)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8de3)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811dbfd1)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffffffff811f92e5)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e71ef)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffffffff811ea3e1)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
```
In kernel/bpf/offload.c (ffffffff81207d85)
Location: include/linux/bpf.h:924
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
```
</details>
</li>
</ul>

## Differences
