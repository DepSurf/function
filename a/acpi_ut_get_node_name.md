# Function: <code>acpi_ut_get_node_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814a716b)
Location: drivers/acpi/acpica/utdecode.c:270
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
```
**Symbols:**

```
ffffffff814a716b-ffffffff814a71b6: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff814f64ee)
Location: drivers/acpi/acpica/utdecode.c:271
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
```
**Symbols:**

```
ffffffff814f64ee-ffffffff814f6539: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815190b1)
Location: drivers/acpi/acpica/utdecode.c:272
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
```
**Symbols:**

```
ffffffff815190b1-ffffffff815190fc: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815298c7)
Location: drivers/acpi/acpica/utdecode.c:272
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
```
**Symbols:**

```
ffffffff815298c7-ffffffff81529912: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81582271)
Location: drivers/acpi/acpica/utdecode.c:272
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
```
**Symbols:**

```
ffffffff81582271-ffffffff815822bc: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815b9426)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
```
**Symbols:**

```
ffffffff815b9426-ffffffff815b9471: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815d27f7)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
```
**Symbols:**

```
ffffffff815d27f7-ffffffff815d2842: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816040f5)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
```
**Symbols:**

```
ffffffff816040f5-ffffffff81604142: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8162559f)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
```
**Symbols:**

```
ffffffff8162559f-ffffffff816255ec: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1d45)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816d1d45-ffffffff816d1d92: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816efd23)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816efd23-ffffffff816efd70: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff816d1b88)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816d1b88-ffffffff816d1bd5: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8174931e)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff8174931e-ffffffff8174936b: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8187b66b)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff8187b66b-ffffffff8187b6bc: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff819be9a0)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff819be9a0-ffffffff819bea0d: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a05b90)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81a05b90-ffffffff81a05bfd: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff81a50a30)
Location: drivers/acpi/acpica/utdecode.c:239
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_parent_tree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81a50a30-ffffffff81a50a9d: acpi_ut_get_node_name (STB_GLOBAL)
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
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffff80001079b050)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
```
**Symbols:**

```
ffff80001079b050-ffff80001079b0d0: acpi_ut_get_node_name (STB_GLOBAL)
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
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815fe53e)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
```
**Symbols:**

```
ffffffff815fe53e-ffffffff815fe58b: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff815e9a35)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
```
**Symbols:**

```
ffffffff815e9a35-ffffffff815e9a82: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8161987f)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
```
**Symbols:**

```
ffffffff8161987f-ffffffff816198cc: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *acpi_ut_get_node_name(void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdecode.c (ffffffff8163372f)
Location: drivers/acpi/acpica/utdecode.c:238
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsdebug.c:acpi_ds_dump_method_stack
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_restart_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_pop
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/evregion.c:acpi_ev_attach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_install_node
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsnames.c:acpi_ns_handle_to_name
  - drivers/acpi/acpica/nsobject.c:acpi_ns_detach_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_remove_address_range
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
  - drivers/acpi/acpica/dbcmds.c:acpi_db_send_notify
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_calling_tree
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_results
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_method_info
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_arguments
```
**Symbols:**

```
ffffffff8163372f-ffffffff8163377c: acpi_ut_get_node_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
