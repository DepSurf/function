# Function: <code>btf_type_is_void</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7ad7)
Location: kernel/bpf/btf.c:307
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811daf0f)
Location: kernel/bpf/btf.c:317
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811efc3c)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff811f0660-ffffffff811f0675: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fc35c)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff811fcd70-ffffffff811fcd85: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122266c)
Location: kernel/bpf/btf.c:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff81222d70-ffffffff81222d85: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227275)
Location: kernel/bpf/btf.c:425
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff81227f30-ffffffff81227f45: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122bd4d)
Location: kernel/bpf/btf.c:426
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff8122ca20-ffffffff8122ca35: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812645d2)
Location: kernel/bpf/btf.c:426
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff81265380-ffffffff81265395: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b39c1)
Location: kernel/bpf/btf.c:458
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/bloom_filter.c:bloom_map_check_btf
```
**Symbols:**

```
ffffffff812b13c0-ffffffff812b13db: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313ea0)
Location: kernel/bpf/btf.c:463
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/bloom_filter.c:bloom_map_check_btf
```
**Symbols:**

```
ffffffff813115b0-ffffffff813115cb: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343cb8)
Location: kernel/bpf/btf.c:485
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/bloom_filter.c:bloom_map_check_btf
```
**Symbols:**

```
ffffffff81340f90-ffffffff81340fab: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369c48)
Location: kernel/bpf/btf.c:486
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/bloom_filter.c:bloom_map_check_btf
```
**Symbols:**

```
ffffffff813675a0-ffffffff813675bb: btf_type_is_void (STB_GLOBAL)
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
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff80001028287c)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffff800010283998-ffff8000102839cc: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b31cc)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
c04b4178-c04b41a4: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032d048)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
c00000000032e080-c00000000032e0a8: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b93fc)
Location: kernel/bpf/btf.c:329
Inline: True
```
**Symbols:**

```
ffffffe0001b93fc-ffffffe0001b942c: btf_type_is_void (STB_GLOBAL)
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
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f497c)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff811f5390-ffffffff811f53a5: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e76cc)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff811e80e0-ffffffff811e80f5: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f274c)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff811f3160-ffffffff811f3175: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool btf_type_is_void(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81200c5c)
Location: kernel/bpf/btf.c:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
**Symbols:**

```
ffffffff81201670-ffffffff81201685: btf_type_is_void (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
