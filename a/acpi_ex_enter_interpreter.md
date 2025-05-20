# Function: <code>acpi_ex_enter_interpreter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81499ebb)
Location: drivers/acpi/acpica/exutils.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff81499ebb-ffffffff81499ee9: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff814e8dc4)
Location: drivers/acpi/acpica/exutils.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff814e8dc4-ffffffff814e8df2: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8150b5c7)
Location: drivers/acpi/acpica/exutils.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
```
**Symbols:**

```
ffffffff8150b5c7-ffffffff8150b61b: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8151bbf7)
Location: drivers/acpi/acpica/exutils.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
```
**Symbols:**

```
ffffffff8151bbf7-ffffffff8151bc4b: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8156ba53)
Location: drivers/acpi/acpica/exutils.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8156ba53-ffffffff8156bae1: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815a26ab)
Location: drivers/acpi/acpica/exutils.c:52
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815a26ab-ffffffff815a2739: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815bb36e)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815bb36e-ffffffff815bb3fc: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815ecf48)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815ecf48-ffffffff815ecfd6: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8160e2dd)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8160e2dd-ffffffff8160e36b: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba63b)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816ba63b-ffffffff816ba6c9: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816d8033)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816d8033-ffffffff816d80c1: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816b9fc5)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816b9fc5-ffffffff816ba053: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81731015)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81731015-ffffffff817310a3: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81861c3a)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81861c3a-ffffffff81861cd6: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8199efd0)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8199efd0-ffffffff8199f07c: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff819e5ca0)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff819e5ca0-ffffffff819e5d4c: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81a309f0)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81a309f0-ffffffff81a30a9c: acpi_ex_enter_interpreter (STB_GLOBAL)
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
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffff80001078a5e8)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
```
**Symbols:**

```
ffff80001078a5e8-ffff80001078a648: acpi_ex_enter_interpreter (STB_GLOBAL)
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
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815eff90)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
```
**Symbols:**

```
ffffffff815eff90-ffffffff815effe4: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815db567)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
```
**Symbols:**

```
ffffffff815db567-ffffffff815db5bb: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816025bd)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816025bd-ffffffff8160264b: acpi_ex_enter_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ex_enter_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8161c46d)
Location: drivers/acpi/acpica/exutils.c:51
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nsload.c:acpi_ns_load_table
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8161c46d-ffffffff8161c4fb: acpi_ex_enter_interpreter (STB_GLOBAL)
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
