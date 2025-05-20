# Function: <code>btf_put</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7de0)
Location: kernel/bpf/btf.c:684
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811c7de0-ffffffff811c7e48: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811db100)
Location: kernel/bpf/btf.c:812
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811db100-ffffffff811db168: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f06c0)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811f06c0-ffffffff811f0728: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fcdd0)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811fcdd0-ffffffff811fce38: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222fb0)
Location: kernel/bpf/btf.c:941
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff81222fb0-ffffffff8122302f: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812292b0)
Location: kernel/bpf/btf.c:1532
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff812292b0-ffffffff8122932f: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122db50)
Location: kernel/bpf/btf.c:1533
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff8122db50-ffffffff8122dbcf: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81266580)
Location: kernel/bpf/btf.c:1533
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/map_in_map.c:bpf_map_meta_free
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff81266580-ffffffff812665ff: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b3120)
Location: kernel/bpf/btf.c:1661
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_copy_kptr_off_tab
  - kernel/bpf/syscall.c:bpf_map_free_kptr_off_tab
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:bpf_free_kfunc_btf_tab
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/map_in_map.c:bpf_map_meta_free
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:bpf_find_btf_id
```
**Symbols:**

```
ffffffff812b3120-ffffffff812b31bd: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313550)
Location: kernel/bpf/btf.c:1684
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:bpf_free_kfunc_btf_tab
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/map_in_map.c:bpf_map_meta_free
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:bpf_find_btf_id
```
**Symbols:**

```
ffffffff81313550-ffffffff813135ed: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343220)
Location: kernel/bpf/btf.c:1714
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:bpf_free_kfunc_btf_tab
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/map_in_map.c:bpf_map_meta_free
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:bpf_find_btf_id
```
**Symbols:**

```
ffffffff81343220-ffffffff813432bd: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369150)
Location: kernel/bpf/btf.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_finish_parse
  - kernel/trace/trace_btf.c:btf_find_func_proto
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:bpf_free_kfunc_btf_tab
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/map_in_map.c:bpf_map_meta_free
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:bpf_find_btf_id
```
**Symbols:**

```
ffffffff81369150-ffffffff813691ed: btf_put (STB_GLOBAL)
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
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010283a70)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffff800010283a70-ffff800010283b60: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b41fc)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
c04b41fc-c04b4268: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032e120)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
c00000000032e120-c00000000032e1fc: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001bb0ae)
Location: kernel/bpf/btf.c:913
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffe0001b8ada-ffffffe0001b8b4a: btf_put.part.0 (STB_LOCAL)
ffffffe0001b94ae-ffffffe0001b94f6: btf_put (STB_GLOBAL)
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
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f53f0)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811f53f0-ffffffff811f5458: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e8140)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811e8140-ffffffff811e81a8: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f31c0)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff811f31c0-ffffffff811f3228: btf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void btf_put(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812016d0)
Location: kernel/bpf/btf.c:913
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
**Symbols:**

```
ffffffff812016d0-ffffffff81201738: btf_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
