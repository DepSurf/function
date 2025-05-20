# Function: <code>__apei_exec_read_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff814b3960)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
```
**Symbols:**

```
ffffffff814b3960-ffffffff814b399e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815032e0)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff815032e0-ffffffff8150331e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815274d0)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff815274d0-ffffffff8152750e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8153a410)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff8153a410-ffffffff8153a44e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8159cf70)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff8159cf70-ffffffff8159cfae: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815d4b40)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff815d4b40-ffffffff815d4b7e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815ee2f0)
Location: drivers/acpi/apei/apei-base.c:65
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff815ee2f0-ffffffff815ee32e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81620080)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff81620080-ffffffff816200be: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81641b60)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff81641b60-ffffffff81641b9e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816ee725)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff816ef050-ffffffff816ef08e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8170bd55)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff8170c680-ffffffff8170c6be: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816ed395)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff816edce0-ffffffff816edd1e: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff817674e7)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff81cf22a3-ffffffff81cf22c7: __apei_exec_read_register.cold (STB_LOCAL)
ffffffff81767d00-ffffffff81767d54: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8189bbe7)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff81eba2ff-ffffffff81eba323: __apei_exec_read_register.cold (STB_LOCAL)
ffffffff8189c4a0-ffffffff8189c500: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff819e4397)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff82092a5a-ffffffff82092a7e: __apei_exec_read_register.cold (STB_LOCAL)
ffffffff819e4df0-ffffffff819e4e50: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a2c9b7)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff821137e9-ffffffff8211380d: __apei_exec_read_register.cold (STB_LOCAL)
ffffffff81a2d410-ffffffff81a2d470: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a77bf7)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff821f115c-ffffffff821f1180: __apei_exec_read_register.cold (STB_LOCAL)
ffffffff81a78650-ffffffff81a786b0: __apei_exec_read_register (STB_GLOBAL)
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
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffff8000107acbb0)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffff8000107acbb0-ffff8000107acc04: __apei_exec_read_register (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815fdf70)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff815fdf70-ffffffff815fdfae: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816359a0)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff816359a0-ffffffff816359de: __apei_exec_read_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __apei_exec_read_register(struct acpi_whea_header *entry, u64 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8164fcb0)
Location: drivers/acpi/apei/apei-base.c:57
Inline: True
Direct callers:
  - drivers/acpi/apei/apei-base.c:apei_exec_read_register_value
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_set_dst_address_base
  - drivers/acpi/apei/erst.c:erst_exec_set_src_address_base
  - drivers/acpi/apei/erst.c:erst_exec_skip_next_instruction_if_true
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_exec_subtract_value
  - drivers/acpi/apei/erst.c:erst_exec_add_value
  - drivers/acpi/apei/erst.c:erst_exec_load_var2
  - drivers/acpi/apei/erst.c:erst_exec_load_var1
```
**Symbols:**

```
ffffffff8164fcb0-ffffffff8164fcee: __apei_exec_read_register (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
