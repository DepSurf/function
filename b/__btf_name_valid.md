# Function: <code>__btf_name_valid</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811efdb0)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff811efdb0-ffffffff811efe4e: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fc4d0)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff811fc4d0-ffffffff811fc56e: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81220110)
Location: kernel/bpf/btf.c:555
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff81220110-ffffffff812201a8: __btf_name_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223590)
Location: kernel/bpf/btf.c:657
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff81223590-ffffffff81223646: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81228030)
Location: kernel/bpf/btf.c:659
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff81228030-ffffffff812280e6: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81260300)
Location: kernel/bpf/btf.c:659
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff81260300-ffffffff812603b6: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ab1e0)
Location: kernel/bpf/btf.c:754
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff812ab1e0-ffffffff812ab2b7: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130ab40)
Location: kernel/bpf/btf.c:755
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff8130ab40-ffffffff8130ac17: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133a4a0)
Location: kernel/bpf/btf.c:777
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff8133a4a0-ffffffff8133a561: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813605d0)
Location: kernel/bpf/btf.c:778
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff813605d0-ffffffff81360691: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffff800010282b00)
Location: kernel/bpf/btf.c:540
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffff800010282b00-ffff800010282bf4: __btf_name_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b35cc)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
c04b35cc-c04b36b0: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (c00000000032d250)
Location: kernel/bpf/btf.c:540
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
c00000000032d250-c00000000032d338: __btf_name_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b8b96)
Location: kernel/bpf/btf.c:540
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffe0001b8b96-ffffffe0001b8c4a: __btf_name_valid.isra.0 (STB_LOCAL)
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
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4af0)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff811f4af0-ffffffff811f4b8e: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e7840)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff811e7840-ffffffff811e78de: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f28c0)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff811f28c0-ffffffff811f295e: __btf_name_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __btf_name_valid(const struct btf *btf, u32 offset, bool dot_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81200dd0)
Location: kernel/bpf/btf.c:540
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
```
**Symbols:**

```
ffffffff81200dd0-ffffffff81200e6e: __btf_name_valid (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool dot_ok</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
