# Function: <code>acpi_get_table_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814a5c5d)
Location: drivers/acpi/acpica/tbxface.c:355
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff814a5c5d-ffffffff814a5ce1: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814f4f37)
Location: drivers/acpi/acpica/tbxface.c:355
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff814f4f37-ffffffff814f4fbb: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81517c1c)
Location: drivers/acpi/acpica/tbxface.c:407
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81517c1c-ffffffff81517c85: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81528263)
Location: drivers/acpi/acpica/tbxface.c:407
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81528263-ffffffff815282cc: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8157fe5e)
Location: drivers/acpi/acpica/tbxface.c:439
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff8157fe5e-ffffffff8157ff30: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815b7055)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff815b7055-ffffffff815b7127: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815d0412)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff815d0412-ffffffff815d04e4: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81601cae)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81601cae-ffffffff81601d80: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81623157)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81623157-ffffffff81623229: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf657)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff816cf657-ffffffff816cf723: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816ed657)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff816ed657-ffffffff816ed723: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf513)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff816cf513-ffffffff816cf5df: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81746b83)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81746b83-ffffffff81746c4f: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81878bee)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81878bee-ffffffff81878cc7: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff819baf80)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff819baf80-ffffffff819bb074: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a02120)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81a02120-ffffffff81a02214: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a4cfa0)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81a4cfa0-ffffffff81a4d094: acpi_get_table_by_index (STB_GLOBAL)
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
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffff80001079837c)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
```
**Symbols:**

```
ffff80001079837c-ffff8000107983fc: acpi_get_table_by_index (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815fce99)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff815fce99-ffffffff815fcf02: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815e83bf)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff815e83bf-ffffffff815e8428: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81617437)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff81617437-ffffffff81617509: acpi_get_table_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_table_by_index(u32 table_index, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816312e7)
Location: drivers/acpi/acpica/tbxface.c:405
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_load_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_initialize_facs
```
**Symbols:**

```
ffffffff816312e7-ffffffff816313b9: acpi_get_table_by_index (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_table_header **out_table</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_table_header **table</code>
</li>
</ul>
</details>
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
