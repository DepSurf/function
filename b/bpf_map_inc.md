# Function: <code>bpf_map_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81173470)
Location: kernel/bpf/syscall.c:184
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81173470-ffffffff81173487: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811813f0)
Location: kernel/bpf/syscall.c:229
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811813f0-ffffffff81181426: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118d000)
Location: kernel/bpf/syscall.c:272
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff8118d000-ffffffff8118d036: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191e80)
Location: kernel/bpf/syscall.c:338
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff81191e80-ffffffff81191eb6: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f5b0)
Location: kernel/bpf/syscall.c:469
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff8119f5b0-ffffffff8119f5e8: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b35e0)
Location: kernel/bpf/syscall.c:545
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811b35e0-ffffffff811b3621: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1cc0)
Location: kernel/bpf/syscall.c:601
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811c1cc0-ffffffff811c1d01: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2310)
Location: kernel/bpf/syscall.c:658
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811d2310-ffffffff811d2351: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de8b0)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811de8b0-ffffffff811de8f1: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fefec)
Location: kernel/bpf/syscall.c:911
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811fb390-ffffffff811fb3a3: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe32c)
Location: kernel/bpf/syscall.c:924
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811fa4f0-ffffffff811fa503: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fedbc)
Location: kernel/bpf/syscall.c:925
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811fb430-ffffffff811fb443: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230a0c)
Location: kernel/bpf/syscall.c:952
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff8122cb70-ffffffff8122cb83: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81270d50)
Location: kernel/bpf/syscall.c:1186
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff8126ee80-ffffffff8126ee99: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6d80)
Location: kernel/bpf/syscall.c:1229
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff812c4660-ffffffff812c4679: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812edf23)
Location: kernel/bpf/syscall.c:1304
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff812eb660-ffffffff812eb679: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130ccc3)
Location: kernel/bpf/syscall.c:1335
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/arraymap.c:prog_array_map_clear
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_link_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81309bb0-ffffffff81309bc9: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102600a8)
Location: kernel/bpf/syscall.c:661
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffff8000102600a8-ffff800010260180: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c0493288)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
c0493288-c04932bc: bpf_map_inc.part.0 (STB_LOCAL)
c04932bc-c0493330: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304b90)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
c000000000304b90-c000000000304c08: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019fde0)
Location: kernel/bpf/syscall.c:661
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffe00019d73c-ffffffe00019d79a: bpf_map_inc (STB_GLOBAL)
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
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6ed0)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811d6ed0-ffffffff811d6f11: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9c90)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811c9c90-ffffffff811c9cd1: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4ca0)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811d4ca0-ffffffff811d4ce1: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_map_inc(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e2fd0)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811e2fd0-ffffffff811e3011: bpf_map_inc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct bpf_map *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool uref</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bpf_map *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
