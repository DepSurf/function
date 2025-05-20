# Function: <code>acpi_ds_method_data_get_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8148cb6d)
Location: drivers/acpi/acpica/dsmthdat.c:248
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff8148cb6d-ffffffff8148cc12: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff814db986)
Location: drivers/acpi/acpica/dsmthdat.c:249
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff814db986-ffffffff814dba2b: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff814fe295)
Location: drivers/acpi/acpica/dsmthdat.c:249
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff814fe295-ffffffff814fe33a: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8150e75c)
Location: drivers/acpi/acpica/dsmthdat.c:249
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff8150e75c-ffffffff8150e801: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81553273)
Location: drivers/acpi/acpica/dsmthdat.c:249
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff81553273-ffffffff815533de: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81589bc3)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff81589bc3-ffffffff81589d2e: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815a2189)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff815a2189-ffffffff815a22f4: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815d3809)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff815d3809-ffffffff815d3975: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815f4a81)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff815f4a81-ffffffff815f4bed: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff816a0b0a)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff816a0b0a-ffffffff816a0c76: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff816be322)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff816be322-ffffffff816be48e: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff816a03ff)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff816a03ff-ffffffff816a056f: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81716c20)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff81716c20-ffffffff81716dc3: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8184676d)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff8184676d-ffffffff8184691c: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8197e370)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff8197e370-ffffffff8197e556: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff819c4e20)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff819c4e20-ffffffff819c5009: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81a0f870)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff81a0f870-ffffffff81a0fa59: acpi_ds_method_data_get_node (STB_GLOBAL)
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
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffff80001077e19c)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffff80001077e19c-ffff80001077e278: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815e1e74)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff815e1e74-ffffffff815e1f1c: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815cd4ea)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff815cd4ea-ffffffff815cd592: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815e8d61)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff815e8d61-ffffffff815e8ecd: acpi_ds_method_data_get_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_get_node(u8 type, u32 index, struct acpi_walk_state *walk_state, struct acpi_namespace_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81602c11)
Location: drivers/acpi/acpica/dsmthdat.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
```
**Symbols:**

```
ffffffff81602c11-ffffffff81602d7d: acpi_ds_method_data_get_node (STB_GLOBAL)
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
