# Function: <code>__real_strlcpy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/params.c:param_get_string
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/trace_probe.c:fetch_comm_string
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/ext4/file.c:ext4_file_open
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
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
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:fetch_comm_string
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/ext4/file.c:ext4_file_open
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
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
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:fetch_comm_string
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
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
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget_userns
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/algapi.c:crypto_check_alg
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
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
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/ext4/file.c:ext4_sample_last_mounted
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/kobject_uevent.c:init_uevent_argv
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_name_device
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:netdev_boot_setup_add
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - mm/zswap.c:zswap_pool_create
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - lib/kobject_uevent.c:init_uevent_argv
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - net/core/devlink.c:devlink_param_value_str_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - net/core/devlink.c:devlink_param_value_str_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:add_kallsyms
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - net/core/devlink.c:devlink_param_value_str_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - lib/kobject_uevent.c:init_uevent_argv
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/processor_idle.c:combine_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_func_address_lookup
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - lib/kobject_uevent.c:init_uevent_argv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - lib/kobject_uevent.c:init_uevent_argv
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_getdrvinfo
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/of/base.c:of_modalias_node
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/atags_parse.c:setup_machine_tags
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/mtd/parsers/cmdlinepart.c:parse_cmdline_partitions
  - drivers/mtd/parsers/cmdlinepart.c:newpart
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_drvinfo
  - drivers/net/ethernet/ti/cpsw.c:cpsw_get_drvinfo
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
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
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:snd_timer_new
  - sound/core/pcm.c:_snd_pcm_new
  - sound/core/pcm_native.c:snd_pcm_info
  - sound/core/pcm_native.c:snd_pcm_info
  - sound/core/pcm_native.c:snd_pcm_info
  - sound/core/compress_offload.c:snd_compress_new
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/cpuidle/cpuidle-powernv.c:add_powernv_state
  - drivers/cpuidle/cpuidle-powernv.c:add_powernv_state
  - drivers/of/base.c:of_modalias_node
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
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
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:post_relocation
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/relay.c:relay_late_setup_files
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/char_dev.c:__register_chrdev_region
  - fs/exec.c:__set_task_comm
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/integrity/ima/ima_api.c:ima_d_path
  - crypto/api.c:crypto_larval_alloc
  - crypto/xts.c:create
  - block/genhd.c:register_blkdev
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - drivers/acpi/processor_idle.c:flatten_lpi_states
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:async_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:async_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/eisa/eisa-bus.c:eisa_init_device
  - net/core/dev.c:netdev_boot_setup
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/devlink.c:devlink_param_value_str_fill
  - net/sched/sch_api.c:qdisc_get_default
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/kobject_uevent.c:kobject_uevent_env
```
</details>
</li>
</ul>

## Differences
