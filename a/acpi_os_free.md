# Function: <code>acpi_os_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814290b3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff814577a9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff814581d8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8147a5ce)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff8147b092)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff8147be68)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff81480b52)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff8148a48f)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_free_properties
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8148ca1e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff8148e1f7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8148fdcf)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff814902a7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff814906a1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8149104c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81491ce6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81492095)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff81492643)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81492ad3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81493ba9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81494206)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdebug.c (ffffffff814950e7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdebug.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/exdebug.c:acpi_ex_stop_trace_method
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81495a23)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81496641)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81497920)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81499ca3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8149a85f)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b92f)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8149cd11)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8149d243)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff8149d5b0)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8149ee79)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8149f8da)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814a00e5)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff814a2d04)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff814a3dc1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff814a4154)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff814a46f1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff814a5118)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff814a6284)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff814a7295)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
```
In drivers/acpi/acpica/uterror.c (ffffffff814a79f4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff814a7c98)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff814a8604)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814a9337)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff814a95e4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81527467)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
```
```
In drivers/iommu/dmar.c (ffffffff8153387c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816207c4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662573)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8167d906)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474258)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff814a43d2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff814a4e7c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c8b9c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff814c969a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff814ca53f)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff814cf4f6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff814d9c5b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff814db82b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff814dd002)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff814debd3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff814df098)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff814df687)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff814dfe6c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff814e0b48)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff814e0fc1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff814e142d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff814e18c3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e29b7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff814e3368)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff814e4a24)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff814e5950)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff814e6c23)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff814e89f2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff814e8da1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff814e975c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea9c2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff814ebc4a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nseval.c (ffffffff814ec023)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff814ec47a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff814ec7f6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee77b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff814eebf1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef85e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff814f202e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff814f30fc)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff814f3497)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff814f3afd)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff814f449d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff814f570c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff814f68af)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff814f6d74)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff814f7019)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff814f78ca)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814f85c9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff814f89c1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff8157aaf9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/iommu/dmar.c (ffffffff81588116)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816811c2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c27c8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff816de696)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81496798)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff814c61e2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff814c6cfc)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814eaae0)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff814eb5de)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff814ec45b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff814f1460)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff814fc507)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff814fe13a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff814ff8fa)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8150149b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815019fb)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81501fee)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815027d2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815034ae)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81503927)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff81503d6c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81504202)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81505370)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81505c0a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81507278)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815081a4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81509477)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8150b246)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8150b5a6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8150bfe4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8150d24a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff8150e4d0)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8150e8a9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8150ed00)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff8150f0b7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8150f4d1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81510bf6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81511681)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815122b3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81514b7c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81515c4a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff81515fe5)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8151664b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff81517188)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815182cf)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff81519472)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff81519937)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81519bdc)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff8151a4e6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8151afd7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8151b3cf)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff815a7609)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/iommu/dmar.c (ffffffff815b57d6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816aeef2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f0788)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ea56)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0306)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff814d080b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff814d0c75)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814f6979)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff814f7752)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff814f849c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff814f92d6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff814fee10)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff8150c569)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8150e602)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff8150fde3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81511970)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81511ed3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815124ca)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81512d1e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815139f4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81513e6c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815142ab)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81514b3c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8151593a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81516215)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8151787a)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815187df)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81519aac)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8151b875)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8151bbd6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8151c609)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d91d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff8151eb87)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nseval.c (ffffffff8151ef69)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8151f3ca)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff8151f78d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8151fb88)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815212ac)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81521de2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8152274d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81525427)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815264cb)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff815269c7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81526eb3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff815279a3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81528af7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff815299f2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff8152a167)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8152a40c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff8152ad0d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8152b7f2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8152bbc1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff815bd28d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/iommu/dmar.c (ffffffff815cb636)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816c4110)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81706013)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817246b8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/gpio/gpiolib-acpi.c (ffffffff814ded6c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81510a3c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff81510eae)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815379c9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815389f2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff81539ccc)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff8153ab46)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff81540e10)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff8154f169)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff8154f6aa)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff81551153)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81552f7e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81555109)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff81555d57)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8155947d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81559df9)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8155a6f6)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8155b4ed)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8155c9c8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8155d2a2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff8155daac)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8155e8da)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8156033b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81561164)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff8156293c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8156472c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8156661f)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81567d1e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8156b2de)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8156b9d3)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8156cb23)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e689)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff8156ef29)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff81570477)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff8157054e)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815714cf)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8157183d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff81572650)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81572dd8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff81574a35)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81575b53)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815763bf)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81576ed1)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8157b59c)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8157d1a4)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff8157daf0)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8157e3ac)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff8157f28f)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81580a70)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff81582621)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff81583217)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81583550)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff815842d7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff81584b52)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815859f2)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81585fcc)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81588bc7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815894a8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81589575)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8158ac96)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8158ad5b)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff8158b767)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8158c658)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff8158d625)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8158d6bc)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff8162371d)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/iommu/dmar.c (ffffffff81632406)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8172fef8)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817771e7)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795b88)
Location: include/acpi/platform/aclinuxex.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150e2c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81545b1d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff8154603e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8156d555)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff8156e7b2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff8156fa42)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff815709cc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff81576cd9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff81585a09)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff81585f2b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff81587a5c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815898d6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff8158bb38)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff8158c838)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8158ff98)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815908ff)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8159128f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81592069)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81593570)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81593e3f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff81594649)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815954bf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81596ff2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81597e55)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff8159963b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8159b488)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8159d2d0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8159e9d7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815a1f36)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff815a262b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815a376b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815a5369)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815a5c04)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff815a7162)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff815a7239)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815a8213)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815a8443)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815a9507)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff815a95bd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815a9d4f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff815ab9aa)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815acac5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815ad2df)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815ade3a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff815af90b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815b2776)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815b437a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff815b4cd1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815b558b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff815b6487)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815b7c64)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff815b97d9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff815ba3d9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ba6ed)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff815bb473)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff815bbcc3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815bbff7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815bcba8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815bd17c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff815bfd42)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815c0621)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff815c06ee)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815c1f8c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff815c2051)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff815c2a64)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff815c396c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff815c496d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815c4a04)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff8165d4ec)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8165fca7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8166d6fb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8176ef84)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7f44)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8662)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815232f0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81541b82)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff8155c5de)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81585115)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff81586372)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff81587622)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff81588594)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8158e8c9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/property.c (ffffffff8159df46)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff8159e25b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828d8ab3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff8159ff6d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815a1e15)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815a4107)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff815a4e78)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815a861d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815a8f87)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815a993a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815aa70b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815abc0e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ac5bc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815acd4c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815adbcd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815af6f6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815b0559)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff815b1d58)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815b397a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815b5814)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815b6f1d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815babf6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff815bb2ee)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815bdd25)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815be2ae)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815be90b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff815bfeb2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff815bff89)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815c10a6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815c12d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815c23af)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff815c2465)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815c2c83)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff815c49ad)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815c5abc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815c62d6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6e2b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff815c8993)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff815ca05e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815cb980)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815cd736)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff815ce08d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815ce947)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff815cf847)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815d1027)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff815d2baa)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff815d3833)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815d3b47)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff815d48c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff815d5109)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815d543d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815d5fee)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815d65c2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff815d91b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff815d9a92)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff815d9b5f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815db412)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff815db4d7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff815dc0a2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff815dce4f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff815ddec3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815ddf5a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff8167b9ac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e1f7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8168bb0b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81793602)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de646)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff846)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81551730)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81571224)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff8158c900)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b5d35)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815b7005)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815b8210)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff815b924e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815bf626)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffffffff815c6b7e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff815cf466)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff815cf7bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828f2927)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff815d1546)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815d349f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815d5802)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff815d658a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815d9d88)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815da716)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815db103)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815dbeef)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815dd419)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ddde0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815de562)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815df3f6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e0f82)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815e1dd9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff815e3615)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815e54b9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815e7369)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815e8aaf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815ec7c8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff815ecec8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef92d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815efeb4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f08a5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff815f1b30)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff815f1c0d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815f2a82)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815f2cb0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815f3d8a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff815f3e40)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815f468a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff815f6294)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f739e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f7bd2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f87d8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff815fa0fe)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff815fb812)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815fd133)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815fef88)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff815ff8f6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816001b5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff816010cf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816028ea)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff816044b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff816051b7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816054c3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff81606241)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff81606aa2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81606dd5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81607996)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81607f8f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8160acb0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8160b5a5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff8160b672)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8160cf26)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8160cfe4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff8160db7c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8160e932)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff8160f9c2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8160fa59)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff816b25e4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b4efb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816c34fb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff817d1f81)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181f0b4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840a3e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81572cf0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff815925d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff815ae520)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815d6f65)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815d8235)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815d94a0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff815da48e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815e08e6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffffffff815e7dae)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff815f06e6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff815f0a3b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828fbb31)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff815f27b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815f4713)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815f6a7a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff815f7802)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815fb041)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815fba56)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815fc443)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815fd232)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815fe75c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815ff123)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815ff8a5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81600739)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81602317)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff8160316e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff816049aa)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8160684e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816086fe)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81609e44)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8160db5d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8160e25d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81610dbb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81611342)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81611d33)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff81612fc4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff816130a1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff81613f20)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8161414e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81615229)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff816152df)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81615b2d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff81617738)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81618844)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81619078)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81619c7e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff8161b5a5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff8161ccbc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8161e5dd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81620432)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff81620da0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8162165f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff8162257a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81623d95)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff8162595d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff81626661)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8162696d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff816276dc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff81627f3d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81628270)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81628e31)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8162942a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8162c151)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8162ca46)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff8162cb13)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8162e3c7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8162e485)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff8162f01d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8162fdd7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff81630e6b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81630f02)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff816d52c4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7bdb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816e644b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81802e51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81850375)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8187239e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81617c15)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81640661)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_optimize_delay
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff81657780)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81680c95)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff816821c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff816833e0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff81683fa2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff816898ea)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_init_power_state
```
```
In drivers/acpi/pci_root.c (ffffffff8169374a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff8169c966)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff8169ccdb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff82d12379)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff8169e7b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816a079c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a2b2a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff816a38f8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816a7163)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7b79)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816a86ae)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a93e1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816aa46f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816ab357)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff816abad9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac732)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ae5ab)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816af414)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff816b0c4c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816b2b3b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816b4a01)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b615c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b9ebb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff816ba5bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816bd1ce)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd9f6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff816be264)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff816bf4e1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff816bfcbf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff816c0436)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816c065c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816c1673)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff816c1800)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816c204e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff816c3c30)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4d51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5459)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c6141)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff816c7b21)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff816c9245)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816cab3c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816cc9c1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff816cd1a7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816cdc5c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff816cebb3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816d047d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff816d20fb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff816d2e11)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816d311d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff816d3e9b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff816d46d7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d4a0a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d56da)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816d5c06)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d893e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d923e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff816d930b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816dabcb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816dac89)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff816db8c2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816dc7b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff816dd8c8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dd95c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81789594)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c2f9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c949)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff818d3597)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819467be)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e399)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81666a71)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_optimize_delay
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff81677bd0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8169f785)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff816a0985)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff816a1d62)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff816a74aa)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_init_power_state
```
```
In drivers/acpi/pci_root.c (ffffffff816b123a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff816b9806)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff816b9b3b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff816ba2b0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff82fffe4d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff816bbfdf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816bdfb4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816c0320)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff816c10ee)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816c4959)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816c536f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816c5f1e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816c6c65)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816c7d21)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816c8c96)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff816c9418)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ca071)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816cbeea)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816ccd50)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff816ce588)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816d0466)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816d2326)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816d3a70)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff816d47f4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816d78b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff816d7fb3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816dad70)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816db598)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff816dbdd2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff816dd05a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff816dd838)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff816ddfaf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816de1d5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816df1db)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff816df368)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816dfbb6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff816e1c82)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816e2d95)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816e348c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e4163)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff816e5b43)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff816e726b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816e8b51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816ea9d8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff816eb1be)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816ebc62)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff816ecbb9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816ee47d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff816f00d9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff816f0def)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816f10fb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff816f1e68)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff816f26a4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816f29d7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816f3696)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816f3bb1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816f68fc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f71cd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff816f729a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816f8ba1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816f8c4e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff816f9903)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816fa85a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff816fb96c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816fba00)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff817a04ce)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2889)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa619)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff818dd937)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c71e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81621ed9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff816493e4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff8165a23f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81682425)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff816834f5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff81684b52)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff8168a0c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
```
```
In drivers/acpi/pci_root.c (ffffffff8169340a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff8169b7c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff8169ba1b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff8169c1ed)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff8320af35)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff8169e10c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816a0094)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a23b1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff816a3184)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816a69dd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff816a73f1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff816a7e88)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a8c99)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff816a9d3a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff816aac7c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff816ab3f9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac052)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816adeb6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816aed1c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff816b054b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816b2415)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff816b42cd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff816b5a18)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff816b678d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff816b9848)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff816b9f45)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcd0c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd4dd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff816bdcad)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff816bef4a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff816bf727)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff816bfe9b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816c00c1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816c10c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff816c1253)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff816c1aa1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff816c3b72)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816c4c6b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5361)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c6035)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff816c7a26)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff816c912e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816caa16)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff816cc8ea)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff816cd0d0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff816cdb3b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff816cea80)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff816d0332)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff816d1f3e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff816d2c96)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff816d2fa3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff816d3d0f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff816d4555)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d4888)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d5452)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816d5a4f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d8753)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d9045)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff816d9112)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816daa16)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff816daac3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff816db73f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816dc691)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff816dd78f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dd823)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81783191)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785586)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d38f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff818c0cdc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81920303)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8192feed)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a8759)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff816912dc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff816baf44)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff816cc588)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff816f7595)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff816f8915)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff816f9e12)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff816ff5b4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
```
```
In drivers/acpi/pci_root.c (ffffffff81708f5a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff81711666)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff817118d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff817120cd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff832f36aa)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff8171470c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff817166ac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81718ce7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff81719b00)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8171d4d0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff8171e038)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8171eacf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8171f8e0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81720994)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff817218d6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff81722053)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81722d6f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81724c75)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81725adb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff8172736d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff8172934a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8172b2ac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8172ca41)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8172d7b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81730898)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff81730f95)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81733f96)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8173476c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81734f3c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff817361ff)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff817369dc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff81737150)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81737376)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff817383b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff81738540)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81738d8e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff8173aea6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8173bfd0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8173c6c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173d39a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff8173ed91)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff817404d0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81741db8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81743dba)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff817445a0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8174500b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff817460f0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81747a12)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff8174977d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff8174a4da)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8174a7e7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff8174b5b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff8174be2c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8174c1fc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8174ce79)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8174d4b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81750307)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81750bda)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81750ca7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff817526b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff817527a5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff81753696)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8175464c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff8175587f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81755913)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81809b91)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180c0c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff81814b13)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8195741c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2fa3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d31bd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55b86)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b0821)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pcie/edr.c (ffffffff817dd61f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/pci-acpi.c (ffffffff817e0547)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff817f2d66)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff818244e5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff81825197)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_check_dsm
```
```
In drivers/acpi/device_sysfs.c (ffffffff81827172)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff8182d072)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:__acpi_device_add
```
```
In drivers/acpi/pci_root.c (ffffffff8183732a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff81840687)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff8184098c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff8184141d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff834ab864)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff818440b7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff818461ca)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81848a0c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff81849852)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff8184d4e7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff8184e100)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8184ebd1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8184fa70)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81851151)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81851f4b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff818524af)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff818531ff)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff818552bd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81855e63)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff81857b5f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81859b99)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8185bbff)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff8185d3c9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8185e178)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff818613f2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff81861b90)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81864f27)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8186577e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81865f81)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff818673bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff81867bb1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff818683c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81868600)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81869731)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff818698d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff8186a1c7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff8186c4a3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8186d6b4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8186e4c2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186ece4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff81870617)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff81871dca)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8187386d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81875939)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff8187634b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81876d56)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff81877f44)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81879a70)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff8187bb61)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff8187c942)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8187cc9e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff8187db08)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff8187e44c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8187e84e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8187f5b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8187fc47)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81882ef9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff818837ca)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff818838a5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81885445)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81885546)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff81886487)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81886fa0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff818888f6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff818889ae)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81949b02)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c715)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff81955a32)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
```
```
In drivers/base/physical_location.c (ffffffff819b48e9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81ab1120)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b233fd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35a68)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc53d7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
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
In drivers/gpio/gpiolib-acpi.c (ffffffff818ca391)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pcie/edr.c (ffffffff81900067)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/pci-acpi.c (ffffffff81903507)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff8191b476)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81955915)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff81956357)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/utils.c:acpi_get_subsystem_id
```
```
In drivers/acpi/device_sysfs.c (ffffffff81959062)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff8195fd9f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/acpi/pci_root.c (ffffffff8196c58d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff8197708f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_free_device_properties
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff819773bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff81977ebd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff83ee3e9e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff8197b6ff)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff8197dbb4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81980c30)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff81981dbb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81986510)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81986f51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff819882e5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81989457)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8198af09)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8198c127)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff8198c73d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8198d72f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198fdc0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81990e27)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff81993299)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff819956e1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81997cb9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81999a02)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff8199acbd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8199e53a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8199ee25)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff819a2dcd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff819a39ad)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff819a476b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff819a5bbc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff819a64fd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff819a6a9d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff819a7085)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff819a860b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff819a896c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff819a920b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff819abdbf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819ad2f9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819add6d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819aef3a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff819b0e7a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff819b271b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff819b4a70)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff819b7190)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff819b7b96)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff819b8b12)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff819ba1fc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff819bc29c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff819bfb51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff819bfef1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff819c01c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff819c1433)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff819c2040)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff819c2523)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff819c356a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff819c3d5f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff819c7e14)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c8877)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff819c89a4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff819caa53)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff819cacce)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff819cc076)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff819ccec5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff819cee1f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff819cef65)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81aad10c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0935)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abc542)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
```
```
In drivers/base/physical_location.c (ffffffff81b298d0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81c391c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5d08)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccab9b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/platform/x86/intel/pmc/tgl.c (ffffffff81d6f2cb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
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
In drivers/gpio/gpiolib-acpi.c (ffffffff8190d430)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pcie/edr.c (ffffffff819435e7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/pci-acpi.c (ffffffff81946ba7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff8195ea86)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8199bd15)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff8199c757)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/utils.c:acpi_get_subsystem_id
```
```
In drivers/acpi/device_sysfs.c (ffffffff8199f4d2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff819a618f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/acpi/pci_root.c (ffffffff819b2b0c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff819bd98f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_free_device_properties
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff819bddac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff819be79d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff8370987e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff819c219f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff819c4664)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff819c76ee)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff819c87fb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff819ccf80)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff819cd98e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff819ced25)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff819cfe93)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff819d1989)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff819d2ba7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff819d31bd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff819d41bf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d6860)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff819d7927)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff819d9db9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff819dc304)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff819deacf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff819e0758)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff819e1969)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff819e520a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff819e5af5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff819e9a7d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff819ea65d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff819eb2ec)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff819ec8ac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff819ed21d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff819ed7b9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff819edda5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff819ef316)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff819ef81c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff819f00bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff819f2c7f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff819f41c9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819f4c29)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5e2a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff819f7d83)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff819f961b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff819fba70)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff819fe2e0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff819fece6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff819ffca4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff81a0135c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a0343c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff81a06d51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff81a070f1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a073c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff81a08783)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff81a09390)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a09873)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a8fa)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a0b12f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a0f218)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0fc97)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81a0fdc4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a11eb3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81a12137)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff81a134d6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a14355)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff81a162ef)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a16435)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81af897c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc812)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b08e32)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
```
```
In drivers/base/physical_location.c (ffffffff81b79a80)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81ca0949)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d38f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d3292b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/platform/x86/intel/pmc/tgl.c (ffffffff81ddcf35)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
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
In drivers/gpio/gpiolib-acpi.c (ffffffff81955130)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pcie/edr.c (ffffffff8198c8b7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/pci-acpi.c (ffffffff8198fed3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff819a80e6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff819e4265)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff819e5787)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/utils.c:acpi_get_subsystem_id
```
```
In drivers/acpi/device_sysfs.c (ffffffff819e7b6d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:create_of_modalias
```
```
In drivers/acpi/scan.c (ffffffff819eeb6f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/acpi/pci_root.c (ffffffff819fd0ac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff81a0825f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_free_device_properties
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff81a0867c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/x86/s2idle.c (ffffffff81a09b16)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
```
```
In drivers/acpi/acpi_adxl.c (ffffffff8393cd0e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff81a0cbbf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0f0b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81a1213e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_resolve_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff81a1324b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81a17a20)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81a1845d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81a19824)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81a1a9c3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81a1c518)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81a1d7cb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_is_pci_root_bridge
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff81a1dded)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81a1edef)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a2151e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81a22616)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff81a24aa9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff81a26ff4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff81a297bf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81a2b477)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff81a2c6b8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81a2ff5a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff81a30845)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81a347f7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81a35416)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81a360ac)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff81a3766c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff81a37fdd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff81a38579)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81a38b65)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81a3a106)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff81a3a60c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81a3aeda)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff81a3da9f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3efe9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3fa49)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_ns_get_device_callback
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a40c7a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff81a42bd3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff81a4446b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff81a468c0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81a4915f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff81a49b66)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_walk_resources
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4ab24)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff81a4c1dc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a4e2dc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff81a51bf1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff81a51f91)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a52296)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff81a53693)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff81a542a0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a54813)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a5589a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a560ff)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a5a358)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5ae27)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81a5af54)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a5d043)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81a5d2c7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff81a5e666)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a5f4e5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff81a614cf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a61615)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81b4bf9c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4fe22)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5ce52)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
```
```
In drivers/base/physical_location.c (ffffffff81bcd9df)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81d55599)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd30b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de893a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/platform/x86/amd/wbrf.c (ffffffff81e92b79)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/amd/wbrf.c:amd_wbrf_retrieve_freq_band
  - drivers/platform/x86/amd/wbrf.c:wbrf_record
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106caaf8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffff8000106f83d8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffff8000107188c4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffff800010764330)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffff8000107657a4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffff80001076694c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffff80001076d204)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffff800010775634)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffff80001077b6e0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/acpica/dsmethod.c (ffff80001077dfc8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffff80001077f55c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffff80001077fd08)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffff800010781c40)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evregion.c (ffff8000107826bc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffff800010782d50)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/exconfig.c (ffff800010783d7c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffff80001078556c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffff8000107866ec)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffff800010787b90)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffff80001078a158)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffff80001078a5a4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffff80001078b53c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (ffff80001078b840)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffff80001078bf84)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffff80001078cd64)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nseval.c (ffff80001078cf64)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffff80001078d464)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffff80001078dc30)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffff80001078ddec)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffff80001078e304)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffff80001078fe98)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffff800010790b44)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffff8000107916e8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffff800010792a40)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffff800010793754)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffff800010794b3c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffff800010795f88)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffff80001079663c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffff800010796e5c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffff800010797a94)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffff800010798e78)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffff80001079b2a0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffff80001079bb1c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffff80001079bd0c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utmutex.c (ffff80001079d04c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffff80001079d798)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffff80001079dc30)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/arm64/iort.c (ffff8000107b17e0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/char/tpm/tpm_ppi.c (ffff8000108c01a0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c2e18)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffff800010a37768)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90e74)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5cbc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815684b0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81586464)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff815a1ce0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815ca495)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815cb565)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff815ccc5e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815d2ce6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffffffff815d908e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff815df376)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff815df6cb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828e47c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e1cec)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815e308d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff815e384c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815e54c4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815e5abd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815e6168)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815e69b5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815e76b4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815e7c34)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815e7fd4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815e88c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e97da)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815ea0b4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815eb64e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815ec646)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815ed986)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815efbce)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff815eff5f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815f1a9f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815f1d11)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815f2377)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff815f2fdf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815f3263)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815f35be)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815f3c89)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff815f3d09)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815f4122)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815f58b9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f63d2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6de0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff815f808f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff815f8c7c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815f9d9b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815fb063)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff815fb56f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815fbbd3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff815fc6eb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815fd76a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff815fe68f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff815feec3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ff13b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff815ffa4e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8160006b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816005d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816009a4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff8169ad14)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169d62b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816abf2b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff817bb231)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81806145)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559300)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81575234)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff81590e80)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b3515)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815b45b5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815b59c0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff815b67de)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815bc8a6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffffffff815c2c7e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff815ca9b6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff815caceb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828dc86c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815cd362)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815ce6fe)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff815ceeb8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815d0b2b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815d111f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815d17c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815d200d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815d2d02)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815d3272)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815d360f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815d3ef1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d4dfd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815d56d2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815d6c67)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815d7c5a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815d8f7e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff815db1ad)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff815db536)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff815dd041)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff815dd2ae)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff815dd90a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff815de56d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nseval.c (ffffffff815de7f1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff815deb47)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff815df20d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff815df28d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff815df6a1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff815e0e44)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815e1927)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e254c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff815e35ce)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff815e41bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff815e52d0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff815e6593)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff815e6a9f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff815e70fe)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff815e7c16)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff815e8c8b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff815e9b86)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
```
```
In drivers/acpi/acpica/uterror.c (ffffffff815ea3ba)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff815ea62d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff815eaf3b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815eb553)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815eba99)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff815ebe64)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/nfit/core.c (ffffffff815f73a1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:nfit_intel_shutdown_status
  - drivers/acpi/nfit/core.c:nfit_intel_shutdown_status
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/acpi/nfit/core.c:acpi_label_write
  - drivers/acpi/nfit/core.c:pkg_to_buf
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff81678704)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b01b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8168988b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff817acc51)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd8c5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567020)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff81586324)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff815a2270)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815cb245)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815cc515)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815cd780)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff815ce76e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815d4bc6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffffffff815dc08e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff815e49c6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff815e4d1b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828f772d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff815e6a96)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff815e89f3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff815ead5a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff815ebae2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff815ef321)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff815efd36)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff815f0723)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815f1512)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff815f2a3c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff815f3403)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff815f3b85)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815f4a19)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f65f7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff815f744e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff815f8c8a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff815fab2e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff815fc9de)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff815fe124)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff81601e3d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8160253d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8160509b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81605622)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff81606013)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff816072a4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff81607381)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff81608200)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff8160842e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff81609509)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff816095bf)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81609e0d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff8160ba18)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff8160cb24)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8160d358)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160df5e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff8160f885)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff81610f9c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff816128bd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81614712)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff81615080)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8161593f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff8161685a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81618075)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff81619c3d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff8161a941)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff8161ac4d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff8161b9bc)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff8161c21d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8161c550)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8161d111)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff8161d70a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff81620431)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81620d26)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81620df3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816226a7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff81622765)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff816232fd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff816240b7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff8162514b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816251e2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff816c8f84)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cb89b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816da10b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff817f7cd1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818451f5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8186652e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81580f40)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
```
```
In drivers/pci/pci-acpi.c (ffffffff815a07d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
```
In drivers/pci/pci-label.c (ffffffff815bc670)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815e50e5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_delete_lock
```
```
In drivers/acpi/utils.c (ffffffff815e63b5)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815e7620)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
```
```
In drivers/acpi/device_sysfs.c (ffffffff815e862e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815eea86)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
```
```
In drivers/acpi/pci_root.c (ffffffff815f5f4e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_create
```
```
In drivers/acpi/property.c (ffffffff815fe886)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_free_properties
  - drivers/acpi/property.c:acpi_destroy_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_data_ok
```
```
In drivers/acpi/x86/apple.c (ffffffff815febcb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/acpi_adxl.c (ffffffff828fcb85)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_decode
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/acpi_adxl.c:adxl_dsm
```
```
In drivers/acpi/acpica/dsdebug.c (ffffffff81600946)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff816028a3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dspkginit.c (ffffffff81604c0a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dsutils.c (ffffffff81605992)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff816091d1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dswstate.c:acpi_ds_delete_walk_state
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81609be6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff8160a5d3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8160b3c2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_handlers
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
```
```
In drivers/acpi/acpica/evregion.c (ffffffff8160c8ec)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff8160d2b3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evsci.c (ffffffff8160da35)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160e8c9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816104a7)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff816112fe)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exdump.c (ffffffff81612b3a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
```
```
In drivers/acpi/acpica/exfldio.c (ffffffff816149de)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field
```
```
In drivers/acpi/acpica/exnames.c (ffffffff8161688e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exnames.c:acpi_ex_get_name_string
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81617fd4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exstorob.c (ffffffff8161bced)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string
```
```
In drivers/acpi/acpica/extrace.c (ffffffff8161c3ed)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff8161ef4b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff8161f4d2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_delete_pci_list
```
```
In drivers/acpi/acpica/nsaccess.c (ffffffff8161fec3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
```
```
In drivers/acpi/acpica/nsconvert.c (ffffffff81621154)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
```
In drivers/acpi/acpica/nsdump.c (ffffffff81621231)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
```
```
In drivers/acpi/acpica/nseval.c (ffffffff816220b0)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff816222de)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (ffffffff816233b9)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
```
```
In drivers/acpi/acpica/nsobject.c (ffffffff8162346f)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81623cbd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nssearch.c (ffffffff816258c8)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
```
```
In drivers/acpi/acpica/nsutils.c (ffffffff816269d4)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsutils.c:acpi_ns_print_node_pathname
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81627208)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
```
```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627e0e)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
  - drivers/acpi/acpica/nsxfname.c:acpi_get_object_info
```
```
In drivers/acpi/acpica/psloop.c (ffffffff81629735)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
```
```
In drivers/acpi/acpica/psparse.c (ffffffff8162ae4c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
```
```
In drivers/acpi/acpica/rscreate.c (ffffffff8162c76d)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff8162e5c2)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/rsxface.c (ffffffff8162ef30)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (ffffffff8162f7ef)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_terminate
  - drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list
```
```
In drivers/acpi/acpica/tbinstal.c (ffffffff8163070a)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81631f25)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_delete_address_lists
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
```
```
In drivers/acpi/acpica/utdelete.c (ffffffff81633aed)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
```
```
In drivers/acpi/acpica/uterror.c (ffffffff816347f1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81634afd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utinit.c (ffffffff8163586c)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
  - drivers/acpi/acpica/utinit.c:acpi_ut_subsystem_shutdown
```
```
In drivers/acpi/acpica/utmisc.c (ffffffff816360cd)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81636400)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81636fc1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
```
```
In drivers/acpi/acpica/utosi.c (ffffffff816375ba)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_remove_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
```
```
In drivers/acpi/acpica/dbcmds.c (ffffffff8163a2e1)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_trace
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff8163abd6)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_dump_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff8163aca3)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8163c557)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_delete_objects
```
```
In drivers/acpi/acpica/dbhistry.c (ffffffff8163c615)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history
```
```
In drivers/acpi/acpica/dbmethod.c (ffffffff8163d1ad)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff8163df67)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
```
In drivers/acpi/acpica/dbutils.c (ffffffff8163effb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8163f092)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_terminate_debugger
```
```
In drivers/char/tpm/tpm_ppi.c (ffffffff816e3464)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e5d6b)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816f46bb)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/core/usb-acpi.c (ffffffff81811f11)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f775)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff818817de)
Location: include/acpi/platform/aclinuxex.h:60
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
</ul>

## Differences
