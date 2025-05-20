# Function: <code>acpi_os_allocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff814911ae)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81492e10)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81493dd8)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8149630e)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff814978b5)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81499bd3)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8149a8c6)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8149cd54)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814a0090)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff814a596f)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff814a6223)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff814a646d)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff814a6a4a)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff814a8a7b)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff81493dd8-ffffffff81493e01: acpi_os_allocate (STB_LOCAL)
ffffffff814a646d-ffffffff814a6496: acpi_os_allocate (STB_LOCAL)
ffffffff814a6a4a-ffffffff814a6a7a: acpi_os_allocate (STB_LOCAL)
ffffffff814a8a7b-ffffffff814a8ab0: acpi_os_allocate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff814dff7b)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff814e1c16)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff814e2f35)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff814e561d)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff814e6bb8)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff814e8922)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff814e97c2)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff814ebefc)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef3b9)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff814f4ca0)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff814f54e7)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff814f5748)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff814f5df8)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff814f7d4a)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff814e2f35-ffffffff814e2f5e: acpi_os_allocate (STB_LOCAL)
ffffffff814f5748-ffffffff814f5771: acpi_os_allocate (STB_LOCAL)
ffffffff814f5df8-ffffffff814f5e28: acpi_os_allocate (STB_LOCAL)
ffffffff814f7d4a-ffffffff814f7d7f: acpi_os_allocate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815028e1)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81504555)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff8150593e)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81507e71)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8150940c)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8150b176)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8150c04a)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8150e782)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81511e0e)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81517902)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815180d6)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff8151830b)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815189bb)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8151a966)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff8150593e-ffffffff81505967: acpi_os_allocate (STB_LOCAL)
ffffffff8151830b-ffffffff81518334: acpi_os_allocate (STB_LOCAL)
ffffffff815189bb-ffffffff815189eb: acpi_os_allocate (STB_LOCAL)
ffffffff8151a966-ffffffff8151a99b: acpi_os_allocate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff81512e2d)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81514a9a)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81515f49)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815184a5)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81519a41)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8151b7aa)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8151c66f)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8151ee39)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815228f7)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff8152811f)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815288ff)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81528b33)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815291dc)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8152b189)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff81515f49-ffffffff81515f72: acpi_os_allocate (STB_LOCAL)
ffffffff81528b33-ffffffff81528b5c: acpi_os_allocate (STB_LOCAL)
ffffffff815291dc-ffffffff8152920c: acpi_os_allocate (STB_LOCAL)
ffffffff8152b189-ffffffff8152b1be: acpi_os_allocate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff8155b66e)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8155e80b)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81560b91)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81565f53)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81567cb0)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8156b13f)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8156cbdf)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff81571311)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8157707b)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff8157f98c)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815806a3)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81580aac)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8158122e)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81584b7a)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81588be8)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81588de2)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8158a1c3)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8158acd0)
Location: include/acpi/platform/aclinuxex.h:84
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8158d752)
Location: include/acpi/platform/aclinuxex.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81560b91-ffffffff81560bba: acpi_os_allocate (STB_LOCAL)
ffffffff81580aac-ffffffff81580ad5: acpi_os_allocate (STB_LOCAL)
ffffffff8158122e-ffffffff8158125e: acpi_os_allocate (STB_LOCAL)
ffffffff81584b7a-ffffffff81584baf: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff8158a1c3-ffffffff8158a1ec: acpi_os_allocate (STB_LOCAL)
ffffffff8158acd0-ffffffff8158acf9: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815921eb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815953f0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff8159783c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8159cc83)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8159e964)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815a1d9f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815a3827)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815a8055)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815adfe4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815b6b84)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815b7897)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815b7ca0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815b840a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815bbceb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff815bfd63)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815bff5f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815c1336)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff815c1fc6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815c4a9a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff8159783c-ffffffff81597865: acpi_os_allocate (STB_LOCAL)
ffffffff815b7ca0-ffffffff815b7cc9: acpi_os_allocate (STB_LOCAL)
ffffffff815b840a-ffffffff815b843a: acpi_os_allocate (STB_LOCAL)
ffffffff815bbceb-ffffffff815bbd20: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff815c1336-ffffffff815c135f: acpi_os_allocate (STB_LOCAL)
ffffffff815c1fc6-ffffffff815c1fef: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815aa88d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815adafe)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815aff40)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815b51bd)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815b6eaa)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815baa5f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815be366)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815c0ee8)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6fd5)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815cff41)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815d0c5a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815d1063)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815d17c9)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815d5131)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff815d91d4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815d93d0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815da7af)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff815db44c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815ddff0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815aff40-ffffffff815aff69: acpi_os_allocate (STB_LOCAL)
ffffffff815d1063-ffffffff815d108c: acpi_os_allocate (STB_LOCAL)
ffffffff815d17c9-ffffffff815d17f9: acpi_os_allocate (STB_LOCAL)
ffffffff815d5131-ffffffff815d5166: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff815da7af-ffffffff815da7d8: acpi_os_allocate (STB_LOCAL)
ffffffff815db44c-ffffffff815db475: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815dc073)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815df323)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815e17c7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815e6d10)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815e8a3b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815ec631)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815eff79)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f8900)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816017c8)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81602510)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81602926)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816030a2)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81606aca)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8160acd1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8160aee2)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8160c2d3)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8160cf60)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8160faf0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815e17c7-ffffffff815e17f0: acpi_os_allocate (STB_LOCAL)
ffffffff81602926-ffffffff8160294f: acpi_os_allocate (STB_LOCAL)
ffffffff816030a2-ffffffff816030d2: acpi_os_allocate (STB_LOCAL)
ffffffff81606aca-ffffffff81606aff: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff8160c2d3-ffffffff8160c2fc: acpi_os_allocate (STB_LOCAL)
ffffffff8160cf60-ffffffff8160cf89: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815fd3b6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81600666)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81602b5c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816080a5)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81609dd0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8160d9c6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81611407)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81619da6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81622c73)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816239bb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81623dd1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8162454c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81627f65)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8162c172)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8162c383)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8162d774)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8162e401)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81630f99)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81602b5c-ffffffff81602b85: acpi_os_allocate (STB_LOCAL)
ffffffff81623dd1-ffffffff81623dfa: acpi_os_allocate (STB_LOCAL)
ffffffff8162454c-ffffffff8162457c: acpi_os_allocate (STB_LOCAL)
ffffffff81627f65-ffffffff81627f9a: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff8162d774-ffffffff8162d79d: acpi_os_allocate (STB_LOCAL)
ffffffff8162e401-ffffffff8162e42a: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff816a9565)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac89a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816aeeb1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816b43af)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b60e8)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b9d24)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816bda58)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c62c3)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816cf2bb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816d00a3)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816d04ca)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816d0c26)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d46ff)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d895a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8b2d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816d9f7d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816dac16)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dda00)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff816aeeb1-ffffffff816aeeda: acpi_os_allocate (STB_LOCAL)
ffffffff816d04ca-ffffffff816d04f3: acpi_os_allocate (STB_LOCAL)
ffffffff816d0c26-ffffffff816d0c56: acpi_os_allocate (STB_LOCAL)
ffffffff816d46ff-ffffffff816d4734: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff816d9f7d-ffffffff816d9fa6: acpi_os_allocate (STB_LOCAL)
ffffffff816dac16-ffffffff816dac3f: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff816c6de9)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ca1d9)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816cc7ed)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816d1c80)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816d39fc)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816d771c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816db5fa)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e42e5)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816ed171)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816ee0a3)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816ee4b9)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816eec04)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816f26cc)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816f5d32)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f6abc)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816f7efb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816f8bdb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816fba9e)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff816cc7ed-ffffffff816cc816: acpi_os_allocate (STB_LOCAL)
ffffffff816d1c80-ffffffff816d1ca9: acpi_os_allocate (STB_LOCAL)
ffffffff816ed171-ffffffff816ed19a: acpi_os_allocate (STB_LOCAL)
ffffffff816ee4b9-ffffffff816ee4e2: acpi_os_allocate (STB_LOCAL)
ffffffff816eec04-ffffffff816eec34: acpi_os_allocate (STB_LOCAL)
ffffffff816f26cc-ffffffff816f2701: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff816f5d32-ffffffff816f5d5b: acpi_os_allocate (STB_LOCAL)
ffffffff816f7efb-ffffffff816f7f24: acpi_os_allocate (STB_LOCAL)
ffffffff816f8bdb-ffffffff816f8c04: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff816a8e1d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac1ba)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816ae7b9)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816b3c76)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b59a4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b96b1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd593)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c61b7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff816cf177)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816cff58)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816d036e)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816d0ab9)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d457d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d876f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d892c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816d9d6e)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816daa50)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dd8c1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff816ae7b9-ffffffff816ae7e2: acpi_os_allocate (STB_LOCAL)
ffffffff816d036e-ffffffff816d0397: acpi_os_allocate (STB_LOCAL)
ffffffff816d0ab9-ffffffff816d0ae9: acpi_os_allocate (STB_LOCAL)
ffffffff816d457d-ffffffff816d45b2: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff816d9d6e-ffffffff816d9d97: acpi_os_allocate (STB_LOCAL)
ffffffff816daa50-ffffffff816daa79: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff8171fa64)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81722ed7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81725578)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8172ac3f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8172c9cd)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81730701)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81734822)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173d51c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff817467e7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff817475cb)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81747a4e)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81748199)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8174be54)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81750323)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff817504e0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81751992)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff817526ed)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff817559b1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81725578-ffffffff817255a1: acpi_os_allocate (STB_LOCAL)
ffffffff81747a4e-ffffffff81747a77: acpi_os_allocate (STB_LOCAL)
ffffffff81748199-ffffffff817481c9: acpi_os_allocate (STB_LOCAL)
ffffffff8174be54-ffffffff8174be89: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff81751992-ffffffff817519bb: acpi_os_allocate (STB_LOCAL)
ffffffff817526ed-ffffffff81752716: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff8184fc10)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8185338b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81855c75)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8185b517)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8185d355)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81861190)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81865830)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186e817)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff818785c7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff818795fc)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81879ab2)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8187a2ab)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8187e484)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81882137)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8188300a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81884704)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8188548b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81888a4b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81855c75-ffffffff81855ca5: acpi_os_allocate (STB_LOCAL)
ffffffff8185b517-ffffffff8185b547: acpi_os_allocate (STB_LOCAL)
ffffffff81861190-ffffffff818611c0: acpi_os_allocate (STB_LOCAL)
ffffffff8186e817-ffffffff8186e847: acpi_os_allocate (STB_LOCAL)
ffffffff818785c7-ffffffff818785f7: acpi_os_allocate (STB_LOCAL)
ffffffff81879ab2-ffffffff81879ae2: acpi_os_allocate (STB_LOCAL)
ffffffff8187a2ab-ffffffff8187a2db: acpi_os_allocate (STB_LOCAL)
ffffffff8187e484-ffffffff8187e4c2: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff81882137-ffffffff81882167: acpi_os_allocate (STB_LOCAL)
ffffffff8188300a-ffffffff8188303a: acpi_os_allocate (STB_LOCAL)
ffffffff81884704-ffffffff81884734: acpi_os_allocate (STB_LOCAL)
ffffffff8188548b-ffffffff818854bb: acpi_os_allocate (STB_LOCAL)
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
In drivers/acpi/acpica/evglock.c (ffffffff819895f6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8198d93a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81990dab)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81997819)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8199998e)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8199e2bf)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff819a394a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819aeed1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff819baabd)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff819bbd27)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff819bc527)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff819bcfbe)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff819c21c4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff819c7e30)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c7fd7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff819ca8b0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff819cacef)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff819cf020)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
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
In drivers/acpi/acpica/evglock.c (ffffffff819d0036)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff819d43ca)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff819d78ab)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff819de499)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff819e06e4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff819e4f8f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff819ea5fa)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5dc1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81a01c4f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a02ec7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81a036c7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81a04138)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a09514)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a0f234)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0f3f7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a11d10)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81a12158)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a164f0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
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
In drivers/acpi/acpica/evglock.c (ffffffff81a1ab66)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81a1effa)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81a2256b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81a29189)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81a2b3d4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81a2fcdf)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81a3538a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a40c11)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81a4cacf)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a4dd47)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81a4e567)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81a4efd8)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a54424)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a5a374)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a537)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a5cea0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81a5d2e8)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a616d0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/exconfig.c (ffff800010783a28)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffff800010786450)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffff800010787b2c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffff80001078a038)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffff80001078b8d0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffff800010791884)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffff8000107981dc)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffff800010798c40)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffff800010798ed4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffff80001079a76c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffff80001079cef8)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffff800010783a28-ffff800010783a54: acpi_os_allocate (STB_LOCAL)
ffff800010798ed4-ffff800010798f00: acpi_os_allocate (STB_LOCAL)
ffff80001079a76c-ffff80001079a7a8: acpi_os_allocate (STB_LOCAL)
ffff80001079cef8-ffff80001079cf30: acpi_os_allocate.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815e6aca)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815e881b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815e9da4)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815ec30a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815ed912)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815efb06)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815f1d7f)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6f08)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815fcd52)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815fd571)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815fd7a6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815fde3a)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815fff18)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff815e9da4-ffffffff815e9dcd: acpi_os_allocate (STB_LOCAL)
ffffffff815fd7a6-ffffffff815fd7cf: acpi_os_allocate (STB_LOCAL)
ffffffff815fde3a-ffffffff815fde6a: acpi_os_allocate (STB_LOCAL)
ffffffff815fff18-ffffffff815fff4d: acpi_os_allocate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815d2122)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815d3e49)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815d53c7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815d7923)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815d8f0d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815db0ea)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815dd31c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e20f2)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff815e827d)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815e8a97)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff815e8cc7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815e9313)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815eb405)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/nfit/core.c (ffffffff815f53ab)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_label_write
Direct callers:
  - drivers/acpi/nfit/core.c:pkg_to_buf
```
**Symbols:**

```
ffffffff815d53c7-ffffffff815d53eb: acpi_os_allocate (STB_LOCAL)
ffffffff815e8cc7-ffffffff815e8ceb: acpi_os_allocate (STB_LOCAL)
ffffffff815e9313-ffffffff815e9337: acpi_os_allocate (STB_LOCAL)
ffffffff815eb405-ffffffff815eb435: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff815f31d0-ffffffff815f31f4: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff815f1696)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815f4946)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815f6e3c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815fc385)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815fe0b0)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81601ca6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816056e7)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160e086)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81616f53)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81617c9b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff816180b1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8161882c)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8161c245)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81620452)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81620663)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81621a54)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816226e1)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81625279)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815f6e3c-ffffffff815f6e65: acpi_os_allocate (STB_LOCAL)
ffffffff816180b1-ffffffff816180da: acpi_os_allocate (STB_LOCAL)
ffffffff8161882c-ffffffff8161885c: acpi_os_allocate (STB_LOCAL)
ffffffff8161c245-ffffffff8161c27a: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff81621a54-ffffffff81621a7d: acpi_os_allocate (STB_LOCAL)
ffffffff816226e1-ffffffff8162270a: acpi_os_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void *acpi_os_allocate(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evglock.c (ffffffff8160b546)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160e7f6)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81610cec)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81616235)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81617f60)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8161bb56)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8161f597)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627f36)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (ffffffff81630e03)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81631b4b)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (ffffffff81631f61)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816326dc)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816360f5)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Direct callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8163a302)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8163a513)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8163b904)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8163c591)
Location: include/acpi/platform/aclinuxex.h:50
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8163f129)
Location: include/acpi/platform/aclinuxex.h:50
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81610cec-ffffffff81610d15: acpi_os_allocate (STB_LOCAL)
ffffffff81631f61-ffffffff81631f8a: acpi_os_allocate (STB_LOCAL)
ffffffff816326dc-ffffffff8163270c: acpi_os_allocate (STB_LOCAL)
ffffffff816360f5-ffffffff8163612a: acpi_os_allocate.constprop.0 (STB_LOCAL)
ffffffff8163b904-ffffffff8163b92d: acpi_os_allocate (STB_LOCAL)
ffffffff8163c591-ffffffff8163c5ba: acpi_os_allocate (STB_LOCAL)
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
