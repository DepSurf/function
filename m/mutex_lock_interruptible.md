# Function: <code>mutex_lock_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81821f60)
Location: kernel/locking/mutex.c:786
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:SyS_delete_module
  - fs/libfs.c:simple_attr_read
  - fs/libfs.c:simple_attr_write
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_open
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_grab_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_register_device
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
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
  - drivers/md/md.c:md_open
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - net/unix/af_unix.c:unix_set_peek_off
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81821f60-ffffffff81821f9d: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189c3c0)
Location: kernel/locking/mutex.c:790
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:SyS_delete_module
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_open
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/md/md.c:md_open
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff8189c3c0-ffffffff8189c3fd: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d0f10)
Location: kernel/locking/mutex.c:930
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:SyS_delete_module
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/md/md.c:md_open
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff818d0f10-ffffffff818d0f42: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81908100)
Location: kernel/locking/mutex.c:1095
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:SyS_delete_module
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/md/md.c:md_open
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81908100-ffffffff8190813a: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819921e0)
Location: kernel/locking/mutex.c:1095
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:SyS_delete_module
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:genpd_summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/md/md.c:md_open
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff819921e0-ffffffff8199221a: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819eef90)
Location: kernel/locking/mutex.c:1097
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:genpd_summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff819eef90-ffffffff819eefc4: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2a2d0)
Location: kernel/locking/mutex.c:1275
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81a2a2d0-ffffffff81a2a304: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9aa60)
Location: kernel/locking/mutex.c:1280
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81a9aa60-ffffffff81a9aa98: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad23b0)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81ad23b0-ffffffff81ad23e8: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bca4a0)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_send
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/exec.c:__do_execve_file
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_setup
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81bca4a0-ffffffff81bca4dc: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c43300)
Location: kernel/locking/mutex.c:1309
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_send
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_setup
  - drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81c43300-ffffffff81c4333c: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c349c0)
Location: kernel/locking/mutex.c:1307
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81c349c0-ffffffff81c349fc: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d53250)
Location: kernel/locking/mutex.c:921
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_available_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
  - drivers/ptp/ptp_clock.c:ptp_clock_settime
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81d53250-ffffffff81d5328c: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f24b30)
Location: kernel/locking/mutex.c:977
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - mm/huge_memory.c:split_huge_pages_write
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_available_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:read_descriptors
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
  - drivers/ptp/ptp_clock.c:ptp_clock_settime
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81f24b30-ffffffff81f24b7a: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820d00a0)
Location: kernel/locking/mutex.c:977
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - mm/huge_memory.c:split_huge_pages_write
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_available_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
  - drivers/ptp/ptp_clock.c:ptp_clock_settime
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjtime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff820d00a0-ffffffff820d00ea: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82153860)
Location: kernel/locking/mutex.c:977
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - mm/huge_memory.c:split_huge_pages_write
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_available_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
  - drivers/ptp/ptp_clock.c:ptp_clock_settime
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjtime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_set_read_only
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff82153860-ffffffff821538aa: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff822366a0)
Location: kernel/locking/mutex.c:982
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - mm/huge_memory.c:split_huge_pages_write
  - fs/namespace.c:__do_sys_fsmount
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_commit_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/acpi/apei/erst.c:erst_open_pstore
  - drivers/pmdomain/core.c:summary_show
  - drivers/pmdomain/core.c:genpd_lock_interruptible_mtx
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_available_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/gpu/drm/drm_file.c:drm_read
  - drivers/gpu/drm/drm_file.c:drm_read
  - drivers/gpu/drm/drm_sysfs.c:status_store
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_compat
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softraw
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_softrepeat
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_set
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_scroll
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_force_release
  - drivers/input/keyboard/atkbd.c:atkbd_do_set_extra
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
  - drivers/ptp/ptp_clock.c:ptp_clock_settime
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_show
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
  - drivers/ptp/ptp_vclock.c:ptp_get_vclocks_index
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_settime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjtime
  - drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine
  - drivers/md/md.c:md_open
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-autodetect.c:md_setup_drive
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
```
**Symbols:**

```
ffffffff822366a0-ffffffff822366ea: mutex_lock_interruptible (STB_GLOBAL)
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
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da36f0)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__arm64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffff800010da36f0-ffff800010da3758: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9c7fc)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__se_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/exec.c:__do_execve_file
  - fs/namespace.c:__se_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
c0e9c7fc-c0e9c85c: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5d10)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store
  - arch/powerpc/platforms/powernv/opal-powercap.c:powercap_show
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_store
  - arch/powerpc/platforms/powernv/opal-psr.c:psr_show
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__se_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__se_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
c000000000ee5d10-c000000000ee5d98: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c7520)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__se_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/exec.c:__do_execve_file
  - fs/namespace.c:__se_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffe0008c7520-ffffffe0008c7566: mutex_lock_interruptible (STB_GLOBAL)
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
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a71220)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81a71220-ffffffff81a71258: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2d610)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81a2d610-ffffffff81a2d648: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81add630)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81add630-ffffffff81add668: mutex_lock_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mutex_lock_interruptible(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae91e0)
Location: kernel/locking/mutex.c:1306
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/printk/printk.c:devkmsg_read
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_attr_read
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:fscontext_read
  - fs/proc/base.c:proc_pid_attr_write
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_namespace
  - security/tomoyo/domain.c:tomoyo_update_domain
  - security/tomoyo/domain.c:tomoyo_update_policy
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/apparmor/apparmorfs.c:attr_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - block/blk-mq-debugfs.c:hctx_sched_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_bitmap_show
  - block/blk-mq-debugfs.c:hctx_tags_show
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/hw_random/core.c:hwrng_attr_available_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/base/power/domain.c:summary_show
  - drivers/base/power/domain.c:genpd_lock_interruptible_mtx
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible
  - drivers/usb/core/sysfs.c:supports_autosuspend_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u2_show
  - drivers/usb/core/sysfs.c:usb3_hardware_lpm_u1_show
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/usb/core/sysfs.c:persist_store
  - drivers/usb/core/sysfs.c:avoid_reset_quirk_store
  - drivers/usb/core/sysfs.c:serial_show
  - drivers/usb/core/sysfs.c:manufacturer_show
  - drivers/usb/core/sysfs.c:product_show
  - drivers/usb/core/sysfs.c:bConfigurationValue_store
  - drivers/usb/core/sysfs.c:bConfigurationValue_show
  - drivers/usb/core/sysfs.c:configuration_show
  - drivers/usb/core/sysfs.c:bMaxPower_show
  - drivers/usb/core/sysfs.c:bmAttributes_show
  - drivers/usb/core/sysfs.c:bNumInterfaces_show
  - drivers/input/serio/serio.c:drvctl_store
  - drivers/input/input.c:input_register_handle
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_flush_device
  - drivers/input/input.c:input_open_device
  - drivers/input/input.c:input_grab_device
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/mousedev.c:mixdev_open_devices
  - drivers/input/mousedev.c:mousedev_open_device
  - drivers/input/evdev.c:evdev_ioctl_handler
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_open
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_sysfs.c:ptp_pin_store
  - drivers/ptp/ptp_sysfs.c:ptp_pin_show
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
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
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:chunk_size_store
  - drivers/md/md.c:raid_disks_store
  - drivers/md/md.c:layout_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:rdev_attr_store
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_sysfs.c:firmware_store
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_set_peek_off
```
**Symbols:**

```
ffffffff81ae91e0-ffffffff81ae9205: mutex_lock_interruptible (STB_GLOBAL)
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
