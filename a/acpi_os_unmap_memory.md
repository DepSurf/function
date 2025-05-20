# Function: <code>acpi_os_unmap_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8181aeea)
Location: drivers/acpi/osl.c:466
Inline: False
Direct callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8181aeea-ffffffff8181aefa: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81895052)
Location: drivers/acpi/osl.c:424
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81895052-ffffffff81895062: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff818c97ab)
Location: drivers/acpi/osl.c:425
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff818c97ab-ffffffff818c97bb: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81900d80)
Location: drivers/acpi/osl.c:424
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81900d80-ffffffff81900d90: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8198ad80)
Location: drivers/acpi/osl.c:424
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8198ad80-ffffffff8198ad90: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e76a0)
Location: drivers/acpi/osl.c:429
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff819e76a0-ffffffff819e76b0: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81a22b10)
Location: drivers/acpi/osl.c:429
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81a22b10-ffffffff81a22b20: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81a92bd0)
Location: drivers/acpi/osl.c:415
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81a92bd0-ffffffff81a92be0: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81aca3a0)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81aca3a0-ffffffff81aca3b0: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81bc2710)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81bc2710-ffffffff81bc2720: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81c3b750)
Location: drivers/acpi/osl.c:444
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81c3b750-ffffffff81c3b760: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81c2df10)
Location: drivers/acpi/osl.c:447
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81c2df10-ffffffff81c2df20: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81d4c820)
Location: drivers/acpi/osl.c:447
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81d4c820-ffffffff81d4c830: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81f1c360)
Location: drivers/acpi/osl.c:446
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81f1c360-ffffffff81f1c378: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff820c4380)
Location: drivers/acpi/osl.c:446
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff820c4380-ffffffff820c4398: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff82148160)
Location: drivers/acpi/osl.c:446
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff82148160-ffffffff82148178: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8222aac0)
Location: drivers/acpi/osl.c:446
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/tables.c:acpi_table_initrd_override
  - drivers/acpi/acpi_fpdt.c:fpdt_process_subtable
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
  - drivers/acpi/acpica/tbdata.c:acpi_tb_check_duplication
  - drivers/acpi/acpica/tbdata.c:acpi_tb_invalidate_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8222aac0-ffffffff8222aad8: acpi_os_unmap_memory (STB_GLOBAL)
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
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010d9dc38)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffff800010d9dc38-ffff800010d9dc6c: acpi_os_unmap_memory (STB_GLOBAL)
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
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81a69210)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81a69210-ffffffff81a69220: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81a25cd0)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81a25cd0-ffffffff81a25ce0: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81ad5620)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81ad5620-ffffffff81ad5630: acpi_os_unmap_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_os_unmap_memory(void *virt, acpi_size size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81ae1ae0)
Location: drivers/acpi/osl.c:433
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/tables.c:acpi_os_physical_table_override
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
  - drivers/acpi/acpica/tbdata.c:acpi_tb_acquire_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81ae1ae0-ffffffff81ae1af0: acpi_os_unmap_memory (STB_GLOBAL)
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
