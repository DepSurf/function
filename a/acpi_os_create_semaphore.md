# Function: <code>acpi_os_create_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a45c)
Location: drivers/acpi/osl.c:1240
Inline: False
Direct callers:
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff8147a45c-ffffffff8147a4d0: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8a14)
Location: drivers/acpi/osl.c:1173
Inline: False
Direct callers:
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff814c8a14-ffffffff814c8a88: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea958)
Location: drivers/acpi/osl.c:1168
Inline: False
Direct callers:
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff814ea958-ffffffff814ea9cc: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f67e0)
Location: drivers/acpi/osl.c:1167
Inline: False
Direct callers:
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff814f67e0-ffffffff814f6850: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815375f0)
Location: drivers/acpi/osl.c:1177
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815375f0-ffffffff815376bf: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d170)
Location: drivers/acpi/osl.c:1182
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff8156d170-ffffffff8156d23f: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584d30)
Location: drivers/acpi/osl.c:1188
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81584d30-ffffffff81584df4: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5940)
Location: drivers/acpi/osl.c:1174
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815b5940-ffffffff815b5a1d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6b70)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815d6b70-ffffffff815d6c4d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816808a0)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff816808a0-ffffffff8168097d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f390)
Location: drivers/acpi/osl.c:1198
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff8169f390-ffffffff8169f46d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682040)
Location: drivers/acpi/osl.c:1198
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81682040-ffffffff8168211d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f7170)
Location: drivers/acpi/osl.c:1198
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff816f7170-ffffffff816f724d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824070)
Location: drivers/acpi/osl.c:1200
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81824070-ffffffff8182414c: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955420)
Location: drivers/acpi/osl.c:1200
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81955420-ffffffff819554fc: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199b820)
Location: drivers/acpi/osl.c:1200
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff8199b820-ffffffff8199b8fc: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e3d40)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff819e3d40-ffffffff819e3e4d: acpi_os_create_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff8000107640b0)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffff8000107640b0-ffff800010764130: acpi_os_create_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca300)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff815ca300-ffffffff815ca370: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3380)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
**Symbols:**

```
ffffffff815b3380-ffffffff815b33eb: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cae50)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815cae50-ffffffff815caf2d: acpi_os_create_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_create_semaphore(u32 max_units, u32 initial_units, acpi_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4cf0)
Location: drivers/acpi/osl.c:1194
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_create_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815e4cf0-ffffffff815e4dcd: acpi_os_create_semaphore (STB_GLOBAL)
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
