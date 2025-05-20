# Function: <code>kernfs_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8128b0c0)
Location: fs/kernfs/file.c:866
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:action_store
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/bitmap.c:bitmap_endwrite
```
**Symbols:**

```
ffffffff8128b0c0-ffffffff8128b150: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812b85f0)
Location: fs/kernfs/file.c:887
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/bitmap.c:bitmap_endwrite
```
**Symbols:**

```
ffffffff812b85f0-ffffffff812b8680: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812cdd90)
Location: fs/kernfs/file.c:887
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/bitmap.c:bitmap_endwrite
```
**Symbols:**

```
ffffffff812cdd90-ffffffff812cde20: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812db390)
Location: fs/kernfs/file.c:933
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/bitmap.c:bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff812db390-ffffffff812db40d: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff812ffc80)
Location: fs/kernfs/file.c:933
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff812ffc80-ffffffff812ffd01: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8132d980)
Location: fs/kernfs/file.c:933
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff8132d980-ffffffff8132d9fe: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81344d30)
Location: fs/kernfs/file.c:921
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff81344d30-ffffffff81344df2: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/file.c (0)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff8136e265-ffffffff8136e278: kernfs_notify.cold (STB_LOCAL)
ffffffff8136cf90-ffffffff8136d04e: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81385110)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff81385110-ffffffff813851d1: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813d0410)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff813d0410-ffffffff813d04d1: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e1fe0)
Location: fs/kernfs/file.c:913
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff813e1fe0-ffffffff813e20a1: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e8c10)
Location: fs/kernfs/file.c:913
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff813e8c10-ffffffff813e8cd1: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143a940)
Location: fs/kernfs/file.c:913
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff8143a940-ffffffff8143aa01: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b6120)
Location: fs/kernfs/file.c:915
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff814b6120-ffffffff814b61fc: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154cef0)
Location: fs/kernfs/file.c:975
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff8154cef0-ffffffff8154cfb9: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81584bc0)
Location: fs/kernfs/file.c:975
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:update_triggers
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/usb/core/hub.c:update_port_device_state
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff81584bc0-ffffffff81584c89: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bd610)
Location: fs/kernfs/file.c:953
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:update_triggers
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/usb/core/hub.c:update_port_device_state
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff815bd610-ffffffff815bd6d9: kernfs_notify (STB_GLOBAL)
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
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffff800010455248)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffff800010455248-ffff80001045540c: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c0616ca0)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
c0616ca0-c0616da4: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c00000000056da00)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
c00000000056da00-c00000000056db68: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffe0002e661a)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffe0002e661a-ffffffe0002e66f8: kernfs_notify (STB_GLOBAL)
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
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8137d6f0)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
**Symbols:**

```
ffffffff8137d6f0-ffffffff8137d7b1: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8136e1a0)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/acpi/nfit/core.c:acpi_nfit_scrub
  - drivers/acpi/nfit/core.c:__acpi_nvdimm_notify
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/pmem.c:pmem_do_bvec
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
**Symbols:**

```
ffffffff8136e1a0-ffffffff8136e261: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8137b1c0)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff8137b1c0-ffffffff8137b281: kernfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernfs_notify(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8138ecb0)
Location: fs/kernfs/file.c:931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - fs/sysfs/file.c:sysfs_notify
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
  - drivers/nvdimm/region.c:nd_region_notify
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
**Symbols:**

```
ffffffff8138ecb0-ffffffff8138ed71: kernfs_notify (STB_GLOBAL)
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
