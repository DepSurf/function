# Function: <code>finish_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void finish_wait(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3520)
Location: kernel/sched/wait.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/cpu.c:cpu_hotplug_begin
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/wait.c:__wait_on_bit
  - kernel/sched/wait.c:__wait_on_bit_lock
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:hib_wait_io
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:bdi_unregister
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:inode_dio_wait
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/notify/mark.c:fsnotify_mark_destroy
  - fs/aio.c:read_events
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:__break_lease
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:mb_cache_entry_get
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq-tag.c:bt_get
  - block/blk-mq-tag.c:bt_get
  - block/bsg.c:bsg_get_done_cmd
  - block/bsg.c:bsg_get_done_cmd
  - block/bsg.c:bsg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_req
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810c3520-ffffffff810c3584: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void finish_wait(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6ea0)
Location: kernel/sched/wait.c:232
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_begin
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait.c:__wait_on_bit_lock
  - kernel/sched/wait.c:__wait_on_bit
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
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_unregister
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/aio.c:read_events
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq-tag.c:bt_get
  - block/blk-mq-tag.c:bt_get
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/bsg.c:bsg_get_done_cmd
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu_ida.c:percpu_ida_alloc
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
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
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_make_request
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_req
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810c6ea0-ffffffff810c6f04: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void finish_wait(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cceb0)
Location: kernel/sched/wait.c:253
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_begin
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait.c:__wait_on_bit_lock
  - kernel/sched/wait.c:__wait_on_bit_lock
  - kernel/sched/wait.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_unregister
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/aio.c:read_events
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_queue_enter
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-wbt.c:wbt_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu_ida.c:percpu_ida_alloc
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
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_make_request
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_req
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810cceb0-ffffffff810ccf15: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9780)
Location: kernel/sched/wait.c:294
Inline: False
Direct callers:
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-wbt.c:wbt_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu_ida.c:percpu_ida_alloc
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_make_request
  - drivers/md/bitmap.c:bitmap_wait_behind_writes
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_areq
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810c9780-ffffffff810c97ea: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0fc0)
Location: kernel/sched/wait.c:349
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-wbt.c:wbt_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu_ida.c:percpu_ida_alloc
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_start_areq
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810d0fc0-ffffffff810d102a: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9660)
Location: kernel/sched/wait.c:345
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:__get_unlocked_mapping_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-wbt.c:wbt_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu_ida.c:percpu_ida_alloc
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810d9660-ffffffff810d96c5: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e3160)
Location: kernel/sched/wait.c:347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810e3160-ffffffff810e31c5: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9c10)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810e9c10-ffffffff810e9c78: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f55e0)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810f55e0-ffffffff810f5648: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fed20)
Location: kernel/sched/wait.c:361
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:resolve_symbol_wait
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:xol_take_insn_slot
  - mm/filemap.c:wait_on_page_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/quota/dquot.c:invalidate_dquots
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810fed20-ffffffff810fed88: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd620)
Location: kernel/sched/wait.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:resolve_symbol_wait
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:xol_take_insn_slot
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:__io_uring_task_cancel
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dax.c:alloc_dax_mapping_reclaim
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
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
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810fd620-ffffffff810fd68b: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffa00)
Location: kernel/sched/wait.c:381
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/softirq.c:tasklet_kill
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:simplify_symbols
  - kernel/module.c:simplify_symbols
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:pre_ssout
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810ffa00-ffffffff810ffa6b: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bad0)
Location: kernel/sched/wait.c:389
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/softirq.c:tasklet_kill
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:simplify_symbols
  - kernel/module.c:simplify_symbols
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:pre_ssout
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/bdev.c:bd_prepare_to_claim
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
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
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff8111bad0-ffffffff8111bb3a: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113be90)
Location: kernel/sched/wait.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/softirq.c:tasklet_kill
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit
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
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:pre_ssout
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/bdev.c:bd_prepare_to_claim
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff8113be90-ffffffff8113bf09: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811669b0)
Location: kernel/sched/wait.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit
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
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:pre_ssout
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/bdev.c:bd_prepare_to_claim
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff811669b0-ffffffff81166a29: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176e20)
Location: kernel/sched/wait.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit
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
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:pre_ssout
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/bdev.c:bd_prepare_to_claim
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff81176e20-ffffffff81176e99: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184de0)
Location: kernel/sched/wait.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit_lock
  - kernel/sched/build_utility.c:__wait_on_bit
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
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/seccomp.c:recv_wait_event
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:pre_ssout
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/shmem.c:shmem_falloc_wait
  - mm/shmem.c:shmem_falloc_wait
  - mm/shmem.c:shmem_evict_inode
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - fs/super.c:grab_super
  - fs/super.c:super_lock
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/aio.c:read_events
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:__break_lease
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:invalidate_dquots
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_fc_begin_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/bdev.c:bd_prepare_to_claim
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
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
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_thread
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/gpu/drm/drm_file.c:drm_read
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank
  - drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_flush
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_file_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff81184de0-ffffffff81184e59: finish_wait (STB_GLOBAL)
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
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158c50)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:wait_on_page_bit_common
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__arm64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffff800010158c50-ffff800010158d2c: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5d1c)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:do_io_getevents
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
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
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/host/sdhci.c:sdhci_send_tuning
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_wait_for_idle
  - sound/core/init.c:snd_card_disconnect_sync
  - sound/core/compress_offload.c:snd_compress_wait_for_drain
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
c03a5d1c-c03a5d9c: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acda0)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtasd.c:rtas_log_read
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_wait_response_interruptible
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_wait_response
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:wb_wait_for_completion
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
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
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/hvc/hvsi.c:wait_for_state
  - drivers/tty/hvc/hvsi.c:wait_for_state
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_send
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_recv
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_wait_writes
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
c0000000001acda0-c0000000001ace50: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000febd4)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:synchronize_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffe0000febd4-ffffffe0000fec3a: finish_wait (STB_GLOBAL)
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
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee9e0)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:nvme_wait_reset
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810ee9e0-ffffffff810eea48: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810dea70)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler
  - drivers/scsi/storvsc_drv.c:storvsc_dev_remove
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:nvme_wait_reset
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810dea70-ffffffff810dead8: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebb10)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810ebb10-ffffffff810ebb78: finish_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void finish_wait(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6b70)
Location: kernel/sched/wait.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - kernel/sched/wait_bit.c:__wait_on_bit
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
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/audit.c:kauditd_thread
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/mempool.c:mempool_alloc
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_evict_inode
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:pipe_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/file.c:expand_files
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/aio.c:read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_disable
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:wait_transaction_locked
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
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
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - block/blk-core.c:blk_queue_enter
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/sbitmap.c:sbitmap_finish_wait
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
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
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
  - drivers/md/md.c:md_handle_request
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/garbage.c:wait_for_unix_gc
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff810f6b70-ffffffff810f6bd8: finish_wait (STB_GLOBAL)
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
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
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
