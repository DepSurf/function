# Function: <code>strlcpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t strlcpy(char *dest, const char *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1fc0)
Location: lib/string.c:139
Inline: False
Direct callers:
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_get_string
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:SyS_delete_module
  - kernel/module.c:load_module
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/acct.c:do_acct_process
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/events/core.c:perf_event_comm
  - kernel/events/core.c:perf_event_mmap
  - mm/page_alloc.c:setup_numa_zonelist_order
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/super.c:mount_bdev
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/ext4/file.c:ext4_file_open
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - block/elevator.c:__elevator_change
  - block/genhd.c:register_blkdev
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register
  - drivers/clk/clkdev.c:vclkdev_alloc
  - net/core/dev.c:netdev_boot_setup
  - net/core/dev.c:dev_set_alias
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/netpoll.c:__netpoll_setup
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_bind_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff813f1fc0-ffffffff813f2007: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t strlcpy(char *dest, const char *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438960)
Location: lib/string.c:139
Inline: False
Direct callers:
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_get_string
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:SyS_delete_module
  - kernel/acct.c:do_acct_process
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:task_cgroup_path
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_probe.c:fetch_comm_string
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/page_alloc.c:setup_numa_zonelist_order
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/ext4/file.c:ext4_file_open
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - block/elevator.c:__elevator_change
  - block/genhd.c:register_blkdev
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register
  - drivers/clk/clkdev.c:vclkdev_alloc
  - net/core/dev.c:dev_set_alias
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_bind_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81438960-ffffffff814389a7: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t strlcpy(char *dest, const char *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455950)
Location: lib/string.c:139
Inline: False
Direct callers:
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_get_string
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:SyS_delete_module
  - kernel/acct.c:do_acct_process
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:task_cgroup_path
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_probe.c:fetch_comm_string
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/page_alloc.c:setup_numa_zonelist_order
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_name
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/ext4/file.c:ext4_file_open
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/elevator.c:__elevator_change
  - block/genhd.c:register_blkdev
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register
  - net/core/dev.c:dev_set_alias
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81455950-ffffffff81455997: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8209dbc0)
Location: include/linux/string.h:250
Inline: True
Inline callers:
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_get_string
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:SyS_delete_module
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_probe.c:fetch_comm_string
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/ext4/file.c:ext4_file_open
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/console/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:of_led_classdev_register
  - net/core/dev.c:dev_alloc_name
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818f7290-ffffffff818f72d2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff826a3b66)
Location: include/linux/string.h:285
Inline: True
Inline callers:
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:SyS_delete_module
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_probe.c:fetch_comm_string
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/ext4/file.c:ext4_file_open
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:of_led_classdev_register
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8197dc90-ffffffff8197dcd2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff826ccc04)
Location: include/linux/string.h:286
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_probe.c:fetch_comm_string
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_name
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:of_led_classdev_register
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819da170-ffffffff819da1b2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82882c0e)
Location: include/linux/string.h:293
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_name
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:of_led_classdev_register
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a12390-ffffffff81a123d2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82899bdf)
Location: include/linux/string.h:300
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:of_led_classdev_register
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a81810-ffffffff81a81862: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289cbdf)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ab8a20-ffffffff81ab8a72: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82cc324f)
Location: include/linux/string.h:347
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_builtin
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/ext4/file.c:ext4_sample_last_mounted
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:__elevator_change
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:init_uevent_argv
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_name_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup_add
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff815f3690-ffffffff815f36d1: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faf2b4)
Location: include/linux/string.h:341
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_builtin
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:xts_create
  - block/elevator.c:__elevator_change
  - block/genhd.c:__register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:init_uevent_argv
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_name_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup_add
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81617d20-ffffffff81617d61: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b8d42)
Location: include/linux/fortify-string.h:80
Inline: True
Inline callers:
  - init/main.c:setup_boot_config
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_builtin
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_comm
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:xts_create
  - block/elevator.c:__elevator_change
  - block/genhd.c:__register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup_add
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff815fb370-ffffffff815fb3b1: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8329936f)
Location: include/linux/fortify-string.h:80
Inline: True
Inline callers:
  - init/main.c:setup_boot_config
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_builtin
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_comm
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:xts_create
  - block/elevator.c:__elevator_change
  - block/genhd.c:__register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81668c40-ffffffff81668c81: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83447593)
Location: include/linux/fortify-string.h:150
Inline: True
Inline callers:
  - init/main.c:setup_boot_config
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_builtin
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_comm
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:xts_create
  - block/elevator.c:__elevator_change
  - block/genhd.c:__register_blkdev
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:init_uevent_argv
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/processor_idle.c:combine_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81782460-ffffffff817824c3: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/version.c (ffffffff83e61b0d)
Location: include/linux/fortify-string.h:261
Inline: True
Inline callers:
  - init/version.c:early_hostname
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_builtin
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_func_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_comm
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - crypto/xts.c:xts_create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:__register_blkdev
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
  - lib/kobject_uevent.c:init_uevent_argv
```
**Symbols:**

```
ffffffff8203f2e0-ffffffff8203f343: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/version.c (ffffffff83681f2d)
Location: include/linux/fortify-string.h:241
Inline: True
Inline callers:
  - init/version.c:early_hostname
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/acct.c:fill_ac
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - crypto/xts.c:xts_create
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - lib/kobject_uevent.c:init_uevent_argv
```
**Symbols:**

```
ffffffff820bd750-ffffffff820bd7b8: strlcpy (STB_GLOBAL)
```
</details>
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
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800011430b84)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__arm64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_get_drvinfo
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_getdrvinfo
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_getdrvinfo
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_getdrvinfo
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/of/base.c:of_modalias_node
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010d92e90-ffff800010d92ef0: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c1500b40)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/atags_parse.c:setup_machine_tags
  - arch/arm/kernel/atags_parse.c:parse_tag_cmdline
  - arch/arm/kernel/vdso.c:find_symbol
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__se_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/clk/mvebu/dove-divider.c:dove_divider_clk_init
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_get_info
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/mtd/parsers/cmdlinepart.c:parse_cmdline_partitions
  - drivers/mtd/parsers/cmdlinepart.c:newpart
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_get_drvinfo
  - drivers/net/ethernet/ti/cpsw.c:cpsw_get_drvinfo
  - drivers/net/ethernet/ti/cpsw.c:cpsw_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/of/base.c:of_modalias_node
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - sound/core/init.c:snd_card_set_id_no_lock
  - sound/core/init.c:snd_card_new
  - sound/core/control.c:snd_ctl_new1
  - sound/core/ctljack.c:snd_kctl_jack_new
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:snd_timer_new
  - sound/core/pcm.c:_snd_pcm_new
  - sound/core/pcm_native.c:snd_pcm_info
  - sound/core/pcm_native.c:snd_pcm_info
  - sound/core/pcm_native.c:snd_pcm_info
  - sound/core/compress_offload.c:snd_compress_new
  - sound/soc/soc-core.c:fmt_single_name
  - sound/soc/soc-core.c:fmt_single_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0e8f730-c0e8f780: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (c000000001343c14)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/powerpc/kernel/vdso.c:find_symbol64
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/pci-ioda.c:pe_level_printk
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__se_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/cpuidle/cpuidle-powernv.c:add_powernv_state
  - drivers/cpuidle/cpuidle-powernv.c:add_powernv_state
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/base.c:of_modalias_node
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000ed6eb0-c000000000ed6f48: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t strlcpy(char *dest, const char *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bd032)
Location: lib/string.c:141
Inline: False
Direct callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/base.c:of_modalias_node
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0008bd032-ffffffe0008bd088: strlcpy (STB_GLOBAL)
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
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8288abdf)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a57870-ffffffff81a578c2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82888b83)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/vxlan.c:vxlan_get_drvinfo
  - drivers/net/vxlan.c:vxlan_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_init_net
  - net/ipv4/ip_tunnel.c:__ip_tunnel_create
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a14950-ffffffff81a149a2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289dbdf)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ac3c60-ffffffff81ac3cb2: strlcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t strlcpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8289dbdf)
Location: include/linux/string.h:321
Inline: True
Inline callers:
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_sysfs_init
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
  - kernel/kallsyms.c:update_iter
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_comm
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/dynamic_debug.c:ddebug_setup_query
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/leds/led-class.c:led_classdev_register_ext
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/dev.c:netdev_boot_setup
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_ioctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ad0130-ffffffff81ad0182: strlcpy (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *p</code>
</li>
<li>
<b>Param added. </b>
<code>const char *q</code>
</li>
<li>
<b>Param removed. </b>
<code>char *dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *src</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *p</code> ➡️ <code>const char * p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *q</code> ➡️ <code>const const char * q</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char *src</code>
</li>
<li>
<b>Param removed. </b>
<code>char *p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *q</code>
</li>
</ul>
</details>
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
