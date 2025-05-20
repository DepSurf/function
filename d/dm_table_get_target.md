# Function: <code>dm_table_get_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a57d5)
Location: drivers/md/dm-table.c:1164
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
Direct callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff816a6880-ffffffff816a68ac: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706e62)
Location: drivers/md/dm-table.c:1266
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81706b00-ffffffff81706b2c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81738d3d)
Location: drivers/md/dm-table.c:1267
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff817389d0-ffffffff817389fc: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817524c2)
Location: drivers/md/dm-table.c:1318
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81751f30-ffffffff81751f5c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c46a8)
Location: drivers/md/dm-table.c:1320
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff817c4110-ffffffff817c413c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180d1a6)
Location: drivers/md/dm-table.c:1358
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff8180cc00-ffffffff8180cc2c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818390dd)
Location: drivers/md/dm-table.c:1338
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81838b30-ffffffff81838b5c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187bcc1)
Location: drivers/md/dm-table.c:1351
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff8187b6c0-ffffffff8187b6ec: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818adaa1)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff818ad4b0-ffffffff818ad4dc: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197dd6a)
Location: drivers/md/dm-table.c:1325
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_all_devices_attribute
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff8197d780-ffffffff8197d7ac: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81982273)
Location: drivers/md/dm-table.c:1264
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
Direct callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81981d00-ffffffff81981d2c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81966636)
Location: drivers/md/dm-table.c:1460
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
Direct callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff819660c0-ffffffff819660ec: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0e846)
Location: drivers/md/dm-table.c:1455
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
Direct callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81a0e2b0-ffffffff81a0e2dc: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b76f9c)
Location: drivers/md/dm-table.c:1447
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_supports_poll
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
Direct callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81b769f0-ffffffff81b76a28: dm_table_get_target (STB_GLOBAL)
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
In drivers/md/dm-zone.c (ffffffff81d09d7e)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d0ac68)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In drivers/md/dm.c (ffffffff81d0f58d)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81d14b30)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_postsuspend_targets
  - drivers/md/dm-table.c:dm_table_presuspend_undo_targets
  - drivers/md/dm-table.c:dm_table_presuspend_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_supports_poll
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_table_destroy
```
```
In drivers/md/dm-ioctl.c (ffffffff81d16e41)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_status
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
In drivers/md/dm-zone.c (ffffffff81d72ecf)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d73d9e)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In drivers/md/dm.c (ffffffff81d78989)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81d7dc60)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_postsuspend_targets
  - drivers/md/dm-table.c:dm_table_presuspend_undo_targets
  - drivers/md/dm-table.c:dm_table_presuspend_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_supports_poll
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_table_destroy
```
```
In drivers/md/dm-ioctl.c (ffffffff81d7ff14)
Location: drivers/md/dm-core.h:229
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_status
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
In drivers/md/dm-zone.c (ffffffff81e29fcf)
Location: drivers/md/dm-core.h:232
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81e2aeae)
Location: drivers/md/dm-core.h:232
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In drivers/md/dm.c (ffffffff81e2fbc1)
Location: drivers/md/dm-core.h:232
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81e35020)
Location: drivers/md/dm-core.h:232
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_resume_targets
  - drivers/md/dm-table.c:dm_table_postsuspend_targets
  - drivers/md/dm-table.c:dm_table_presuspend_undo_targets
  - drivers/md/dm-table.c:dm_table_presuspend_targets
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:validate_hardware_zoned
  - drivers/md/dm-table.c:validate_hardware_zoned
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_supports_poll
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
  - drivers/md/dm-table.c:dm_table_destroy
```
```
In drivers/md/dm-ioctl.c (ffffffff81e37605)
Location: drivers/md/dm-core.h:232
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:retrieve_status
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b045cc)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffff800010b04030-ffff800010b04080: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be3604)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_all_devices_attribute
  - drivers/md/dm-table.c:dm_table_supports_flush
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
  - drivers/md/dm-table.c:validate_hardware_logical_block_alignment
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
c0be3084-c0be30b0: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf3fe0)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
c000000000bf38f0-c000000000bf3928: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f37ec)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffe0006f33ac-ffffffe0006f33fa: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81853921)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff81853330-ffffffff8185335c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181af31)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff8181a940-ffffffff8181a96c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a2f51)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff818a2960-ffffffff818a298c: dm_table_get_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_target(struct dm_table *t, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bf191)
Location: drivers/md/dm-table.c:1349
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_has_no_data_devices
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff818beba0-ffffffff818bebcc: dm_table_get_target (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
