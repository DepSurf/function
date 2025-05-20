# Function: <code>kthread_create_on_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0270)
Location: kernel/kthread.c:270
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - fs/notify/mark.c:fsnotify_mark_init
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/md.c:md_register_thread
  - drivers/md/dm.c:init_rq_based_worker_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810a0270-ffffffff810a0443: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3960)
Location: kernel/kthread.c:270
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/md.c:md_register_thread
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810a3960-ffffffff810a3b3f: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8c10)
Location: kernel/kthread.c:357
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/md.c:md_register_thread
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810a8c10-ffffffff810a8c70: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a59f0)
Location: kernel/kthread.c:361
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/md.c:md_register_thread
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff810a59f0-ffffffff810a5a52: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac100)
Location: kernel/kthread.c:368
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/md.c:md_register_thread
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff810ac100-ffffffff810ac162: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3390)
Location: kernel/kthread.c:382
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/md/md.c:md_register_thread
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810b3390-ffffffff810b33f0: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc4d0)
Location: kernel/kthread.c:382
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810bc4d0-ffffffff810bc530: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1c70)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810c1c70-ffffffff810c1cd0: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c81c0)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810c81c0-ffffffff810c8220: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0dc0)
Location: kernel/kthread.c:427
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_sq_offload_start
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_start_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/char/hw_random/core.c:hwrng_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_init_queue
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
```
**Symbols:**

```
ffffffff810d0dc0-ffffffff810d0e20: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb870)
Location: kernel/kthread.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_sq_offload_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_start_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/char/hw_random/core.c:hwrng_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
```
**Symbols:**

```
ffffffff810cb870-ffffffff810cb8d0: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd0f0)
Location: kernel/kthread.c:456
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff810cd0f0-ffffffff810cd150: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e02c0)
Location: kernel/kthread.c:456
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff810e02c0-ffffffff810e0320: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9f20)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff810f9f20-ffffffff810f9f9a: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111cc80)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff8111cc80-ffffffff8111ccfa: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129da0)
Location: kernel/kthread.c:516
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff81129da0-ffffffff81129e1a: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134410)
Location: kernel/kthread.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_probe
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff81134410-ffffffff8113448a: kthread_create_on_node (STB_GLOBAL)
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
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127d88)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_create_worker_thread
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffff800010127d88-ffff800010127e34: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b110)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
c037b110-c037b178: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171a10)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_event.c:eeh_event_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
c000000000171a10-c000000000171a54: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df778)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffe0000df778-ffffffe0000df7cc: kthread_create_on_node (STB_GLOBAL)
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
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2540)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810c2540-ffffffff810c25a0: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0d90)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_one_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_one_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
```
**Symbols:**

```
ffffffff810b0d90-ffffffff810b0df0: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1a90)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810c1a90-ffffffff810c1af0: kthread_create_on_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9ec0)
Location: kernel/kthread.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/workqueue.c:create_worker
  - kernel/kthread.c:kthread_create_on_cpu
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/md/md.c:md_register_thread
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
**Symbols:**

```
ffffffff810c9ec0-ffffffff810c9f20: kthread_create_on_node (STB_GLOBAL)
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
