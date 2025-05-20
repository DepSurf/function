# Function: <code>btf_type_id_size</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7e70)
Location: kernel/bpf/btf.c:821
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_check_btf
  - kernel/bpf/arraymap.c:array_map_check_btf
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_member
```
**Symbols:**

```
ffffffff811c7e70-ffffffff811c7f2c: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811db190)
Location: kernel/bpf/btf.c:953
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff811db190-ffffffff811db269: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0750)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff811f0750-ffffffff811f0858: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fce60)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff811fce60-ffffffff811fcf68: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223130)
Location: kernel/bpf/btf.c:1160
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff81223130-ffffffff81223240: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812295e0)
Location: kernel/bpf/btf.c:1789
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff812295e0-ffffffff8122977a: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122de80)
Location: kernel/bpf/btf.c:1791
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff8122de80-ffffffff8122e00c: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81266a80)
Location: kernel/bpf/btf.c:1791
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff81266a80-ffffffff81266c0c: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b3c40)
Location: kernel/bpf/btf.c:1920
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff812b3c40-ffffffff812b3e3a: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81314140)
Location: kernel/bpf/btf.c:1944
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff81314140-ffffffff8131433a: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343fb0)
Location: kernel/bpf/btf.c:1974
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff81343fb0-ffffffff81344236: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369f40)
Location: kernel/bpf/btf.c:1975
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff81369f40-ffffffff8136a1c6: btf_type_id_size (STB_GLOBAL)
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
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010283b90)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffff800010283b90-ffff800010283cf0: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b428c)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
c04b428c-c04b43fc: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032e240)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
c00000000032e240-c00000000032e3ac: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b94f6)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffe0001b94f6-ffffffe0001b9610: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f5480)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff811f5480-ffffffff811f5588: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e81d0)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff811e81d0-ffffffff811e82d8: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3250)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff811f3250-ffffffff811f3358: btf_type_id_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct btf_type *btf_type_id_size(const struct btf *btf, u32 *type_id, u32 *ret_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81201760)
Location: kernel/bpf/btf.c:1054
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_array_seq_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
**Symbols:**

```
ffffffff81201760-ffffffff81201868: btf_type_id_size (STB_GLOBAL)
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
