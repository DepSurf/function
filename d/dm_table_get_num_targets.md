# Function: <code>dm_table_get_num_targets</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a6e90)
Location: drivers/md/dm-table.c:1534
Inline: True
Direct callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:retrieve_status
```
**Symbols:**

```
ffffffff816a6e90-ffffffff816a6ea1: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706fe2)
Location: drivers/md/dm-table.c:1636
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
Direct callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff817071d0-ffffffff817071e1: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81738ebd)
Location: drivers/md/dm-table.c:1637
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
Direct callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff817390a0-ffffffff817390b1: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8175256a)
Location: drivers/md/dm-table.c:1864
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81752930-ffffffff81752941: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c4777)
Location: drivers/md/dm-table.c:1854
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_calculate_queue_limits
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_get_wildcard_target
Direct callers:
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff817c4b70-ffffffff817c4b81: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180d191)
Location: drivers/md/dm-table.c:1942
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
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8180d730-ffffffff8180d741: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818390d3)
Location: drivers/md/dm-table.c:1935
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
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81839680-ffffffff81839691: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187bc6a)
Location: drivers/md/dm-table.c:1981
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8187c1c0-ffffffff8187c1d1: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ada4a)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff818adfa0-ffffffff818adfb1: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197dd1c)
Location: drivers/md/dm-table.c:1957
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
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8197e200-ffffffff8197e211: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819822ac)
Location: drivers/md/dm-table.c:1886
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
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81982840-ffffffff81982851: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8196666f)
Location: drivers/md/dm-table.c:2083
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
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81966c60-ffffffff81966c71: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0e87f)
Location: drivers/md/dm-table.c:2079
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
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81a0ee60-ffffffff81a0ee71: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b76fd1)
Location: drivers/md/dm-table.c:2070
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
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81b77550-ffffffff81b77567: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b0457c)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffff800010b04a48-ffff800010b04a70: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be35a8)
Location: drivers/md/dm-table.c:1979
Inline: True
Inline callers:
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
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
c0be3a40-c0be3a5c: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf3f74)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
c000000000bf45e0-c000000000bf45f0: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f37de)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffe0006f3bd8-ffffffe0006f3bfc: dm_table_get_num_targets (STB_GLOBAL)
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
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818538ca)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81853e20-ffffffff81853e31: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181aeda)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8181b430-ffffffff8181b441: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a2efa)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff818a3450-ffffffff818a3461: dm_table_get_num_targets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bf13a)
Location: drivers/md/dm-table.c:1979
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
  - drivers/md/dm-table.c:dm_table_supports_dax
Direct callers:
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:retrieve_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff818bf690-ffffffff818bf6a1: dm_table_get_num_targets (STB_GLOBAL)
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
