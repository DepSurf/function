# Function: <code>acpi_os_signal_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a560)
Location: drivers/acpi/osl.c:1329
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utxface.c:acpi_install_interface_handler
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffffffff8147a560-ffffffff8147a598: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8b1b)
Location: drivers/acpi/osl.c:1262
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_install_interface_handler
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffffffff814c8b1b-ffffffff814c8b53: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814eaa5f)
Location: drivers/acpi/osl.c:1257
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_install_interface_handler
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffffffff814eaa5f-ffffffff814eaa97: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f68f0)
Location: drivers/acpi/osl.c:1256
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffffffff814f68f0-ffffffff814f6928: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815378d0)
Location: drivers/acpi/osl.c:1266
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815378d0-ffffffff81537956: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d460)
Location: drivers/acpi/osl.c:1271
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff8156d460-ffffffff8156d4e3: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81585020)
Location: drivers/acpi/osl.c:1277
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81585020-ffffffff815850a3: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5c40)
Location: drivers/acpi/osl.c:1263
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815b5c40-ffffffff815b5cc9: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6e70)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815d6e70-ffffffff815d6ef9: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680ba0)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81680ba0-ffffffff81680c29: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f690)
Location: drivers/acpi/osl.c:1287
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff8169f690-ffffffff8169f719: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682340)
Location: drivers/acpi/osl.c:1287
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81682340-ffffffff816823c9: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1287
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81ceee05-ffffffff81ceee1a: acpi_os_signal_semaphore.cold (STB_LOCAL)
ffffffff816f7490-ffffffff816f7537: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81eb6576-ffffffff81eb658b: acpi_os_signal_semaphore.cold (STB_LOCAL)
ffffffff818243b0-ffffffff81824479: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff82091794-ffffffff820917a9: acpi_os_signal_semaphore.cold (STB_LOCAL)
ffffffff81955790-ffffffff81955859: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff82112107-ffffffff8211211c: acpi_os_signal_semaphore.cold (STB_LOCAL)
ffffffff8199bb90-ffffffff8199bc59: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff821efe0b-ffffffff821efe20: acpi_os_signal_semaphore.cold (STB_LOCAL)
ffffffff819e40e0-ffffffff819e41a9: acpi_os_signal_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764228)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffff800010764228-ffff800010764294: acpi_os_signal_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca410)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffffffff815ca410-ffffffff815ca447: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3490)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
```
**Symbols:**

```
ffffffff815b3490-ffffffff815b34c7: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb150)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815cb150-ffffffff815cb1d9: acpi_os_signal_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_signal_semaphore(acpi_handle handle, u32 units);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4ff0)
Location: drivers/acpi/osl.c:1283
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_terminate_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_all_mutexes
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_signal_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_release_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815e4ff0-ffffffff815e5079: acpi_os_signal_semaphore (STB_GLOBAL)
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
