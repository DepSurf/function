# Function: <code>mddev_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168de7a)
Location: drivers/md/md.h:469
Inline: True
Inline callers:
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
In drivers/md/md.c (ffffffff816fc3c4)
Location: drivers/md/md.h:446
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/bitmap.c (ffffffff81700d53)
Location: drivers/md/md.h:446
Inline: True
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
In drivers/md/md.c (ffffffff8172c9f6)
Location: drivers/md/md.h:472
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/bitmap.c (ffffffff81732ab3)
Location: drivers/md/md.h:472
Inline: True
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
In drivers/md/md.c (ffffffff817452fc)
Location: drivers/md/md.h:483
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/bitmap.c (ffffffff8174b883)
Location: drivers/md/md.h:483
Inline: True
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
In drivers/md/md.c (ffffffff817b74cc)
Location: drivers/md/md.h:490
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff817bdbd3)
Location: drivers/md/md.h:490
Inline: True
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
In drivers/md/md.c (ffffffff817fe92e)
Location: drivers/md/md.h:501
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81805bd3)
Location: drivers/md/md.h:501
Inline: True
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
In drivers/md/md.c (ffffffff8182aace)
Location: drivers/md/md.h:502
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81831dd3)
Location: drivers/md/md.h:502
Inline: True
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
In drivers/md/md.c (ffffffff8186d003)
Location: drivers/md/md.h:511
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81874583)
Location: drivers/md/md.h:511
Inline: True
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
In drivers/md/md.c (ffffffff8189edf3)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff818a6393)
Location: drivers/md/md.h:518
Inline: True
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
In drivers/md/md.c (ffffffff8196ef5b)
Location: drivers/md/md.h:527
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81976185)
Location: drivers/md/md.h:527
Inline: True
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
In drivers/md/md.c (ffffffff8196bd6b)
Location: drivers/md/md.h:533
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff8197b175)
Location: drivers/md/md.h:533
Inline: True
```
```
In drivers/md/md-autodetect.c (ffffffff830130d0)
Location: drivers/md/md.h:533
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffffffff81950f8b)
Location: drivers/md/md.h:532
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff8195f395)
Location: drivers/md/md.h:532
Inline: True
```
```
In drivers/md/md-autodetect.c (ffffffff8321e1ff)
Location: drivers/md/md.h:532
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffffffff819f64cb)
Location: drivers/md/md.h:533
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81a04cd5)
Location: drivers/md/md.h:533
Inline: True
```
```
In drivers/md/md-autodetect.c (ffffffff833075a9)
Location: drivers/md/md.h:533
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffffffff81b5c62c)
Location: drivers/md/md.h:541
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c9b5)
Location: drivers/md/md.h:541
Inline: True
```
```
In drivers/md/md-autodetect.c (ffffffff834c0a56)
Location: drivers/md/md.h:541
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffffffff81cf6adc)
Location: drivers/md/md.h:558
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81d08ab5)
Location: drivers/md/md.h:558
Inline: True
```
```
In drivers/md/md-autodetect.c (ffffffff83eff9db)
Location: drivers/md/md.h:558
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffffffff81d68df9)
Location: drivers/md/md.h:579
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81d6fa61)
Location: drivers/md/md.h:579
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:backlog_store
```
```
In drivers/md/md-autodetect.c (ffffffff83725810)
Location: drivers/md/md.h:579
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffffffff81e1f9f9)
Location: drivers/md/md.h:561
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81e25a8e)
Location: drivers/md/md.h:561
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:backlog_store
```
```
In drivers/md/md-autodetect.c (ffffffff83959706)
Location: drivers/md/md.h:561
Inline: True
Inline callers:
  - drivers/md/md-autodetect.c:md_setup_drive
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
In drivers/md/md.c (ffff800010af38d8)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffff800010afb304)
Location: drivers/md/md.h:518
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd4f0c)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (c0bdbd68)
Location: drivers/md/md.h:518
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000be25f4)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (c000000000be94fc)
Location: drivers/md/md.h:518
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e7166)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffe0006ecaca)
Location: drivers/md/md.h:518
Inline: True
```
</details>
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
In drivers/md/md.c (ffffffff81844c73)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff8184c213)
Location: drivers/md/md.h:518
Inline: True
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
In drivers/md/md.c (ffffffff8180c2d3)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff81813833)
Location: drivers/md/md.h:518
Inline: True
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
In drivers/md/md.c (ffffffff818942a3)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff8189b843)
Location: drivers/md/md.h:518
Inline: True
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
In drivers/md/md.c (ffffffff818afef2)
Location: drivers/md/md.h:518
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
```
In drivers/md/md-bitmap.c (ffffffff818b79f3)
Location: drivers/md/md.h:518
Inline: True
```
</details>
</li>
</ul>

## Differences
