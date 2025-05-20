# Function: <code>__bpf_map_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172a7b)
Location: kernel/bpf/syscall.c:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81173420-ffffffff81173467: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181928)
Location: kernel/bpf/syscall.c:214
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811813a0-ffffffff811813e8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118dbb3)
Location: kernel/bpf/syscall.c:257
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8118cfb0-ffffffff8118cff8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119285e)
Location: kernel/bpf/syscall.c:323
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
**Symbols:**

```
ffffffff81191e30-ffffffff81191e80: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a0005)
Location: kernel/bpf/syscall.c:454
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
**Symbols:**

```
ffffffff8119f560-ffffffff8119f5b0: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3144)
Location: kernel/bpf/syscall.c:530
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/sockmap.c:sockmap_get_from_fd
```
**Symbols:**

```
ffffffff811b5650-ffffffff811b5697: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c402e)
Location: kernel/bpf/syscall.c:586
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811c35a0-ffffffff811c35e7: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d587e)
Location: kernel/bpf/syscall.c:643
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811d47b0-ffffffff811d47f8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e2375)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811e0eb0-ffffffff811e0ef8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd1d8)
Location: kernel/bpf/syscall.c:899
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811fef50-ffffffff811fef98: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc4a8)
Location: kernel/bpf/syscall.c:912
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811fe290-ffffffff811fe2d8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201bcb)
Location: kernel/bpf/syscall.c:913
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811fed20-ffffffff811fed68: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233c54)
Location: kernel/bpf/syscall.c:940
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81230970-ffffffff812309b8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8127134b)
Location: kernel/bpf/syscall.c:1174
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81273b00-ffffffff81273b63: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ccfeb)
Location: kernel/bpf/syscall.c:1217
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff812cac00-ffffffff812cac63: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ee746)
Location: kernel/bpf/syscall.c:1292
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff812f2340-ffffffff812f23a6: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130d506)
Location: kernel/bpf/syscall.c:1323
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff813111e0-ffffffff81311246: __bpf_map_get (STB_GLOBAL)
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
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010263500)
Location: kernel/bpf/syscall.c:646
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffff800010263500-ffff8000102635a4: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04971b4)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
c0496068-c04960d8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000309c40)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
c000000000308790-c000000000308848: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a0a46)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffe00019fd12-ffffffe00019fd88: __bpf_map_get (STB_GLOBAL)
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
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811da995)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811d94d0-ffffffff811d9518: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cd755)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811cc290-ffffffff811cc2d8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8765)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811d72a0-ffffffff811d72e8: __bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_get(struct fd f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e6aec)
Location: kernel/bpf/syscall.c:646
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff811e5630-ffffffff811e5678: __bpf_map_get (STB_GLOBAL)
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
