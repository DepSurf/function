# Function: <code>ktime_get_mono_fast_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f5570)
Location: kernel/time/timekeeping.c:410
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
```
**Symbols:**

```
ffffffff810f5570-ffffffff810f5603: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fb440)
Location: kernel/time/timekeeping.c:413
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
```
**Symbols:**

```
ffffffff810fb440-ffffffff810fb4c1: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe200)
Location: kernel/time/timekeeping.c:413
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
```
**Symbols:**

```
ffffffff810fe200-ffffffff810fe2ae: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100560)
Location: kernel/time/timekeeping.c:439
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
```
**Symbols:**

```
ffffffff81100560-ffffffff81100605: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c730)
Location: kernel/time/timekeeping.c:458
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
```
**Symbols:**

```
ffffffff8110c730-ffffffff8110c7df: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811182a0)
Location: kernel/time/timekeeping.c:459
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
```
**Symbols:**

```
ffffffff811182a0-ffffffff8111834f: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811238c0)
Location: kernel/time/timekeeping.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_set_runtime_active
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:pm_runtime_autosuspend_expiration
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff811238c0-ffffffff8112396f: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112e0a0)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_set_runtime_active
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8112e0a0-ffffffff8112e133: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113a050)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8113a050-ffffffff8113a0e3: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148810)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81148810-ffffffff811488a5: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81144c80)
Location: kernel/time/timekeeping.c:485
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81144c80-ffffffff81144d15: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145b70)
Location: kernel/time/timekeeping.c:485
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81145b70-ffffffff81145c03: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:485
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81cb0c2a-ffffffff81cb0c4c: ktime_get_mono_fast_ns.cold (STB_LOCAL)
ffffffff81169610-ffffffff811696b0: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:490
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_tai_fast_ns
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81e621c2-ffffffff81e621e4: ktime_get_mono_fast_ns.cold (STB_LOCAL)
ffffffff8119d2a0-ffffffff8119d341: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:490
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_tai_fast_ns
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8205afcb-ffffffff8205afed: ktime_get_mono_fast_ns.cold (STB_LOCAL)
ffffffff811dbc00-ffffffff811dbca1: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:490
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_tai_fast_ns
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/serial_port.c:serial_port_runtime_resume
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff820d98c3-ffffffff820d98e5: ktime_get_mono_fast_ns.cold (STB_LOCAL)
ffffffff811f0250-ffffffff811f02ed: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:490
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_tai_fast_ns
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pmdomain/core.c:total_idle_time_show
  - drivers/pmdomain/core.c:active_time_show
  - drivers/pmdomain/core.c:idle_states_show
  - drivers/pmdomain/core.c:pm_genpd_init
  - drivers/pmdomain/core.c:genpd_update_accounting
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/serial_port.c:serial_port_runtime_suspend
  - drivers/tty/serial/serial_port.c:serial_port_runtime_resume
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff821b51c2-ffffffff821b51e4: ktime_get_mono_fast_ns.cold (STB_LOCAL)
ffffffff81206390-ffffffff8120642d: ktime_get_mono_fast_ns (STB_GLOBAL)
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
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3f18)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffff8000101a3f18-ffff8000101a3fb0: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03edc94)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_break_ctl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_get_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_tx_empty
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_unthrottle
  - drivers/tty/serial/omap-serial.c:serial_omap_throttle
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_rx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_enable_ms
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autosuspend_device
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/musb/musb_core.c:musb_resume
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_start
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_show
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_show
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_show
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - sound/soc/soc-pcm.c:soc_pcm_close
  - sound/soc/soc-pcm.c:soc_pcm_open
```
**Symbols:**

```
c03edc94-c03edd70: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000205e70)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
c000000000205e70-c000000000205f48: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130aee)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffe000130aee-ffffffe000130b7a: ktime_get_mono_fast_ns (STB_GLOBAL)
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
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81132800)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81132800-ffffffff81132893: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125260)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81125260-ffffffff811252f3: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130520)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81130520-ffffffff811305b3: ktime_get_mono_fast_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 ktime_get_mono_fast_ns();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113cf40)
Location: kernel/time/timekeeping.c:472
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/time/timekeeping.c:ktime_get_boot_fast_ns
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/bpf/helpers.c:bpf_ktime_get_ns
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8113cf40-ffffffff8113cfd3: ktime_get_mono_fast_ns (STB_GLOBAL)
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
