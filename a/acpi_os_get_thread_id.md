# Function: <code>acpi_os_get_thread_id</code>

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
In drivers/acpi/acpica/evxface.c (ffffffff81492d92)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
```
```
In drivers/acpi/acpica/exutils.c (ffffffff81499f69)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff814a8c1f)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814a9e9e)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff814db542)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
```
```
In drivers/acpi/acpica/evxface.c (ffffffff814e1b8e)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
```
```
In drivers/acpi/acpica/exutils.c (ffffffff814e8e72)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff814f7eee)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814f9148)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff814fde39)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815044cd)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8150b6c1)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8151ab0a)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8151bb5f)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff8150e300)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815142fb)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8151bcf1)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8152b32d)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8152c371)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815529cc)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8155db1c)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8156bc07)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81581bc3)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8158513b)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81586b56)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81589cb3)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8158a62a)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8158d851)
Location: include/acpi/platform/aclinuxex.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff81589314)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815946af)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff815a2853)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff815b8d8b)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815bc2bc)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815bdd0c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff815c0e25)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815c1848)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815c4b99)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815a1856)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815acdb2)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff815bb516)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff815d215c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815d5702)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815d7157)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff815da296)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff815dacce)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff815de0ef)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815d2eb3)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815de5d1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff815ed0f7)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81603a4c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81607096)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81608b36)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff8160bdb6)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8160c7f9)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8160fbf1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815f4126)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815ff914)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8160e48c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81624ef6)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81628531)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81629fdb)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff8162d257)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8162dc9a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8163109a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff816a01b1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac7d1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff816ba7ea)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1690)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d4ccb)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d67ba)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff816d9a4f)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816da4a3)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816ddb09)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff816bd9c9)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ca110)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff816d81e2)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff816ef66e)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816f2c98)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816f4765)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff816f79de)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816f8421)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816fbb9f)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff8169faa7)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff816ac0f1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff816ba174)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff816d14d3)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816d4b49)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d6603)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff816d9852)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff816da294)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff816dd9c2)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff817160a7)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81722e0e)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff817311c4)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81748c2d)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8174c549)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8174e16f)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff817513e7)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81751eec)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81755ab2)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff81845bb7)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff818532aa)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff81861e0f)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff8187ad93)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8187eb8d)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff818809e9)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81884057)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81884c0d)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81888b49)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff8197d479)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8198d83b)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8199f1ee)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff819bdbba)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff819c28b0)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff819c4f00)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff819c9385)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff819ca296)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff819cf092)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff819c3f29)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff819d42cb)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff819e5ebe)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81a04daa)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a09c00)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a0c309)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81a107c5)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a116d6)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a16560)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0e949)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81a1eefb)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff81a30c0e)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81a4fc4a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a54ba0)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a572d9)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81a5b955)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81a5c866)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff81a61740)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffff80001077dcc0)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/exutils.c (ffff80001078a734)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffff80001079d0a0)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffff80001079e5f8)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815e19c1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815e8023)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff815f0084)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816000b1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8160112a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815cd03c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815d3651)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff815db65b)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff815eb599)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815ec5e5)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815e8406)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff815f3bf4)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8160276c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff816191d6)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff8161c811)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8161e2bb)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff81621537)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff81621f7a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8162537a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
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
In drivers/acpi/acpica/dsmethod.c (ffffffff816022b6)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
```
In drivers/acpi/acpica/evxface.c (ffffffff8160daa4)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
```
```
In drivers/acpi/acpica/exutils.c (ffffffff8161c61c)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
```
In drivers/acpi/acpica/utdebug.c (ffffffff81633086)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdebug.c:acpi_debug_print
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff816366c1)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex
  - drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8163816b)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state
```
```
In drivers/acpi/acpica/dbdisply.c (ffffffff8163b3e7)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_argument_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_result_object
```
```
In drivers/acpi/acpica/dbexec.c (ffffffff8163be2a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_method_thread
```
```
In drivers/acpi/acpica/dbxface.c (ffffffff8163f22a)
Location: include/acpi/platform/aclinuxex.h:71
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
  - drivers/acpi/acpica/dbxface.c:acpi_db_signal_break_point
```
</details>
</li>
</ul>

## Differences
