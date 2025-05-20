# Function: <code>bpf_link_put</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200b1c)
Location: kernel/bpf/syscall.c:2328
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_release
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
  - kernel/bpf/syscall.c:link_update
```
**Symbols:**

```
ffffffff81200ce0-ffffffff81200d3e: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fffdc)
Location: kernel/bpf/syscall.c:2344
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_release
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:link_update
```
**Symbols:**

```
ffffffff812001b0-ffffffff8120020e: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8120098c)
Location: kernel/bpf/syscall.c:2352
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_release
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81200b60-ffffffff81200bbe: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812326fc)
Location: kernel/bpf/syscall.c:2462
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_release
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff812328d0-ffffffff8123292e: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81275aac)
Location: kernel/bpf/syscall.c:2710
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_release
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812759f0-ffffffff81275a72: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c73fc)
Location: kernel/bpf/syscall.c:2744
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_release
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812c6970-ffffffff812c69f2: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ed520)
Location: kernel/bpf/syscall.c:2857
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812ed520-ffffffff812ed581: bpf_link_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_put(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130c010)
Location: kernel/bpf/syscall.c:2921
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/mprog.c:bpf_mprog_detach
  - kernel/bpf/mprog.c:bpf_mprog_attach
  - kernel/bpf/mprog.c:bpf_mprog_tuple_relative
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff8130c010-ffffffff8130c071: bpf_link_put (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
