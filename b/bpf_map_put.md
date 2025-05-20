# Function: <code>bpf_map_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172e80)
Location: kernel/bpf/syscall.c:96
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81172e80-ffffffff81172ec8: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180dc0)
Location: kernel/bpf/syscall.c:111
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81180dc0-ffffffff81180e08: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118ce40)
Location: kernel/bpf/syscall.c:139
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8118ce40-ffffffff8118ce88: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811933fc)
Location: kernel/bpf/syscall.c:191
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
**Symbols:**

```
ffffffff81191db0-ffffffff81191dc5: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a1253)
Location: kernel/bpf/syscall.c:241
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
**Symbols:**

```
ffffffff8119f490-ffffffff8119f4a5: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b55eb)
Location: kernel/bpf/syscall.c:287
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
**Symbols:**

```
ffffffff811b4fe0-ffffffff811b4ff5: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c57d4)
Location: kernel/bpf/syscall.c:315
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
**Symbols:**

```
ffffffff811c33b0-ffffffff811c33c5: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5d99)
Location: kernel/bpf/syscall.c:333
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
```
**Symbols:**

```
ffffffff811d4100-ffffffff811d4115: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e1f88)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff811e0490-ffffffff811e04a5: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe980)
Location: kernel/bpf/syscall.c:490
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/core.c:__bpf_free_used_maps
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff811fca60-ffffffff811fcb0c: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff193)
Location: kernel/bpf/syscall.c:484
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff811fbe60-ffffffff811fbe70: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffc23)
Location: kernel/bpf/syscall.c:485
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_delete_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff811fcba0-ffffffff811fcbb0: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812318d3)
Location: kernel/bpf/syscall.c:504
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put_rcu
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff8122e6e0-ffffffff8122e6f0: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81274b6f)
Location: kernel/bpf/syscall.c:625
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put_rcu
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff81270ce0-ffffffff81270cf6: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6e6f)
Location: kernel/bpf/syscall.c:725
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put_rcu
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff812c6d00-ffffffff812c6d16: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ec900)
Location: kernel/bpf/syscall.c:722
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_dealloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff812ec900-ffffffff812ec9c9: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130b030)
Location: kernel/bpf/syscall.c:750
Inline: True
Direct callers:
  - kernel/bpf/core.c:__bpf_free_used_maps
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_dealloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
**Symbols:**

```
ffffffff821ba5d3-ffffffff821ba5fd: bpf_map_put.cold (STB_LOCAL)
ffffffff8130b010-ffffffff8130b17c: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010265684)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffff800010262bb0-ffff800010262be0: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0497620)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
c0495628-c0495648: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307950)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
c0000000003078b0-c0000000003078c8: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f4b0)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffe00019f40e-ffffffe00019f456: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811da5a8)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff811d8ab0-ffffffff811d8ac5: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cd368)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff811cb870-ffffffff811cb885: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8378)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff811d6880-ffffffff811d6895: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e6728)
Location: kernel/bpf/syscall.c:336
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_put_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff811e4bf0-ffffffff811e4c05: bpf_map_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
