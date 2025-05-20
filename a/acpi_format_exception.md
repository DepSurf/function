# Function: <code>acpi_format_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff814a705f)
Location: drivers/acpi/acpica/utexcep.c:66
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff814a705f-ffffffff814a709e: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff814f63e2)
Location: drivers/acpi/acpica/utexcep.c:66
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff814f63e2-ffffffff814f6421: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81518fa5)
Location: drivers/acpi/acpica/utexcep.c:66
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff81518fa5-ffffffff81518fe4: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff815297bb)
Location: drivers/acpi/acpica/utexcep.c:66
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815297bb-ffffffff815297fa: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81581b2a)
Location: drivers/acpi/acpica/utexcep.c:66
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff81581b2a-ffffffff81581b70: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff815b8cf1)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815b8cf1-ffffffff815b8d37: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff815d20c2)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815d20c2-ffffffff815d2108: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff816039ad)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff816039ad-ffffffff816039f8: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81624e57)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81624e57-ffffffff81624ea2: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff816d15f3)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff816d15f3-ffffffff816d163e: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff816ef5d1)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd/init.c:detect_ivrs
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff816ef5d1-ffffffff816ef61c: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff816d1436)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff816d1436-ffffffff816d1481: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81748b90)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81748b90-ffffffff81748bdb: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff8187ace0)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff8187ace0-ffffffff8187ad32: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff819bdae0)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff819bdae0-ffffffff819bdb35: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81a04cd0)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81a04cd0-ffffffff81a04d25: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81a4fb70)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/viot.c:acpi_viot_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81a4fb70-ffffffff81a4fbc5: acpi_format_exception (STB_GLOBAL)
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
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffff80001079ae74)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - arch/arm64/kernel/acpi.c:acpi_boot_table_init
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/acpi/arm64/iort.c:acpi_iort_init
  - drivers/firmware/arm_sdei.c:sdei_init
```
**Symbols:**

```
ffff80001079ae74-ffff80001079aed4: acpi_format_exception (STB_GLOBAL)
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
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff815fe42e)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff815fe42e-ffffffff815fe471: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff815e9925)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff815e9925-ffffffff815e9968: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81619137)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81619137-ffffffff81619182: acpi_format_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *acpi_format_exception(acpi_status status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utexcep.c (ffffffff81632fe7)
Location: drivers/acpi/acpica/utexcep.c:30
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/exdump.c:acpi_ex_dump_reference_obj
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/rscreate.c:acpi_rs_create_aml_resources
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/utdebug.c:acpi_ut_status_exit
  - drivers/acpi/acpica/uterror.c:acpi_ut_method_error
  - drivers/acpi/acpica/uterror.c:acpi_ut_prefixed_namespace_error
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utxferror.c:acpi_bios_exception
  - drivers/acpi/acpica/utxferror.c:acpi_exception
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbcmds.c:acpi_db_unload_acpi_table
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_object_type
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_single_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_set_scope
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
  - drivers/acpi/apei/hest.c:acpi_hest_init
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/bert.c:bert_init
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81632fe7-ffffffff81633032: acpi_format_exception (STB_GLOBAL)
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
