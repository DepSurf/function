# Function: <code>acpi_os_acquire_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a5d5)
Location: drivers/acpi/osl.c:1703
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
```
**Symbols:**

```
ffffffff8147a5d5-ffffffff8147a5e5: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8ba3)
Location: drivers/acpi/osl.c:1509
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
```
**Symbols:**

```
ffffffff814c8ba3-ffffffff814c8bb3: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814eaae7)
Location: drivers/acpi/osl.c:1504
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
```
**Symbols:**

```
ffffffff814eaae7-ffffffff814eaaf7: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6980)
Location: drivers/acpi/osl.c:1503
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
ffffffff814f6980-ffffffff814f6990: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815379d0)
Location: drivers/acpi/osl.c:1513
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
ffffffff815379d0-ffffffff815379e0: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d560)
Location: drivers/acpi/osl.c:1588
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
ffffffff8156d560-ffffffff8156d570: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81585120)
Location: drivers/acpi/osl.c:1594
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
ffffffff81585120-ffffffff81585130: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5d40)
Location: drivers/acpi/osl.c:1580
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
ffffffff815b5d40-ffffffff815b5d50: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6f70)
Location: drivers/acpi/osl.c:1600
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
ffffffff815d6f70-ffffffff815d6f80: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680ca0)
Location: drivers/acpi/osl.c:1600
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff81680ca0-ffffffff81680cb0: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f790)
Location: drivers/acpi/osl.c:1619
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff8169f790-ffffffff8169f7a0: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682430)
Location: drivers/acpi/osl.c:1609
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff81682430-ffffffff81682440: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f75a0)
Location: drivers/acpi/osl.c:1604
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff816f75a0-ffffffff816f75b0: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824500)
Location: drivers/acpi/osl.c:1521
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff81824500-ffffffff81824516: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955940)
Location: drivers/acpi/osl.c:1521
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff81955940-ffffffff81955956: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199bd40)
Location: drivers/acpi/osl.c:1521
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff8199bd40-ffffffff8199bd56: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e4290)
Location: drivers/acpi/osl.c:1515
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
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
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
ffffffff819e4290-ffffffff819e42a8: acpi_os_acquire_lock (STB_GLOBAL)
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
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764348)
Location: drivers/acpi/osl.c:1600
Inline: False
```
**Symbols:**

```
ffff800010764348-ffff8000107643d8: acpi_os_acquire_lock (STB_GLOBAL)
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
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca4a0)
Location: drivers/acpi/osl.c:1600
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
ffffffff815ca4a0-ffffffff815ca4b0: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3520)
Location: drivers/acpi/osl.c:1600
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
ffffffff815b3520-ffffffff815b3530: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb250)
Location: drivers/acpi/osl.c:1600
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
ffffffff815cb250-ffffffff815cb260: acpi_os_acquire_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t *lockp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e50f0)
Location: drivers/acpi/osl.c:1600
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
ffffffff815e50f0-ffffffff815e5100: acpi_os_acquire_lock (STB_GLOBAL)
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
