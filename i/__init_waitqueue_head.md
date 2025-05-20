# Function: <code>__init_waitqueue_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __init_waitqueue_head(wait_queue_head_t *q, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c31e0)
Location: kernel/sched/wait.c:14
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_notify
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_process
  - kernel/fork.c:_do_fork
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:flush_kthread_worker
  - kernel/kthread.c:flush_kthread_work
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_create_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/backing-dev.c:bdi_init
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_alloc
  - fs/timerfd.c:SyS_timerfd_create
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:exit_aio
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_destroy
  - fs/locks.c:locks_alloc_lock
  - fs/locks.c:locks_init_lock
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dqget
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_init_rl
  - block/blk-core.c:blk_init_rl
  - block/blk-mq-tag.c:bt_alloc
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:make_acpi_ec
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/misc/bmp085.c:bmp085_update_raw_temperature
  - drivers/misc/bmp085.c:show_pressure
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/core.c:__nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_device_register
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/mmc/core/core.c:__mmc_start_req
  - drivers/mmc/core/core.c:mmc_init_context_info
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_clone_lock
  - net/core/flow.c:flow_cache_flush
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810c31e0-ffffffff810c31fd: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __init_waitqueue_head(wait_queue_head_t *q, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6b70)
Location: kernel/sched/wait.c:14
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/kthread.c:flush_kthread_worker
  - kernel/kthread.c:flush_kthread_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mempool.c:mempool_create_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/backing-dev.c:bdi_init
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_alloc
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:SyS_timerfd_create
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:exit_aio
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dqget
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_larval_alloc
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_init_rl
  - block/blk-core.c:blk_init_rl
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_device_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_init_context_info
  - drivers/mmc/core/core.c:__mmc_start_req
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/flow.c:flow_cache_flush
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810c6b70-ffffffff810c6b8d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __init_waitqueue_head(wait_queue_head_t *q, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccb50)
Location: kernel/sched/wait.c:14
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:sched_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_create_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/backing-dev.c:bdi_init
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_alloc
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:SyS_timerfd_create
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dqget
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_larval_alloc
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_init_rl
  - block/blk-core.c:blk_init_rl
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_device_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_init_context_info
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/flow.c:flow_cache_flush
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810ccb50-ffffffff810ccb6d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9410)
Location: kernel/sched/wait.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_create_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_alloc
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:SyS_timerfd_create
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dqget
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_larval_alloc
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_init_rl
  - block/blk-core.c:blk_init_rl
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_init_context_info
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/core/flow.c:flow_cache_flush
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810c9410-ffffffff810c942d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0b00)
Location: kernel/sched/wait.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_create_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/hmm.c:hmm_devmem_add
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/eventpoll.c:ep_alloc
  - fs/eventpoll.c:ep_alloc
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:SyS_timerfd_create
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/blk-core.c:blk_alloc_queue_node
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_init_context_info
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810d0b00-ffffffff810d0b1d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9040)
Location: kernel/sched/wait.c:8
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/hmm.c:hmm_devmem_add
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_init
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_alloc_inode
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - block/blk-core.c:blk_alloc_queue_node
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - lib/percpu_ida.c:__percpu_ida_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810d9040-ffffffff810d905d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2b40)
Location: kernel/sched/wait.c:8
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/hmm.c:hmm_devmem_add
  - fs/super.c:sget_userns
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:alloc_vfsmnt
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810e2b40-ffffffff810e2b5d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9750)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:devm_memremap_pages
  - mm/hmm.c:hmm_mirror_register
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:__fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - drivers/soundwire/bus.c:sdw_transfer_defer
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810e9750-ffffffff810e976d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5120)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810f5120-ffffffff810f513d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fe840)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:init_listener
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_get_open_node
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/keyslot-manager.c:blk_ksm_init
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810fe840-ffffffff810fe85d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd210)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_get_open_node
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/keyslot-manager.c:blk_ksm_init
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810fd210-ffffffff810fd22d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff5d0)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:__fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/keyslot-manager.c:blk_ksm_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810ff5d0-ffffffff810ff5ed: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b6c0)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/sched/psi.c:group_init
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:__fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:locks_remove_flock
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/keyslot-manager.c:blk_ksm_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8111b6c0-ffffffff8111b6dd: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114c89a)
Location: kernel/sched/wait.c:8
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:wait_bit_init
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8113b910-ffffffff8113b935: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117b5da)
Location: kernel/sched/wait.c:8
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:wait_bit_init
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/vmscan.c:lru_gen_init_lruvec
  - mm/backing-dev.c:bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_init_lock
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/decompressor_multi.c:squashfs_decompressor_create
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/notify.c:aa_new_listener
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff81166360-ffffffff81166385: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c2a8)
Location: kernel/sched/wait.c:8
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:wait_bit_init
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_init
  - mm/mm_init.c:pgdat_init_internals
  - mm/mm_init.c:pgdat_init_internals
  - mm/mm_init.c:pgdat_init_internals
  - mm/mm_init.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_init_lock
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/decompressor_multi.c:squashfs_decompressor_create
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/notify.c:aa_new_listener
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff811767d0-ffffffff811767f5: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119ac37)
Location: kernel/sched/wait.c:8
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:wait_bit_init
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:copy_signal
  - kernel/pid.c:alloc_pid
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_init
  - mm/mm_init.c:pgdat_init_internals
  - mm/mm_init.c:pgdat_init_internals
  - mm/mm_init.c:pgdat_init_internals
  - mm/mm_init.c:pgdat_init_internals
  - mm/mmu_notifier.c:__mmu_notifier_register
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:ioctx_alloc
  - fs/dax.c:init_dax_wait_table
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_init_lock
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/decompressor_multi.c:squashfs_decompressor_create
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_bucket_alloc
  - ipc/mqueue.c:mqueue_get_inode
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/notify.c:aa_new_listener
  - block/blk-core.c:blk_alloc_queue
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-crypto-profile.c:blk_crypto_profile_init
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_worker_init
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:rdev_init_serial
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/mmc/core/host.c:mmc_alloc_host
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/rfkill/core.c:rfkill_fop_open
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81184a50-ffffffff81184a75: __init_waitqueue_head (STB_GLOBAL)
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
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010157e18)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_create_worker_thread
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffff800010157e18-ffff800010157e4c: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5744)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/mach-vexpress/spc.c:spc_set_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/zsmalloc.c:zs_create_pool
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - sound/core/init.c:snd_card_free
  - sound/core/init.c:snd_card_new
  - sound/core/init.c:snd_card_new
  - sound/core/pcm.c:snd_pcm_attach_substream
  - sound/core/pcm.c:snd_pcm_attach_substream
  - sound/core/pcm.c:_snd_pcm_new
  - sound/core/compress_offload.c:snd_compr_open
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
c03a5744-c03a5770: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ac5e0)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
c0000000001ac5e0-c0000000001ac600: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe6e0)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/zsmalloc.c:zs_create_pool
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffe0000fe6e0-ffffffe0000fe70c: __init_waitqueue_head (STB_GLOBAL)
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
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee520)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810ee520-ffffffff810ee53d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de5b0)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/hv/connection.c:vmbus_negotiate_version
  - drivers/hv/channel.c:vmbus_teardown_gpadl
  - drivers/hv/channel.c:vmbus_establish_gpadl
  - drivers/hv/channel.c:__vmbus_open
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810de5b0-ffffffff810de5cd: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb650)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810eb650-ffffffff810eb66d: __init_waitqueue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __init_waitqueue_head(struct wait_queue_head *wq_head, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f66b0)
Location: kernel/sched/wait.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
  - kernel/fork.c:sighand_ctor
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/sched/wait_bit.c:wait_bit_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/smp.c:smp_call_on_cpu
  - kernel/acct.c:acct_on
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup.c:init_cgroup_housekeeping
  - kernel/stop_machine.c:cpu_stop_init_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:__relay_reset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/uprobes.c:__create_xol_area
  - mm/filemap.c:pagecache_init
  - mm/mempool.c:mempool_init_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/page_alloc.c:pgdat_init_internals
  - mm/zsmalloc.c:zs_create_pool
  - mm/memremap.c:memremap_pages
  - mm/hmm.c:hmm_alloc_notifier
  - fs/super.c:alloc_super
  - fs/pipe.c:alloc_pipe_info
  - fs/file.c:dup_fd
  - fs/namespace.c:alloc_mnt_ns
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:do_epoll_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/userfaultfd.c:init_once_userfaultfd_ctx
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/dax.c:init_dax_wait_table
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/locks.c:locks_init_lock
  - fs/locks.c:locks_alloc_lock
  - fs/coredump.c:do_coredump
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:journal_init_common
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dev.c:fuse_request_alloc
  - fs/fuse/file.c:fuse_init_file_inode
  - fs/fuse/file.c:fuse_file_alloc
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/debugfs/file.c:debugfs_file_get
  - ipc/mqueue.c:mqueue_get_inode
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_larval_alloc
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/acpi_dbg.c:acpi_aml_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/tty_port.c:tty_port_init
  - drivers/tty/vt/vt.c:vc_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serdev/core.c:serdev_device_alloc
  - drivers/char/virtio_console.c:add_port
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_open
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
  - drivers/mfd/da9052-core.c:da9052_device_init
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/dma-buf/sync_file.c:sync_file_alloc
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/libps2.c:ps2_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-api.c:cec_open
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
  - drivers/pps/kapi.c:pps_register_source
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-io.c:sync_io
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/host.c:mmc_alloc_host
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
  - net/socket.c:sock_alloc_inode
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
  - net/netlink/af_netlink.c:__netlink_create
  - net/ipv4/inet_fragment.c:inet_frags_init
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff810f66b0-ffffffff810f66cd: __init_waitqueue_head (STB_GLOBAL)
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
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
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
