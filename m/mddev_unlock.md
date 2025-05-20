# Function: <code>mddev_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168dd60)
Location: drivers/md/md.c:592
Inline: False
Direct callers:
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8168dd60-ffffffff8168de3a: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816ef2c0)
Location: drivers/md/md.c:587
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff816ef2c0-ffffffff816ef397: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817206a0)
Location: drivers/md/md.c:600
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff817206a0-ffffffff8172077a: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173ae20)
Location: drivers/md/md.c:612
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff8173ae20-ffffffff8173aef3: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817aa0b0)
Location: drivers/md/md.c:646
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff817aa0b0-ffffffff817aa19b: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f6a60)
Location: drivers/md/md.c:657
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff817f6a60-ffffffff817f6b4b: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818229e0)
Location: drivers/md/md.c:650
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff818229e0-ffffffff81822acb: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81864f90)
Location: drivers/md/md.c:711
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff81864f90-ffffffff8186507b: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81896cd0)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff81896cd0-ffffffff81896dbb: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81964300)
Location: drivers/md/md.c:849
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff81964300-ffffffff819643eb: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196adc0)
Location: drivers/md/md.c:831
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff8196adc0-ffffffff8196aee9: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81950050)
Location: drivers/md/md.c:790
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81950050-ffffffff81950179: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f5500)
Location: drivers/md/md.c:791
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff819f5500-ffffffff819f5629: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b589e0)
Location: drivers/md/md.c:796
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81b589e0-ffffffff81b58b15: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf0ac0)
Location: drivers/md/md.c:785
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81cf0ac0-ffffffff81cf0bf5: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d65e80)
Location: drivers/md/md.c:753
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81d65e80-ffffffff81d66085: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1d4a0)
Location: drivers/md/md.c:864
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:metadata_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:bitmap_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81e1d4a0-ffffffff81e1d6a5: mddev_unlock (STB_GLOBAL)
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
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aebce8)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffff800010aebce8-ffff800010aebe1c: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc6a38)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
c0bc6a38-c0bc6b34: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bce1f0)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
c000000000bce1f0-c000000000bce3d4: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006df392)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffe0006df392-ffffffe0006df4a0: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183cb50)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff8183cb50-ffffffff8183cc3b: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818041b0)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff818041b0-ffffffff8180429b: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188c180)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff8188c180-ffffffff8188c26b: mddev_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mddev_unlock(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a4110)
Location: drivers/md/md.c:723
Inline: False
Direct callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_stop_writes
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_direction_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:reshape_position_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_hi_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:suspend_lo_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
```
**Symbols:**

```
ffffffff818a4110-ffffffff818a41f9: mddev_unlock (STB_GLOBAL)
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
