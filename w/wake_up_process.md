# Function: <code>wake_up_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abd50)
Location: kernel/sched/core.c:2065
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:do_exit
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:raise_softirq
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/pid.c:free_pid
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_create_on_node
  - kernel/kthread.c:kthread_stop
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock
  - kernel/locking/mutex.c:__mutex_unlock_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rwsem-xadd.c:__rwsem_do_wake
  - kernel/locking/rwsem-xadd.c:__rwsem_do_wake
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/memory_hotplug.c:put_online_mems
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/notify/mark.c:fsnotify_mark_init
  - fs/coredump.c:do_coredump
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/sem.c:wake_up_sem_queue_do
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:do_md_stop
  - drivers/md/dm.c:init_rq_based_worker_thread
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810abd50-ffffffff810abd67: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aea2e)
Location: kernel/sched/core.c:2154
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/pid.c:free_pid
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_create_on_node
  - kernel/sched/swait.c:swake_up_locked
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:__ww_mutex_lock
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/memory_hotplug.c:put_online_mems
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:wake_up_sem_queue_do
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810ae9e0-ffffffff810ae9f7: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4b6e)
Location: kernel/sched/core.c:2164
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/swait.c:swake_up_locked
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/memory_hotplug.c:put_online_mems
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810b4b20-ffffffff810b4b37: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0c5e)
Location: kernel/sched/core.c:2131
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_unbind_fn
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_wakeup_for_backoff
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - lib/klist.c:klist_dec_and_del
```
**Symbols:**

```
ffffffff810b0c10-ffffffff810b0c27: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b80ae)
Location: kernel/sched/core.c:2150
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_wakeup_for_backoff
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810b8060-ffffffff810b8077: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfbca)
Location: kernel/sched/core.c:2146
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_wakeup_for_backoff
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/dm-rq.c:dm_old_init_request_queue
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810bfb60-ffffffff810bfb77: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8f4a)
Location: kernel/sched/core.c:2140
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810c8ee0-ffffffff810c8ef7: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0ae8)
Location: kernel/sched/core.c:2546
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810d0a90-ffffffff810d0aa7: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810daa98)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810daa40-ffffffff810daa57: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3916)
Location: kernel/sched/core.c:2822
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/exit.c:exit_notify
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:rebind_workers
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_sq_offload_start
  - fs/io_uring.c:__io_async_wake
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - fs/coredump.c:coredump_finish
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - lib/klist.c:klist_release
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_start_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/char/hw_random/core.c:hwrng_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_init_queue
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff810e38a0-ffffffff810e38b7: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1386)
Location: kernel/sched/core.c:3531
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/exit.c:exit_notify
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:rebind_workers
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_disable_sqo_submit
  - fs/io_uring.c:io_sq_thread_stop
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_req_task_work_add
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:create_io_worker
  - fs/coredump.c:coredump_finish
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - lib/klist.c:klist_release
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_start_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/char/hw_random/core.c:hwrng_init
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff810e1310-ffffffff810e1327: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e31a6)
Location: kernel/sched/core.c:3552
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/exit.c:exit_notify
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_sq_thread_finish
  - fs/io_uring.c:io_sq_thread_park
  - fs/io_uring.c:io_req_task_work_add
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - lib/klist.c:klist_release
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff810e3130-ffffffff810e3147: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f9c43)
Location: kernel/sched/core.c:4167
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:exit_notify
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_sq_thread_park
  - fs/io_uring.c:io_req_task_work_add
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:blkdev_bio_end_io_simple
  - lib/klist.c:klist_release
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff810f9be0-ffffffff810f9bf7: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811161c3)
Location: kernel/sched/core.c:4286
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_test
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/fops.c:blkdev_bio_end_io
  - io_uring/io_uring.c:io_sq_thread_park
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - lib/klist.c:klist_release
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:napi_kthread_create
```
**Symbols:**

```
ffffffff81116150-ffffffff81116171: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d673)
Location: kernel/sched/core.c:4400
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/fops.c:blkdev_bio_end_io
  - io_uring/sqpoll.c:io_sq_thread_stop
  - io_uring/sqpoll.c:io_sq_thread_park
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:napi_kthread_create
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff8113d5f0-ffffffff8113d611: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811511f3)
Location: kernel/sched/core.c:4477
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_cull_fn
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_tick
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/vhost_task.c:vhost_task_stop
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/trace/trace_osnoise.c:start_kthread
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/fops.c:blkdev_bio_end_io
  - io_uring/sqpoll.c:io_sq_thread_stop
  - io_uring/sqpoll.c:io_sq_thread_park
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:napi_kthread_create
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff81151170-ffffffff81151191: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115d083)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:exit_notify
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:__exit_signal
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_cull_fn
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:kick_pool
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/vhost_task.c:vhost_task_stop
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/trace/trace_osnoise.c:start_kthread
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/aio.c:aio_complete
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/fops.c:blkdev_bio_end_io
  - io_uring/sqpoll.c:io_sq_thread_stop
  - io_uring/sqpoll.c:io_sq_thread_park
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - lib/closure.c:closure_sync_fn
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_intr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/gpu/drm/drm_syncobj.c:syncobj_wait_fence_func
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:stop_sync_thread
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:napi_kthread_create
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff8115d000-ffffffff8115d021: wake_up_process (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a5e0)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_create_worker_thread
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:wakeup_softirqd
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffff80001013a550-ffff80001013a584: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a17c)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:wakeup_softirqd
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/semaphore.c:__up
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
c038a0f4-c038a118: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000187ed0)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/powerpc/kernel/eeh_event.c:eeh_event_init
  - arch/powerpc/platforms/powernv/opal.c:opal_init
  - arch/powerpc/platforms/powernv/opal.c:opal_handle_hmi_exception
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:wakeup_softirqd
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/semaphore.c:__up
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
c000000000187e40-c000000000187e5c: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e9f88)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:wakeup_softirqd
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/semaphore.c:__up
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffe0000e9f26-ffffffe0000e9f54: wake_up_process (STB_GLOBAL)
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
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4f48)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810d4ef0-ffffffff810d4f07: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3598)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_spawn_one_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_one_nocb_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810c3540-ffffffff810c3557: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1d88)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810d1d30-ffffffff810d1d47: wake_up_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int wake_up_process(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc7a8)
Location: kernel/sched/core.c:2666
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_q
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - kernel/cpu.c:__cpuhp_kick_ap
  - kernel/exit.c:do_exit
  - kernel/exit.c:rcuwait_wake_up
  - kernel/exit.c:release_task
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:pwq_adjust_max_active
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:wq_worker_sleeping
  - kernel/pid.c:free_pid
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/freezer.c:__thaw_task
  - kernel/time/timer.c:process_timeout
  - kernel/time/hrtimer.c:hrtimer_wakeup
  - kernel/time/clocksource.c:clocksource_watchdog_work
  - kernel/time/alarmtimer.c:alarmtimer_nsleep_wakeup
  - kernel/cgroup/freezer.c:cgroup_freeze_task
  - kernel/audit.c:audit_init
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/hung_task.c:hung_task_init
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - mm/oom_kill.c:oom_init
  - mm/vmscan.c:kswapd_run
  - mm/compaction.c:kcompactd_run
  - mm/page_io.c:end_swap_bio_read
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:blkdev_bio_end_io_simple
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
  - fs/io_uring.c:io_uring_create
  - fs/coredump.c:do_coredump
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/super.c:ext4_register_li_request
  - fs/jbd2/journal.c:commit_timeout
  - fs/ecryptfs/kthread.c:ecryptfs_init_kthread
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/acpi/acpi_dbg.c:acpi_aml_create_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_unthrottle
  - drivers/base/devtmpfs.c:devtmpfs_init
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/spi/spi.c:spi_register_controller
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - lib/klist.c:klist_release
```
**Symbols:**

```
ffffffff810dc750-ffffffff810dc767: wake_up_process (STB_GLOBAL)
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
