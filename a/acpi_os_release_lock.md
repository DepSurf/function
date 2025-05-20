# Function: <code>acpi_os_release_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a5e5)
Location: drivers/acpi/osl.c:1714
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_dispatch
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write_bit_register
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
**Symbols:**

```
ffffffff8147a5e5-ffffffff8147a5f5: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8bb3)
Location: drivers/acpi/osl.c:1520
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write_bit_register
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
**Symbols:**

```
ffffffff814c8bb3-ffffffff814c8bc3: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814eaaf7)
Location: drivers/acpi/osl.c:1515
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evsci.c:acpi_ev_sci_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write_bit_register
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
**Symbols:**

```
ffffffff814eaaf7-ffffffff814eab07: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6990)
Location: drivers/acpi/osl.c:1514
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write_bit_register
```
**Symbols:**

```
ffffffff814f6990-ffffffff814f69a0: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815379e0)
Location: drivers/acpi/osl.c:1524
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
  - drivers/acpi/acpica/hwxface.c:acpi_write_bit_register
```
**Symbols:**

```
ffffffff815379e0-ffffffff815379f0: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d570)
Location: drivers/acpi/osl.c:1599
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff8156d570-ffffffff8156d580: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81585130)
Location: drivers/acpi/osl.c:1605
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff81585130-ffffffff81585140: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5d50)
Location: drivers/acpi/osl.c:1591
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815b5d50-ffffffff815b5d60: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6f80)
Location: drivers/acpi/osl.c:1611
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815d6f80-ffffffff815d6f90: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680cb0)
Location: drivers/acpi/osl.c:1612
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff81680cb0-ffffffff81680cc0: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f7a0)
Location: drivers/acpi/osl.c:1631
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff8169f7a0-ffffffff8169f7b0: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682440)
Location: drivers/acpi/osl.c:1621
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff81682440-ffffffff81682450: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f75b0)
Location: drivers/acpi/osl.c:1616
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff816f75b0-ffffffff816f75c0: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824520)
Location: drivers/acpi/osl.c:1533
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff81824520-ffffffff81824538: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955970)
Location: drivers/acpi/osl.c:1533
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff81955970-ffffffff81955988: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199bd70)
Location: drivers/acpi/osl.c:1533
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff8199bd70-ffffffff8199bd88: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int not_used);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e42c0)
Location: drivers/acpi/osl.c:1526
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
```
**Symbols:**

```
ffffffff819e42c0-ffffffff819e42d6: acpi_os_release_lock (STB_GLOBAL)
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
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff8000107643d8)
Location: drivers/acpi/osl.c:1611
Inline: False
```
**Symbols:**

```
ffff8000107643d8-ffff800010764410: acpi_os_release_lock (STB_GLOBAL)
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
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca4b0)
Location: drivers/acpi/osl.c:1611
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815ca4b0-ffffffff815ca4c0: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3530)
Location: drivers/acpi/osl.c:1611
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815b3530-ffffffff815b3540: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb260)
Location: drivers/acpi/osl.c:1611
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815cb260-ffffffff815cb270: acpi_os_release_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_os_release_lock(spinlock_t *lockp, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e5100)
Location: drivers/acpi/osl.c:1611
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler
  - drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake
  - drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815e5100-ffffffff815e5110: acpi_os_release_lock (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int not_used</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
