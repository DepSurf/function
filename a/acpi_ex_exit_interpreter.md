# Function: <code>acpi_ex_exit_interpreter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81499ee9)
Location: drivers/acpi/acpica/exutils.c:124
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
ffffffff81499ee9-ffffffff81499f17: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff814e8df2)
Location: drivers/acpi/acpica/exutils.c:124
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
ffffffff814e8df2-ffffffff814e8e20: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8150b61b)
Location: drivers/acpi/acpica/exutils.c:128
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
ffffffff8150b61b-ffffffff8150b66f: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8151bc4b)
Location: drivers/acpi/acpica/exutils.c:128
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
ffffffff8151bc4b-ffffffff8151bc9f: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8156bae1)
Location: drivers/acpi/acpica/exutils.c:128
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
ffffffff8156bae1-ffffffff8156bb6f: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815a2739)
Location: drivers/acpi/acpica/exutils.c:94
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
ffffffff815a2739-ffffffff815a27c7: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815bb3fc)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff815bb3fc-ffffffff815bb48a: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815ecfd6)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff815ecfd6-ffffffff815ed064: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8160e36b)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff8160e36b-ffffffff8160e3f9: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba6c9)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff816ba6c9-ffffffff816ba757: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816d80c1)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff816d80c1-ffffffff816d814f: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff816ba053)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff816ba053-ffffffff816ba0e1: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff817310a3)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff817310a3-ffffffff81731131: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81861cd6)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff81861cd6-ffffffff81861d72: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8199f090)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff8199f090-ffffffff8199f139: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff819e5d60)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff819e5d60-ffffffff819e5e09: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff81a30ab0)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff81a30ab0-ffffffff81a30b59: acpi_ex_exit_interpreter (STB_GLOBAL)
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
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffff80001078a648)
Location: drivers/acpi/acpica/exutils.c:93
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
ffff80001078a648-ffff80001078a6a8: acpi_ex_exit_interpreter (STB_GLOBAL)
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
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815effe4)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff815effe4-ffffffff815f0038: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff815db5bb)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff815db5bb-ffffffff815db60f: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8160264b)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff8160264b-ffffffff816026d9: acpi_ex_exit_interpreter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ex_exit_interpreter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exutils.c (ffffffff8161c4fb)
Location: drivers/acpi/acpica/exutils.c:93
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
ffffffff8161c4fb-ffffffff8161c589: acpi_ex_exit_interpreter (STB_GLOBAL)
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
