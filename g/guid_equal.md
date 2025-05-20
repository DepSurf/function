# Function: <code>guid_equal</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153cc24)
Location: include/linux/uuid.h:43
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636420)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff816393b5)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8163abee)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154e4e8)
Location: include/linux/uuid.h:43
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f74e)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/acpi/apei/ghes.c:ghes_do_proc
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169ed20)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff816a1a85)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816a37ee)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff817ff1f2)
Location: include/linux/uuid.h:43
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815849c8)
Location: include/linux/uuid.h:44
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d751d)
Location: include/linux/uuid.h:44
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816db15e)
Location: include/linux/uuid.h:44
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff816de215)
Location: include/linux/uuid.h:44
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816df96d)
Location: include/linux/uuid.h:44
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff81848a35)
Location: include/linux/uuid.h:44
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff8184a5a1)
Location: include/linux/uuid.h:44
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff81848a35-ffffffff81848a4a: guid_equal (STB_LOCAL)
ffffffff8184a5a1-ffffffff8184a5b6: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159d6a3)
Location: include/linux/uuid.h:44
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0c9e)
Location: include/linux/uuid.h:44
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd10f)
Location: include/linux/uuid.h:44
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff81700575)
Location: include/linux/uuid.h:44
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81701d1d)
Location: include/linux/uuid.h:44
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff81874ca5)
Location: include/linux/uuid.h:44
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81877481)
Location: include/linux/uuid.h:44
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff81874ca5-ffffffff81874cba: guid_equal (STB_LOCAL)
ffffffff81877481-ffffffff81877496: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81052ac9)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff815cec85)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/acpi/apei/erst.c (ffffffff816218ec)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff8162292c)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736c2d)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff8173a345)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8173bb85)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff818b8ed8)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff818bbce1)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff818b8ed8-ffffffff818b8eed: guid_equal (STB_LOCAL)
ffffffff818bbce1-ffffffff818bbcf6: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810533b9)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff815eff05)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/acpi/apei/erst.c (ffffffff816433cc)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff816443fc)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a932)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff8175e0b5)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175f8a5)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb8d8)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff818ee7b1)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff818eb8d8-ffffffff818eb8ed: guid_equal (STB_LOCAL)
ffffffff818ee7b1-ffffffff818ee7c6: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810583bb)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff8169c5eb)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/apei/erst.c (ffffffff816f07e4)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f17ad)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a3c3)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff8181da55)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8181ef85)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff819bf2d1)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff819c261c)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff819bf2d1-ffffffff819bf2e6: guid_equal (STB_LOCAL)
ffffffff819c261c-ffffffff819c2631: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810571bb)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff816b947b)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/apei/erst.c (ffffffff8170dbc4)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170eb4d)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818294e3)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff8182cb75)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8182decb)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff81c2c069)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81c2cf38)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff81c2c069-ffffffff81c2c07e: guid_equal (STB_LOCAL)
ffffffff81c2cf38-ffffffff81c2cf4d: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81057b09)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff8169b37d)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/apei/erst.c (ffffffff816eed4d)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f00e1)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c6f3)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff8180fec5)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8181119b)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff81c1e2db)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81c1f166)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff81c1e2db-ffffffff81c1e2f0: guid_equal (STB_LOCAL)
ffffffff81c1f166-ffffffff81c1f17b: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810609d9)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff8171121d)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/prmt.c (ffffffff817135bb)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:find_guid_info
```
```
In drivers/acpi/apei/erst.c (ffffffff81768e2d)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176a1d1)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8189a49b)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8189bddb)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff81d2f7e2)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81d307b3)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff81d2f7e2-ffffffff81d2f7f7: guid_equal (STB_LOCAL)
ffffffff81d307b3-ffffffff81d307c8: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183ffa3)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/prmt.c (ffffffff81842c7b)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:find_guid_info
```
```
In drivers/acpi/apei/erst.c (ffffffff8189dd53)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189ee9d)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff819e2ee6)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
```
```
In drivers/firmware/efi/cper.c (ffffffff81efbab3)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81efcbf0)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff81efbab3-ffffffff81efbad2: guid_equal (STB_LOCAL)
ffffffff81efcbf0-ffffffff81efcc0f: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81639df1)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In fs/efivarfs/super.c (ffffffff8163a6e3)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In drivers/acpi/property.c (ffffffff81976593)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/prmt.c (ffffffff81979d8b)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:find_guid_info
```
```
In drivers/acpi/apei/erst.c (ffffffff819e6cf8)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e81f9)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81b5eb46)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
```
```
In drivers/firmware/efi/cper.c (ffffffff81d6559a)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81d68e0e)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81672251)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In fs/efivarfs/super.c (ffffffff81672c93)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In drivers/acpi/property.c (ffffffff819bcf03)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/prmt.c (ffffffff819c081b)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:find_guid_info
```
```
In drivers/acpi/apei/erst.c (ffffffff81a2f3b2)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30919)
Location: include/linux/uuid.h:46
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81bb20ef)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
```
```
In drivers/firmware/efi/cper.c (ffffffff81dd06ca)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81dd403e)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff816ae270)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In fs/efivarfs/super.c (ffffffff816af008)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In drivers/acpi/property.c (ffffffff81a07db3)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/prmt.c (ffffffff81a0b29b)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:find_guid_info
```
```
In drivers/acpi/apei/erst.c (ffffffff81a7a6f2)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7bcf9)
Location: include/linux/uuid.h:46
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81c065df)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_get_claim_class
  - drivers/nvdimm/label.c:nsl_validate_type_guid
```
```
In drivers/firmware/efi/cper.c (ffffffff81e893f1)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81e8c04e)
Location: include/linux/uuid.h:46
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077ae78)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/acpi/apei/erst.c (ffff8000107ae0c0)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffff8000107af5b8)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c338)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffff80001095f6b8)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffff800010961270)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffff800010b5ebfc)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffff800010b5ebfc-ffff800010b5ec1c: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0d3e4)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (c000000000a12060)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (c000000000a145e8)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca490)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffe0005cd418)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffe0005cea4c)
Location: include/linux/uuid.h:36
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815deb95)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f022)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff817127a5)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81713f95)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81043009)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff815ca1d5)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/acpi/nfit/core.c (ffffffff815f9130)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_ars_rescan
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_regions
  - drivers/acpi/nfit/core.c:acpi_nfit_register_regions
  - drivers/acpi/nfit/core.c:acpi_nfit_register_regions
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:nfit_spa_is_virtual
  - drivers/acpi/nfit/core.c:nfit_spa_is_virtual
  - drivers/acpi/nfit/core.c:nfit_spa_is_virtual
  - drivers/acpi/nfit/core.c:nfit_spa_is_virtual
  - drivers/acpi/nfit/core.c:ars_start
  - drivers/acpi/nfit/core.c:ars_start
  - drivers/acpi/nfit/core.c:__nfit_mem_init
  - drivers/acpi/nfit/core.c:__nfit_mem_init
```
```
In drivers/acpi/apei/erst.c (ffffffff815ff7ac)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2aa2)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff816e6225)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816e7a15)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff81845fd8)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81848e41)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184efc6)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:remove_id_store
  - drivers/hv/vmbus_drv.c:hv_vmbus_get_id
  - drivers/hv/vmbus_drv.c:hv_vmbus_get_id
  - drivers/hv/vmbus_drv.c:hv_vmbus_dynid_match
```
```
In drivers/hv/channel_mgmt.c (ffffffff8185255e)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
```
**Symbols:**

```
ffffffff81845fd8-ffffffff81845fed: guid_equal (STB_LOCAL)
ffffffff81848e41-ffffffff81848e56: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81053369)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff815e41e5)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/acpi/apei/erst.c (ffffffff8163720c)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff8163823c)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ddf2)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff81751575)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81752d65)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff818e0738)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff818e35e1)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff818e0738-ffffffff818e074d: guid_equal (STB_LOCAL)
ffffffff818e35e1-ffffffff818e35f6: guid_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool guid_equal(const guid_t *u1, const guid_t *u2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810547e9)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
```
In drivers/acpi/property.c (ffffffff815fe0a5)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/acpi/apei/erst.c (ffffffff8165151c)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
  - drivers/acpi/apei/erst.c:erst_reader
```
```
In drivers/acpi/apei/ghes.c (ffffffff8165257c)
Location: include/linux/uuid.h:36
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81769272)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
```
In drivers/nvdimm/label.c (ffffffff8176c9f5)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
  - drivers/nvdimm/label.c:to_nvdimm_cclass
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8176e1d5)
Location: include/linux/uuid.h:36
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid
```
```
In drivers/firmware/efi/cper.c (ffffffff818fd1d8)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
```
In drivers/firmware/efi/cper-x86.c (ffffffff81900251)
Location: include/linux/uuid.h:36
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
  - drivers/firmware/efi/cper-x86.c:cper_get_err_type
```
**Symbols:**

```
ffffffff818fd1d8-ffffffff818fd1ed: guid_equal (STB_LOCAL)
ffffffff81900251-ffffffff81900266: guid_equal (STB_LOCAL)
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
