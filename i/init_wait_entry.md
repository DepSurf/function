# Function: <code>init_wait_entry</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_wait_entry(wait_queue_t *wait, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cce80)
Location: kernel/sched/wait.c:199
Inline: False
Direct callers:
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/backing-dev.c:bdi_unregister
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_req
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810cce80-ffffffff810cceae: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9750)
Location: kernel/sched/wait.c:201
Inline: False
Direct callers:
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:__request_module
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/bitmap.c:bitmap_wait_behind_writes
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_areq
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810c9750-ffffffff810c977e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0f90)
Location: kernel/sched/wait.c:256
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_areq
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810d0f90-ffffffff810d0fbe: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9540)
Location: kernel/sched/wait.c:250
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/super.c:__get_super_thawed
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810d9540-ffffffff810d956e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e3040)
Location: kernel/sched/wait.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/super.c:__get_super_thawed
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810e3040-ffffffff810e306e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9be0)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810e9be0-ffffffff810e9c0e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f55b0)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810f55b0-ffffffff810f55de: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fecf0)
Location: kernel/sched/wait.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module.c:add_unformed_module
  - kernel/module.c:resolve_symbol_wait
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:xol_take_insn_slot
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/quota/dquot.c:invalidate_dquots
  - fs/kernfs/dir.c:kernfs_drain
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_xs.c:xs_request_enter
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810fecf0-ffffffff810fed1e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd5f0)
Location: kernel/sched/wait.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module.c:add_unformed_module
  - kernel/module.c:resolve_symbol_wait
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:xol_take_insn_slot
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_drain
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dax.c:alloc_dax_mapping_reclaim
  - fs/fuse/dax.c:__fuse_dax_fault
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_xs.c:xs_request_enter
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810fd5f0-ffffffff810fd61e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff9d0)
Location: kernel/sched/wait.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module.c:add_unformed_module
  - kernel/module.c:simplify_symbols
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:pre_ssout
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810ff9d0-ffffffff810ff9fe: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111baa0)
Location: kernel/sched/wait.c:294
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module.c:add_unformed_module
  - kernel/module.c:simplify_symbols
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:pre_ssout
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff8111baa0-ffffffff8111bace: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81143c87)
Location: kernel/sched/wait.c:293
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module/main.c:add_unformed_module
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:pre_ssout
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff8113be50-ffffffff8113be88: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116f5f0)
Location: kernel/sched/wait.c:297
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module/main.c:add_unformed_module
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:pre_ssout
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_drain
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff81166960-ffffffff81166998: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81180ed0)
Location: kernel/sched/wait.c:297
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:pre_ssout
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/kernfs/dir.c:kernfs_drain
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff81176dd0-ffffffff81176e08: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118ec20)
Location: kernel/sched/wait.c:262
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:pre_ssout
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/kernfs/dir.c:kernfs_drain
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/gpu/drm/drm_file.c:drm_read
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_flush
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_file_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff81184d90-ffffffff81184dc8: init_wait_entry (STB_GLOBAL)
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
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158098)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__arm64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffff800010158098-ffff8000101580e0: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5cd4)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:do_io_getevents
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_trx_complete
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/host/sdhci.c:sdhci_send_tuning
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_wait_for_idle
  - sound/core/init.c:snd_card_disconnect_sync
  - sound/core/compress_offload.c:snd_compress_wait_for_drain
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
c03a5cd4-c03a5d1c: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acd60)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtasd.c:rtas_log_read
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_wait_response_interruptible
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_wait_response
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/fs-writeback.c:wb_wait_for_completion
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/hvc/hvsi.c:wait_for_state
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_send
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_recv
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_wait_writes
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
c0000000001acd60-c0000000001acd98: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000feb94)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffe0000feb94-ffffffe0000febd4: init_wait_entry (STB_GLOBAL)
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
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee9b0)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:nvme_wait_reset
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810ee9b0-ffffffff810ee9de: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810dea40)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler
  - drivers/scsi/storvsc_drv.c:storvsc_dev_remove
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:nvme_wait_reset
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810dea40-ffffffff810dea6e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebae0)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810ebae0-ffffffff810ebb0e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_wait_entry(struct wait_queue_entry *wq_entry, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6b40)
Location: kernel/sched/wait.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/workqueue.c:put_unbound_pool
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/events/uprobes.c:handle_swbp
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/file.c:expand_files
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_flush_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/netlink/genetlink.c:genl_unregister_family
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810f6b40-ffffffff810f6b6e: init_wait_entry (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t *wait</code>
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
