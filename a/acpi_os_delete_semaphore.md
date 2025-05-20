# Function: <code>acpi_os_delete_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a4d0)
Location: drivers/acpi/osl.c:1265
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffffffff8147a4d0-ffffffff8147a4f9: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8a88)
Location: drivers/acpi/osl.c:1198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffffffff814c8a88-ffffffff814c8ab4: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea9cc)
Location: drivers/acpi/osl.c:1193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffffffff814ea9cc-ffffffff814ea9f8: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6850)
Location: drivers/acpi/osl.c:1192
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffffffff814f6850-ffffffff814f687c: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815376c0)
Location: drivers/acpi/osl.c:1202
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815376c0-ffffffff81537737: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d240)
Location: drivers/acpi/osl.c:1207
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff8156d240-ffffffff8156d2b7: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81584e00)
Location: drivers/acpi/osl.c:1213
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81584e00-ffffffff81584e77: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5a20)
Location: drivers/acpi/osl.c:1199
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815b5a20-ffffffff815b5a9a: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6c50)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815d6c50-ffffffff815d6cca: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680980)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81680980-ffffffff816809fa: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f470)
Location: drivers/acpi/osl.c:1223
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff8169f470-ffffffff8169f4ea: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682120)
Location: drivers/acpi/osl.c:1223
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81682120-ffffffff8168219a: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f7250)
Location: drivers/acpi/osl.c:1223
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff816f7250-ffffffff816f72ca: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824150)
Location: drivers/acpi/osl.c:1225
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81824150-ffffffff818241eb: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955510)
Location: drivers/acpi/osl.c:1225
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff81955510-ffffffff819555ab: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199b910)
Location: drivers/acpi/osl.c:1225
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff8199b910-ffffffff8199b9ab: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e3e60)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff819e3e60-ffffffff819e3efb: acpi_os_delete_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764130)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffff800010764130-ffff800010764188: acpi_os_delete_semaphore (STB_GLOBAL)
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
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca370)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffffffff815ca370-ffffffff815ca39c: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b33f0)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
```
**Symbols:**

```
ffffffff815b33f0-ffffffff815b341c: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815caf30)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815caf30-ffffffff815cafaa: acpi_os_delete_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_delete_semaphore(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4dd0)
Location: drivers/acpi/osl.c:1219
Inline: False
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utlock.c:acpi_ut_delete_rw_lock
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_terminate
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
```
**Symbols:**

```
ffffffff815e4dd0-ffffffff815e4e4a: acpi_os_delete_semaphore (STB_GLOBAL)
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
