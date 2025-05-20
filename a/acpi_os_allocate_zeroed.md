# Function: <code>acpi_os_allocate_zeroed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a46e)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8147a8c0)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8148c9b6)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8148cf48)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8148fb7d)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81490255)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff814905e7)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81490eef)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81491c38)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff814920a9)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81492f09)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81493ae1)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81495880)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff814979f0)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81499cab)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b7ec)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8149d1a4)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff8149d509)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8149f0b4)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8149f682)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814a037f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff814a2ca5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff814a3d1d)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff814a4680)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff814a6c53)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff814a7b35)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff814a7e6e)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_SUB
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814a8fd6)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff814a962e)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff814aa396)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
**Symbols:**

```
ffffffff8148cf48-ffffffff8148cf77: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814905e7-ffffffff81490616: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8149f682-ffffffff8149f6b1: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814a6c53-ffffffff814a6c89: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814a7e6e-ffffffff814a7e9d: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814a8fd6-ffffffff814a900c: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8a26)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff814c8e88)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff814db7c1)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff814dbd59)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff814de981)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff814df046)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff814df3d8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff814dfcb5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff814e0a88)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff814e10c5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff814e1d08)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e28e4)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff814e4883)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff814e6d11)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff814e89fa)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea87b)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff814ec372)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff814ec74f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee538)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff814ee998)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef683)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff814f1fce)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff814f305f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff814f39c3)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff814f5dc2)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff814f6eb5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff814f71ef)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814f826c)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff814f88ca)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff814f95dc)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
**Symbols:**

```
ffffffff814dbd59-ffffffff814dbd88: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814df3d8-ffffffff814df407: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814ee998-ffffffff814ee9c7: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814f5dc2-ffffffff814f5df8: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814f71ef-ffffffff814f721e: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff814f826c-ffffffff814f82a2: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea96a)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff814eadcc)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff814fe0d0)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff814fe668)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81501249)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815019a9)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81501d3f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8150261b)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815033ee)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81503a2b)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81504647)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8150529d)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815070d7)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81509565)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8150b24e)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8150d103)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8150ebf8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff8150f010)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8150f443)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81510fa0)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81511428)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815120d8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81514b1c)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81515bad)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81516511)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81518985)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81519a78)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81519e0a)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8151ac7a)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8151b2d8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8151c15f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
**Symbols:**

```
ffffffff814fe668-ffffffff814fe697: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81501d3f-ffffffff81501d6e: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81511428-ffffffff81511457: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81518985-ffffffff815189bb: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81519e0a-ffffffff81519e39: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8151ac7a-ffffffff8151acb0: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f67f2)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff814f6e31)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8150e598)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8150eb3f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81511724)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81511e81)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8151221b)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81512b67)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8151392c)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81513f74)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81514b7f)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81515866)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815176c1)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81519b96)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8151b87d)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d7d6)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8151f2c2)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff8151f6e8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8151faf5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81521656)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81521af4)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815225a5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815253ca)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8152642e)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81526d79)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815291a6)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8152a2a8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8152a63a)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8152b495)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8152b9da)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8152c975)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
**Symbols:**

```
ffffffff8150eb3f-ffffffff8150eb6e: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8151221b-ffffffff8151224a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81521af4-ffffffff81521b23: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815291a6-ffffffff815291dc: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8152a63a-ffffffff8152a669: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8152b495-ffffffff8152b4cb: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8152b9da-ffffffff8152ba09: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537606)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81537edb)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff8154f7a2)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81552f13)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81553d5b)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81555346)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815590a8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81559da7)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8155a2c1)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8155b239)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8155c8c7)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8155d3e9)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8155e9bc)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8156023a)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8156454a)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81567e51)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8156b2e6)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e521)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81571c12)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815724e1)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81572cf7)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81575776)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81575f51)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81576d29)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8157b517)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8157d0df)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8157e1df)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815811f8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81583375)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81583986)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81585354)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81585de5)
Location: include/acpi/platform/aclinuxex.h:89
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815876d0)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81588fe0)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8158c5b8)
Location: include/acpi/platform/aclinuxex.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff8155a2c1-ffffffff8155a2f0: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81575f51-ffffffff81575f80: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815811f8-ffffffff8158122e: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81583986-ffffffff815839b5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81585354-ffffffff8158538a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81585de5-ffffffff81585e14: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d175)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8156db33)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff81586067)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81589865)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8158a6ab)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff8158bdca)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8158fbc3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815908a7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81590e67)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81591db6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8159346f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81593f86)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815955a1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81596ef1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8159b2a1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8159eb15)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815a1f48)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815a51fe)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815a8818)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815a8d8a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815a9c64)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815ac6ec)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815acec6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815adcad)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815b26f1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815b42b5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815b53be)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815b83d4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ba512)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815bab23)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815bc509)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815bcf9a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815be875)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815c015e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff815c38cc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff81590e67-ffffffff81590e96: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815a8d8a-ffffffff815a8db9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815acec6-ffffffff815acef5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815b83d4-ffffffff815b840a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815bab23-ffffffff815bab52: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815bc509-ffffffff815bc53f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815bcf9a-ffffffff815bcfc9: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584d35)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815856dc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff8159e389)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815a1da4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815a2c69)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815a4399)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815a8248)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815a8f2f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815a9512)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815aa455)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815abb0d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ac68a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815adcaf)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815af5f5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815b3793)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815b705b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815bac08)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815bdbba)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815c16a6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815c1c2f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815c2b0d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815c56e3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815c5ebd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6c9c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815cb8fb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815cd671)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815ce77a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815d1793)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815d396c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815d3f7d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815d594f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815d63e0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815d7cdc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815d95c2)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff815dcdaf)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff815a9512-ffffffff815a9541: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815c1c2f-ffffffff815c1c5e: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815c5ebd-ffffffff815c5eec: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815d1793-ffffffff815d17c9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815d3f7d-ffffffff815d3fac: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815d594f-ffffffff815d5985: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815d63e0-ffffffff815d640f: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5945)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815b60e0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff815cf720)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815d1f38)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815d3431)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815d4309)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815d5a99)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815d99a7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815da6be)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815dacad)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815dbc2f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815dd319)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ddeb0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815df4da)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e0e81)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815e52c4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815e894e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815ec7da)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef7c1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f02f4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815f305e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815f35f9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815f4514)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f6fde)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f77aa)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f8648)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815fd0ac)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815feec2)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815fffe8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8160306c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816052ea)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816058fc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816072f0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81607d9d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81609701)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8160b0d5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8160e895)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff815b60e0-ffffffff815b6109: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815cf720-ffffffff815cf749: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815dacad-ffffffff815dacdc: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815e894e-ffffffff815e8984: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815f35f9-ffffffff815f3628: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815f77aa-ffffffff815f77d9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8160306c-ffffffff816030a2: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816058fc-ffffffff8160592b: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816072f0-ffffffff81607326: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81607d9d-ffffffff81607dcc: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6b75)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815d7310)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff815f09a0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815f31a8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815f46a5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815f5581)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815f6d11)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815fac5f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815fb9fe)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815fbfed)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815fcf72)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815fe65c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ff1f3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160081d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81602216)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81606659)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81609ce3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8160db6f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81610c4f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81611782)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816144fd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81614a98)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816159b3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81618484)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81618c50)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81619aee)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8161e556)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8162036c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81621492)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81624516)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81626794)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81626da6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8162878b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81629238)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8162aba2)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8162c576)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8162fd3a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff815d7310-ffffffff815d7339: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815f09a0-ffffffff815f09c9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815fbfed-ffffffff815fc01c: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81609ce3-ffffffff81609d19: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81614a98-ffffffff81614ac7: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81618c50-ffffffff81618c7f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81624516-ffffffff8162454c: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81626da6-ffffffff81626dd5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8162878b-ffffffff816287c1: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81629238-ffffffff81629267: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816808a5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff816810b0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff8169cc40)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8169ee48)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816a072e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff816a152b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a2986)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816a6d81)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7b21)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816a8126)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a9121)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816aa36f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816ab427)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816aca51)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ae4aa)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816b262d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b5ffb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b9ecd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816bd062)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff816bdcb9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816c0a0b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816c0fb7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816c1ed4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4285)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5168)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5fb1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816caab6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816cc8fb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816cda88)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816d0c56)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816d2f44)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816d3567)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d4f4f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816d5a19)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff816d734b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8d67)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816dc719)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff816810b0-ffffffff816810d9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8169cc40-ffffffff8169cc69: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8169ee48-ffffffff8169ee77: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816a152b-ffffffff816a155a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816a2986-ffffffff816a29b5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816a8126-ffffffff816a8155: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816b262d-ffffffff816b265c: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816b5ffb-ffffffff816b6031: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c0fb7-ffffffff816c0fe6: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c4285-ffffffff816c42b4: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c5168-ffffffff816c5197: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d0c56-ffffffff816d0c8c: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d3567-ffffffff816d3596: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d4f4f-ffffffff816d4f85: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d5a19-ffffffff816d5a48: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f395)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8169fa00)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff816b9aa0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff816bc660)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816bdf46)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff816bed32)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816c017c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816c4577)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816c5317)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816c590b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816c69a5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816c7c21)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816c8d66)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ca390)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cbde9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816cff58)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816d390f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff816d46f4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816d78c5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816dac04)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816de584)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816deb1f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816dfa3c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816e22c6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816e319b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e3fd3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816e8acb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816ea912)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816eba8e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816eec34)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816f0f22)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816f1534)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816f2f0b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816f39c4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff816f52f1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f6cf6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816fa7bd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff8169fa00-ffffffff8169fa29: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816b9aa0-ffffffff816b9ac9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816bc660-ffffffff816bc68f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816bed32-ffffffff816bed61: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c017c-ffffffff816c01ab: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c590b-ffffffff816c593a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816cff58-ffffffff816cff87: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d390f-ffffffff816d3945: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816deb1f-ffffffff816deb4e: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816e22c6-ffffffff816e22f5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816e319b-ffffffff816e31ca: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816eec34-ffffffff816eec6a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816f1534-ffffffff816f1563: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816f2f0b-ffffffff816f2f41: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816f39c4-ffffffff816f39f3: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682045)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81682a7d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff8169bb17)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8169eb1a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816a0026)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff816a0ef8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a21fe)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816a660a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7399)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816a798d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a89d9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816a9c3a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816aad4c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac371)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816addb5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816b2222)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b58b7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff816b668d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b985a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcba1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816c0470)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816c0a0b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816c1927)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c41b6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5070)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5ea5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816ca990)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816cc824)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd96e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816d0ae9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816d2dca)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff816d33dc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d4db4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816d5861)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff816d718e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8b6e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816dc5f4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff816a21fe-ffffffff816a222d: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816a798d-ffffffff816a79bc: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816b58b7-ffffffff816b58ed: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c0a0b-ffffffff816c0a3a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c41b6-ffffffff816c41e5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816c5070-ffffffff816c509f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d0ae9-ffffffff816d0b1f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d33dc-ffffffff816d340b: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d4db4-ffffffff816d4dea: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816d5861-ffffffff816d5890: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f7175)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff816f7bd5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff817119cc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8171511a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8171663e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8171774c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81718b34)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8171d0fd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff8171dfe0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8171e5d4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8171f620)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81720894)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff817219a6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8172308e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81724b74)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff817290b0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8172c8e0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8172d6b6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff817308aa)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81733e16)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81737725)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81737cc0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81738c14)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8173b4ea)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8173c3d5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173d20a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81741d32)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81743cf4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81744e3e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff817481c9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8174a60e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8174ac20)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8174c7db)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8174d288)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8174ecfa)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81750722)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff817545af)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff81718b34-ffffffff81718b63: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8171e5d4-ffffffff8171e603: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8172c8e0-ffffffff8172c916: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81737cc0-ffffffff81737cef: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8173b4ea-ffffffff8173b519: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8173c3d5-ffffffff8173c404: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff817481c9-ffffffff817481ff: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8174ac20-ffffffff8174ac4f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8174c7db-ffffffff8174c811: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8174d288-ffffffff8174d2b7: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824075)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81824b60)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff81840a6a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8184474d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8184615e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff818471c7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff8184883f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8184d108)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff8184e0a9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8184e6b9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8184f79f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81851058)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8185189d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8185355e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff818551af)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8185959c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8185d26a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8185e085)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff818611c0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81864d9d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff818689fe)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81868feb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8186a04c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8186cb15)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8186db4a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186e847)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81873740)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8187587c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8187643e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff8187a2db)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8187cab8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8187d163)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8187eec4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8187fa0d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81881690)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8188303a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81887568)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff8184474d-ffffffff81844783: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff818471c7-ffffffff818471fd: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8184883f-ffffffff81848875: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8184e6b9-ffffffff8184e6ef: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8185189d-ffffffff818518d3: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8185959c-ffffffff818595d2: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8185d26a-ffffffff8185d2a0: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff818611c0-ffffffff818611f6: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81868feb-ffffffff81869021: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8186cb15-ffffffff8186cb4b: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8186db4a-ffffffff8186db80: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8186e847-ffffffff8186e87d: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81873740-ffffffff81873776: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8187643e-ffffffff81876474: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8187a2db-ffffffff8187a311: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8187d163-ffffffff8187d199: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8187eec4-ffffffff8187eefa: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8187fa0d-ffffffff8187fa43: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8188303a-ffffffff81883070: acpi_os_allocate_zeroed (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff81955425)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff81956f25)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff819774af)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff8197c292)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8197db4c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff8197efbb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81981263)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff819860bb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81986efe)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8198814d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81989120)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8198ae3b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8198c0aa)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8198db40)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198fc97)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8199577e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81999bc9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8199a9d1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8199e4f5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff819a2d46)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff819a76d7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff819a8558)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff819a9129)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819acdd9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819ae116)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819aeb4a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff819b49c0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff819b7124)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff819b8804)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff819bd873)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff819c00e0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff819c0ef1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff819c3819)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff819c3bf5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff819c60a5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c83b5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff819cd67b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
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
In drivers/acpi/osl.c (ffffffff8199b825)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff8199d33a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff819bde9a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff819c2d32)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff819c45fc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff819c5a6d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff819c7cc1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff819ccaeb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff819cd93b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff819ceb8d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff819cfb60)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff819d18bb)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff819d2b2a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff819d45d0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d6737)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff819dc3a1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff819e09b0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff819e175f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff819e51c5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff819e99f6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff819ee3f7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff819ef24a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff819effd9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819f3ca8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819f4fd6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5a1a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff819fb9c0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff819fe274)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff819ff966)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81a04a63)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a072e0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81a08241)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a0abc9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a0afa5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81a0d4a5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0f7d5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a14b0f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e3d45)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff819e53aa)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff81a0876a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff81a0d752)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0f01c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81a104bd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81a12711)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81a16a70)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Direct callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81a183db)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81a1965d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81a1a660)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81a1c41b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81a1d71e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81a1f230)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a213c7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81a27091)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81a2b6d0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff81a2c47f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81a2ff15)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81a34744)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81a391b7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81a3a03a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81a3adc9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3eac8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3feb6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a4086a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81a46810)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81a490c4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4a7e6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff81a4f903)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a52180)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81a53121)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a55b69)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a55f45)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81a58475)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a945)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a5f6e0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff81a16a70-ffffffff81a16adf: acpi_os_allocate_zeroed.constprop.0 (STB_LOCAL)
ffffffff81a5f6e0-ffffffff81a5f74f: acpi_os_allocate_zeroed.constprop.0 (STB_LOCAL)
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
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff8000107640cc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffff800010764c18)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/acpica/dsfield.c (ffff80001077d27c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffff80001077df68)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffff80001077e724)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffff80001077f6dc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffff800010781a0c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evregion.c (ffff800010782610)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffff800010782afc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/exfldio.c (ffff800010785440)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffff800010787abc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffff80001078a164)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffff80001078b4e4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/nsaccess.c (ffff80001078bacc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffff80001078d330)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffff80001078d7d0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffff80001078e278)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffff80001078fd90)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffff800010790908)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffff8000107915a0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffff800010794ae0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffff800010795efc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffff800010796cd0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffff80001079a72c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffff80001079bc9c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffff80001079c19c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffff80001079d318)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffff80001079da08)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffff80001079f25c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
**Symbols:**

```
ffff800010782afc-ffff800010782b2c: acpi_os_allocate_zeroed (STB_LOCAL)
ffff800010787abc-ffff800010787afc: acpi_os_allocate_zeroed (STB_LOCAL)
ffff80001078d7d0-ffff80001078d800: acpi_os_allocate_zeroed (STB_LOCAL)
ffff80001078fd90-ffff80001078fdc0: acpi_os_allocate_zeroed (STB_LOCAL)
ffff800010790908-ffff800010790938: acpi_os_allocate_zeroed (STB_LOCAL)
ffff80001079a72c-ffff80001079a76c: acpi_os_allocate_zeroed (STB_LOCAL)
ffff80001079c19c-ffff80001079c1cc: acpi_os_allocate_zeroed (STB_LOCAL)
ffff80001079d318-ffff80001079d358: acpi_os_allocate_zeroed (STB_LOCAL)
ffff80001079da08-ffff80001079da38: acpi_os_allocate_zeroed (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca305)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815ca8c0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff815df630)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815e1116)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e1c7e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815e2326)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815e3229)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815e5246)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815e5a65)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815e5eb7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815e67f8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815e75e1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815e7cc5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815e88df)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e9707)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815eb482)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815ed8b3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815efbe0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815f195a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f1f92)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815f34ae)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815f382b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815f408d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f5c63)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f60de)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6c50)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815f9d37)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815fafc1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815fba69)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815fde04)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815fefbe)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815ff39e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8160024a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816007b2)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81601a9b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
**Symbols:**

```
ffffffff815ca8c0-ffffffff815ca8e9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815df630-ffffffff815df659: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815e5eb7-ffffffff815e5ee6: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815ed8b3-ffffffff815ed8e9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815f382b-ffffffff815f385a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815f60de-ffffffff815f610d: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815fde04-ffffffff815fde3a: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815ff39e-ffffffff815ff3cd: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8160024a-ffffffff81600280: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816007b2-ffffffff816007e1: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3385)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815b3bc7)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff815cae19)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815cc796)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815cd2f9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815cd99c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815ce89a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815d08b2)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815d10cc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815d1519)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815d1e55)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815d2c34)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815d3303)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815d3f0a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d4d2f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815d6aa0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815d8eba)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815db1ba)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcf01)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815dd52a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815dea3c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815dedb4)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815df611)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815e0d89)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815e1638)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e23bd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815e5271)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815e64f6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815e6f99)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff815e9528)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ea4b5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff815ea890)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815eb8d5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815ebc77)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff815ecf56)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
**Symbols:**

```
ffffffff815d1519-ffffffff815d1543: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815d8eba-ffffffff815d8ee4: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815dedb4-ffffffff815dedde: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815e0d89-ffffffff815e0db3: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815e1638-ffffffff815e1662: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815e9528-ffffffff815e9552: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815ea890-ffffffff815ea8ba: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815eb8d5-ffffffff815eb8ff: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815ebc77-ffffffff815ebca1: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cae55)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815cb5f0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff815e4c80)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff815e7488)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e8985)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff815e9861)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815eaff1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815eef3f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815efcde)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815f02cd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815f1252)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815f293c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815f34d3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815f4afd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f64f6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815fa939)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815fdfc3)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81601e4f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81604f2f)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81605a62)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816087dd)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81608d78)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81609c93)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8160c764)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8160cf30)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160ddce)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81612836)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8161464c)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81615772)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816187f6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8161aa74)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff8161b086)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8161ca6b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8161d518)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff8161ee82)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81620856)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8162401a)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff815cb5f0-ffffffff815cb619: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815e4c80-ffffffff815e4ca9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815f02cd-ffffffff815f02fc: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815fdfc3-ffffffff815fdff9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81608d78-ffffffff81608da7: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8160cf30-ffffffff8160cf5f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816187f6-ffffffff8161882c: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8161b086-ffffffff8161b0b5: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8161ca6b-ffffffff8161caa1: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8161d518-ffffffff8161d547: acpi_os_allocate_zeroed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_allocate_zeroed(acpi_size size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4cf5)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/acpi/utils.c (ffffffff815e5490)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/utils.c:acpi_extract_package
```
```
In drivers/acpi/x86/apple.c (ffffffff815feb30)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsfield.c (ffffffff81601338)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_field
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81602835)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (ffffffff81603711)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81604ea1)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81608def)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81609b8e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8160a17d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8160b102)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8160c7ec)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8160d383)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160e9ad)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816103a6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816147e9)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81617e73)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8161bcff)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8161eddf)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff8161f912)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8162268d)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81622c28)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81623b43)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81626614)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81626de0)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627c7e)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8162c6e6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8162e4fc)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8162f622)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/utcopy.c (ffffffff816326a6)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81634924)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81634f36)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8163691b)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816373c8)
Location: include/acpi/platform/aclinuxex.h:55
Inline: False
Direct callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81638d32)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8163a706)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8163deca)
Location: include/acpi/platform/aclinuxex.h:55
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
```
**Symbols:**

```
ffffffff815e5490-ffffffff815e54b9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff815feb30-ffffffff815feb59: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8160a17d-ffffffff8160a1ac: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81617e73-ffffffff81617ea9: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81622c28-ffffffff81622c57: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81626de0-ffffffff81626e0f: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816326a6-ffffffff816326dc: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff81634f36-ffffffff81634f65: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff8163691b-ffffffff81636951: acpi_os_allocate_zeroed (STB_LOCAL)
ffffffff816373c8-ffffffff816373f7: acpi_os_allocate_zeroed (STB_LOCAL)
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
