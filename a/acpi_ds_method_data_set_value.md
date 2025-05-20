# Function: <code>acpi_ds_method_data_set_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8148cc5a)
Location: drivers/acpi/acpica/dsmthdat.c:314
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff814dbcf9)
Location: drivers/acpi/acpica/dsmthdat.c:315
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff814fe608)
Location: drivers/acpi/acpica/dsmthdat.c:315
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8150eadf)
Location: drivers/acpi/acpica/dsmthdat.c:315
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815533de)
Location: drivers/acpi/acpica/dsmthdat.c:315
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff815533de-ffffffff81553509: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81589d2e)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff81589d2e-ffffffff81589e59: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815a22f4)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff815a22f4-ffffffff815a241f: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815d3975)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff815d3975-ffffffff815d3aa0: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815f4bed)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff815f4bed-ffffffff815f4d18: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff816a0c76)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff816a0c76-ffffffff816a0da1: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff816be48e)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff816be48e-ffffffff816be5b9: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff816a056f)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff816a056f-ffffffff816a069a: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81716dc3)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff81716dc3-ffffffff81716eee: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8184691c)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff8184691c-ffffffff81846a5f: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff8197e570)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff8197e570-ffffffff8197e6c6: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff819c5020)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff819c5020-ffffffff819c5176: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81a0fa70)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff81a0fa70-ffffffff81a0fbc6: acpi_ds_method_data_set_value (STB_LOCAL)
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
In drivers/acpi/acpica/dsmthdat.c (ffff80001077e504)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815e2211)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
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
In drivers/acpi/acpica/dsmthdat.c (ffffffff815cd887)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff815e8ecd)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff815e8ecd-ffffffff815e8ff8: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ds_method_data_set_value(u8 type, u32 index, union acpi_operand_object *object, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmthdat.c (ffffffff81602d7d)
Location: drivers/acpi/acpica/dsmthdat.c:279
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args
```
**Symbols:**

```
ffffffff81602d7d-ffffffff81602ea8: acpi_ds_method_data_set_value (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
