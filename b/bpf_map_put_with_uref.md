# Function: <code>bpf_map_put_with_uref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811733b1)
Location: kernel/bpf/syscall.c:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811733d0-ffffffff811733ed: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181333)
Location: kernel/bpf/syscall.c:119
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff81181350-ffffffff8118136d: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118cf43)
Location: kernel/bpf/syscall.c:147
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff8118cf60-ffffffff8118cf7d: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191a13)
Location: kernel/bpf/syscall.c:196
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff81191dd0-ffffffff81191df2: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e955)
Location: kernel/bpf/syscall.c:246
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff8119f4b0-ffffffff8119f4d2: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b50c5)
Location: kernel/bpf/syscall.c:293
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811b50e0-ffffffff811b5102: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c57cc)
Location: kernel/bpf/syscall.c:321
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811c34f0-ffffffff811c3512: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5d91)
Location: kernel/bpf/syscall.c:339
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d4250-ffffffff811d4274: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e1f80)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811e0950-ffffffff811e0974: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe950)
Location: kernel/bpf/syscall.c:496
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811fe950-ffffffff811fe987: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fdc70)
Location: kernel/bpf/syscall.c:490
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
```
**Symbols:**

```
ffffffff811fdc70-ffffffff811fdca7: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe830)
Location: kernel/bpf/syscall.c:491
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
```
**Symbols:**

```
ffffffff811fe830-ffffffff811fe867: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230470)
Location: kernel/bpf/syscall.c:510
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
```
**Symbols:**

```
ffffffff81230470-ffffffff812304a7: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812733b0)
Location: kernel/bpf/syscall.c:631
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - kernel/bpf/hashtab.c:bpf_iter_fini_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_fini_array_map
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_hash_fini_seq_private
  - net/core/sock_map.c:sock_map_fini_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
  - net/core/bpf_sk_storage.c:bpf_iter_fini_sk_storage_map
```
**Symbols:**

```
ffffffff812733b0-ffffffff812733ef: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c9ac0)
Location: kernel/bpf/syscall.c:731
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - kernel/bpf/hashtab.c:bpf_iter_fini_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_fini_array_map
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_hash_fini_seq_private
  - net/core/sock_map.c:sock_map_fini_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
  - net/core/bpf_sk_storage.c:bpf_iter_fini_sk_storage_map
```
**Symbols:**

```
ffffffff812c9ac0-ffffffff812c9aff: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f2679)
Location: kernel/bpf/syscall.c:737
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - kernel/bpf/hashtab.c:bpf_iter_fini_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_fini_array_map
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_hash_fini_seq_private
  - net/core/sock_map.c:sock_map_fini_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
  - net/core/bpf_sk_storage.c:bpf_iter_fini_sk_storage_map
```
**Symbols:**

```
ffffffff812f1320-ffffffff812f1346: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81311519)
Location: kernel/bpf/syscall.c:767
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/map_iter.c:bpf_iter_detach_map
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
  - kernel/bpf/hashtab.c:bpf_iter_fini_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_fini_array_map
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
  - net/core/sock_map.c:sock_map_iter_detach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_map_iter_attach_target
  - net/core/sock_map.c:sock_hash_fini_seq_private
  - net/core/sock_map.c:sock_map_fini_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_detach_map
  - net/core/bpf_sk_storage.c:bpf_iter_attach_map
  - net/core/bpf_sk_storage.c:bpf_iter_fini_sk_storage_map
```
**Symbols:**

```
ffffffff81310150-ffffffff81310176: bpf_map_put_with_uref (STB_GLOBAL)
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
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001026567c)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffff800010262f38-ffff800010262f70: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0497618)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
c0495b44-c0495b70: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307ff0)
Location: kernel/bpf/syscall.c:342
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
c000000000307ff0-c000000000308078: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f842)
Location: kernel/bpf/syscall.c:342
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffe00019f842-ffffffe00019f8b8: bpf_map_put_with_uref (STB_GLOBAL)
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
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811da5a0)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d8f70-ffffffff811d8f94: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cd360)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811cbd30-ffffffff811cbd54: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8370)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d6d40-ffffffff811d6d64: bpf_map_put_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_put_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e6720)
Location: kernel/bpf/syscall.c:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811e50b0-ffffffff811e50d4: bpf_map_put_with_uref (STB_GLOBAL)
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
