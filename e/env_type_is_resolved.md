# Function: <code>env_type_is_resolved</code>

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
In kernel/bpf/btf.c (ffffffff811c90c1)
Location: kernel/bpf/btf.c:756
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff811dc216)
Location: kernel/bpf/btf.c:888
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f195f)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fe06f)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224515)
Location: kernel/bpf/btf.c:1017
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ad34)
Location: kernel/bpf/btf.c:1607
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122f672)
Location: kernel/bpf/btf.c:1608
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812683d2)
Location: kernel/bpf/btf.c:1608
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b5701)
Location: kernel/bpf/btf.c:1736
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81315d31)
Location: kernel/bpf/btf.c:1759
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81345d01)
Location: kernel/bpf/btf.c:1789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136bc91)
Location: kernel/bpf/btf.c:1790
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010284ff0)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b5610)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032fc5c)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001ba4fa)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f668f)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e93df)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f445f)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8120296f)
Location: kernel/bpf/btf.c:989
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
</ul>

## Differences
