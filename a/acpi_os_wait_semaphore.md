# Function: <code>acpi_os_wait_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a4f9)
Location: drivers/acpi/osl.c:1284
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utxface.c:acpi_install_interface_handler
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffffffff8147a4f9-ffffffff8147a560: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8ab4)
Location: drivers/acpi/osl.c:1217
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_install_interface_handler
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffffffff814c8ab4-ffffffff814c8b1b: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea9f8)
Location: drivers/acpi/osl.c:1212
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_install_interface_handler
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffffffff814ea9f8-ffffffff814eaa5f: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6880)
Location: drivers/acpi/osl.c:1211
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffffffff814f6880-ffffffff814f68e6: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537740)
Location: drivers/acpi/osl.c:1221
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81537740-ffffffff815378c6: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d2c0)
Location: drivers/acpi/osl.c:1226
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff8156d2c0-ffffffff8156d452: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584e80)
Location: drivers/acpi/osl.c:1232
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81584e80-ffffffff81585012: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5aa0)
Location: drivers/acpi/osl.c:1218
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815b5aa0-ffffffff815b5c37: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6cd0)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815d6cd0-ffffffff815d6e67: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680a00)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81680a00-ffffffff81680b9c: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f4f0)
Location: drivers/acpi/osl.c:1242
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff8169f4f0-ffffffff8169f68c: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816821a0)
Location: drivers/acpi/osl.c:1242
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff816821a0-ffffffff8168233c: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1242
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81ceedf0-ffffffff81ceee05: acpi_os_wait_semaphore.cold (STB_LOCAL)
ffffffff816f72d0-ffffffff816f7489: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1244
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff81eb6561-ffffffff81eb6576: acpi_os_wait_semaphore.cold (STB_LOCAL)
ffffffff818241f0-ffffffff818243af: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1244
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff8209177f-ffffffff82091794: acpi_os_wait_semaphore.cold (STB_LOCAL)
ffffffff819555c0-ffffffff8195577f: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1244
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff821120f2-ffffffff82112107: acpi_os_wait_semaphore.cold (STB_LOCAL)
ffffffff8199b9c0-ffffffff8199bb7f: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_remove_interface
  - drivers/acpi/acpica/utxface.c:acpi_install_interface
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff821efdf6-ffffffff821efe0b: acpi_os_wait_semaphore.cold (STB_LOCAL)
ffffffff819e3f10-ffffffff819e40cf: acpi_os_wait_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764188)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffff800010764188-ffff800010764224: acpi_os_wait_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca3a0)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffffffff815ca3a0-ffffffff815ca40c: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3420)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
```
**Symbols:**

```
ffffffff815b3420-ffffffff815b348c: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cafb0)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815cafb0-ffffffff815cb147: acpi_os_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_wait_semaphore(acpi_handle handle, u32 units, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4e50)
Location: drivers/acpi/osl.c:1238
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_semaphore
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_write_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_release_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_acquire_read_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
  - drivers/acpi/acpica/utosi.c:acpi_ut_interface_terminate
  - drivers/acpi/acpica/utosi.c:acpi_ut_initialize_interfaces
  - drivers/acpi/acpica/utxface.c:acpi_update_interfaces
  - drivers/acpi/acpica/utxfmutex.c:acpi_acquire_mutex
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_interfaces
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
**Symbols:**

```
ffffffff815e4e50-ffffffff815e4fe7: acpi_os_wait_semaphore (STB_GLOBAL)
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
