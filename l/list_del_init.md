# Function: <code>list_del_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81060642)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff8108267f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108b81c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8108ced8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff8109717c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:rescuer_thread
```
```
In kernel/kthread.c (ffffffff810a0ae4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810a2f47)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810b4a1c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c0561)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810c3553)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:abort_exclusive_wait
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f22ba)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clocksource.c (ffffffff810f81ac)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/clockevents.c (ffffffff810fbbf3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8110062e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:do_futex
```
```
In kernel/cgroup.c (ffffffff811150a4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:css_set_move_task
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In kernel/stop_machine.c (ffffffff81120273)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8112ab56)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_kill_trees
```
```
In kernel/kprobes.c (ffffffff8112d751)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81f83502)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811469c8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff8115cc1a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81f855ed)
Location: include/linux/list.h:143
Inline: True
```
```
In kernel/events/core.c (ffffffff811799d5)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:orphans_remove_work
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
```
```
In kernel/padata.c (ffffffff81189a82)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/padata.c:padata_parallel_worker
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
```
```
In mm/shmem.c (ffffffff811aa12c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unuse
```
```
In mm/list_lru.c (ffffffff811b8e85)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff811d5e8e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff811dfa1b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/memcontrol.c (ffffffff811f9a57)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:mem_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff812052e9)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/super.c (ffffffff8120ed85)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/char_dev.c (ffffffff81210876)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff81223c65)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:__d_move
```
```
In fs/inode.c (ffffffff81227d0f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/inode.c:evict
  - fs/inode.c:dispose_list
```
```
In fs/namespace.c (ffffffff8122bede)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/fs-writeback.c (ffffffff81236633)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/pnode.c (ffffffff8123ceb7)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8124277e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/buffer.c:__remove_assoc_queue
  - fs/buffer.c:__bforget
```
```
In fs/block_dev.c (ffffffff812471ac)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
  - fs/block_dev.c:bdev_evict_inode
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bd_forget
```
```
In fs/notify/notification.c (ffffffff8124fb88)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_event
```
```
In fs/notify/mark.c (ffffffff8125034f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81252daf)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff812546c6)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/userfaultfd.c (ffffffff81259f29)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/aio.c (ffffffff8125c1b3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff8125f102)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_dispose_list
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_unlink_lock_ctx
```
```
In fs/mbcache.c (ffffffff8126ca70)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/quota/dquot.c (ffffffff812714c0)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/proc/inode.c (ffffffff8127984a)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8129fa2c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/namei.c (ffffffff812a8591)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
```
```
In fs/ext4/super.c (ffffffff812ac1b4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/mballoc.c (ffffffff812ce043)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/extents_status.c (ffffffff812daced)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/jbd2/commit.c (ffffffff812eabf1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff812f550d)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff8130faac)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/fuse/file.c (ffffffff813199fd)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff8132fb99)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff813457dc)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:selinux_inode_free_security
```
```
In security/tomoyo/common.c (ffffffff81367cd3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/policy.c (ffffffff8137f549)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/policy_unpack.c (ffffffff81382b82)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff8139d08f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_alg
  - crypto/algapi.c:crypto_unregister_template
```
```
In block/elevator.c (ffffffff813b3629)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister
```
```
In block/blk-core.c (ffffffff813baf93)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-tag.c (ffffffff813bbd92)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-flush.c (ffffffff813bd4e2)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff813becb9)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff813c1d14)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-timeout.c (ffffffff813c1f75)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_rq_timed_out_timer
```
```
In block/blk-mq.c (ffffffff813c3a51)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_free_queue
```
```
In block/genhd.c (ffffffff813cb843)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff813d849b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff813d96be)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/noop-iosched.c (ffffffff813dc395)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/noop-iosched.c:noop_merged_requests
  - block/noop-iosched.c:noop_dispatch
```
```
In block/deadline-iosched.c (ffffffff813dca0f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff813def34)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_remove_request
```
```
In lib/kobject.c (ffffffff813eb81a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff813edf24)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In lib/dynamic_debug.c (ffffffff81413d2e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_remove_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
```
In drivers/pwm/core.c (ffffffff8142c5c5)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff8147eebd)
Location: include/linux/list.h:143
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8148340e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff814e1007)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff815123e1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/base/core.c (ffffffff8154933d)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff81549e6e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff8154b1c5)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/dd.c:driver_deferred_probe_del
```
```
In drivers/base/class.c (ffffffff8154cec2)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff8154f59a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff81559b7e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/firmware_class.c (ffffffff8155e7c6)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff81577f37)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
```
```
In drivers/nvdimm/core.c (ffffffff81596c50)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_bus_unregister
```
```
In drivers/dma-buf/fence.c (ffffffff815a3739)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_remove_callback
  - drivers/dma-buf/fence.c:fence_signal_locked
```
```
In drivers/scsi/scsi.c (ffffffff815a7545)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_get_command
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi.c:scsi_destroy_command_freelist
```
```
In drivers/scsi/scsi_error.c (ffffffff815ac333)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad47b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b1a84)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/spi/spi.c (ffffffff815e7b37)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff815ef72d)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff8160c0a9)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/devio.c (ffffffff816196aa)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_getcompleted
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81626bd7)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162dcd8)
Location: include/linux/list.h:143
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81639358)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81644de1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8164bd8c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816559fe)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81657781)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:finish_td
```
```
In drivers/input/serio/serio.c (ffffffff816635b9)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/input.c (ffffffff81667fce)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff8166c3f8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff8168d858)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff8169fccf)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff816ce8eb)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81710e3f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81714bcc)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff81730819)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_forget_dev
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0d03)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
```
```
In net/xfrm/xfrm_state.c (ffffffff817b84b0)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff817c2254)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff817ce6f5)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff817dbccf)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff8181205b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81060448)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff81086fc1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108e81c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81090145)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff8109c5ef)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810a41a0)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810a664a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810c0efa)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810c3ea0)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810c6f52)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/wait.c:abort_exclusive_wait
  - kernel/sched/wait.c:finish_wait
```
```
In kernel/sched/swait.c (ffffffff810c7523)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_locked
```
```
In kernel/rcu/update.c (ffffffff810e9594)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810facc3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clocksource.c (ffffffff810ff40c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/clockevents.c (ffffffff81102f26)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8110a062)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup.c (ffffffff8111c97c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:css_set_move_task
```
```
In kernel/stop_machine.c (ffffffff811281d4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff811349bb)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8113668b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81facaa1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f216)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811675da)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81faebfd)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/events/core.c (ffffffff81192e61)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff8119c24b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff811c3f3a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811cab9c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/list_lru.c (ffffffff811d3125)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff811f3f4e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff811fe0c2)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/huge_memory.c (ffffffff81218038)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8121ef82)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff8122a5c4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff812357b5)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/char_dev.c (ffffffff812372fa)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8124ccc0)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff81250588)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812587d4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff81264699)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff812656c7)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8126b58e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffff812705cb)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff812782de)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/notify/mark.c (ffffffff8127939f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_list
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127b609)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8127e68e)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81282939)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/aio.c (ffffffff812852aa)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff8128abc8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff81298a3c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
```
```
In fs/quota/dquot.c (ffffffff8129fe4a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/proc/inode.c (ffffffff812a65ba)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff812ce2e3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/namei.c (ffffffff812d7684)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/super.c (ffffffff812e0920)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/mballoc.c (ffffffff812fdd22)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/extents_status.c (ffffffff8130a76d)
Location: include/linux/list.h:143
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81318580)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81328f31)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff813437e1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8134e4ef)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff813648e9)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff8137c133)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff8139ddc3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/policy.c (ffffffff813ba8d6)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813bcda8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff813dacc9)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff813f7329)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister
```
```
In block/blk-core.c (ffffffff813ff48d)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_dequeue_request
```
```
In block/blk-tag.c (ffffffff813ffba4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-flush.c (ffffffff81401415)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff81402c89)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff81405cb8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-timeout.c (ffffffff8140615c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff8140ab86)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff8140fb03)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff8141e1dd)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff8141f4e2)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/noop-iosched.c (ffffffff814220ce)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/noop-iosched.c:noop_dispatch
  - block/noop-iosched.c:noop_merged_requests
```
```
In block/deadline-iosched.c (ffffffff81422640)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff81425484)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_remove_request
```
```
In lib/kobject.c (ffffffff81431c0a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81434057)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In lib/dynamic_debug.c (ffffffff81fca202)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In drivers/pwm/core.c (ffffffff81477594)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff814cd762)
Location: include/linux/list.h:143
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814d1eae)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff8153220c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff815653a1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff8159afc0)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff8159babe)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff8159d4a5)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff8159ecb2)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff815a1516)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff815ada1a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff815b0d71)
Location: include/linux/list.h:143
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815b314f)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff815cdb32)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/nvdimm/bus.c (ffffffff815ecc49)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/fence.c (ffffffff815fa839)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_remove_callback
  - drivers/dma-buf/fence.c:fence_signal_locked
```
```
In drivers/scsi/scsi.c (ffffffff815ff727)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_destroy_command_freelist
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi.c:scsi_get_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8160424c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff81607d8b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff81609e73)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8163ed7a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81646205)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff8164e2b4)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff8166d3eb)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff8167a1de)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81685160)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d8d1)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169d443)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a6846)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff816af4df)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6404)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816ba44a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/input/serio/serio.c (ffffffff816c42ad)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff816c7d3a)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff816cc458)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff816eeeb8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff817010db)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8173194b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff8177876c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81781dd6)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/link_watch.c (ffffffff8179b10c)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181ddd8)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff818258fb)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8182f45b)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8183bdd3)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff81849c58)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff81884f38)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188f452)
Location: include/linux/list.h:143
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015749)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810634e8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff8108bf2d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81093793)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810950c5)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810a1780)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810a8e30)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810ac2aa)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810c6ee6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810c9f08)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810ccee4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810cd3f4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_locked
```
```
In kernel/rcu/update.c (ffffffff810f045b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/time/clocksource.c (ffffffff8110227c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81108643)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clockevents.c (ffffffff8110a616)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff81111852)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup.c (ffffffff81124cac)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:css_set_move_task
```
```
In kernel/stop_machine.c (ffffffff81131dd4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8113e73b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8114040b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81fe8dbf)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811593a6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff81172a2a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81feb224)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/events/core.c (ffffffff811a2641)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_free_event
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff811ababb)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff811cdc52)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811dacbc)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/list_lru.c (ffffffff811e2fe5)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff81204a7e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/hugetlb.c (ffffffff8120eb92)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/huge_memory.c (ffffffff8122a5d8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81231492)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff8123cb14)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81248365)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/char_dev.c (ffffffff81249faa)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8125fcb0)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff81263628)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8126bc83)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff81277ad9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff81278bb8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8127e6ce)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffff81283d9b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff8128bfdd)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/notify/mark.c (ffffffff8128cf5f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_list
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128f1b6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8129221e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff8129645d)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/aio.c (ffffffff812994ba)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff8129f958)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff812ad4ba)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
```
```
In fs/quota/dquot.c (ffffffff812b5339)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/ext4/page-io.c (ffffffff812e40d3)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/namei.c (ffffffff812ed274)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/super.c (ffffffff812f6460)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/mballoc.c (ffffffff81313da2)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/extents_status.c (ffffffff8132076d)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8132e576)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff8133ec71)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff81359dec)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81363def)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff8137b109)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff81392c03)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff813b49a3)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/policy.c (ffffffff813d1c96)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813d41d7)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff813f2609)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff81410d39)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/elevator.c:elv_unregister
```
```
In block/blk-core.c (ffffffff81418ead)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_dequeue_request
```
```
In block/blk-tag.c (ffffffff81419454)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-flush.c (ffffffff8141b055)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8141c9b9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff8141ff58)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-timeout.c (ffffffff814203ec)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff814255f6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff8142ae93)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff8143979d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff8143aaa2)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/noop-iosched.c (ffffffff8143d22b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/noop-iosched.c:noop_dispatch
  - block/noop-iosched.c:noop_merged_requests
```
```
In block/deadline-iosched.c (ffffffff8143d77a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff81442bb4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_remove_request
```
```
In lib/kobject.c (ffffffff8144de7a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff814502e7)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In lib/dynamic_debug.c (ffffffff8200721d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In drivers/pwm/core.c (ffffffff814988f9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff814efb98)
Location: include/linux/list.h:156
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814f4250)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff8155e93c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff81591b01)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff815c9520)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff815ca01e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff815cb815)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff815cd272)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff815cfba6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff815dc7ea)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff815dfde7)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_class.c (ffffffff815e2506)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa5ac)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff81619a39)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81628b09)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c575)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi.c (ffffffff8162ed87)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_destroy_command_freelist
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi.c:scsi_get_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8163392c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff816376a4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff81639753)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8166fdea)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff816772f5)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff8167ffc4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff8169b0eb)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff816a7e9e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b338f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb9a1)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816cb563)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d4966)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff816dd67f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4678)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e86ba)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/input/serio/serio.c (ffffffff816f226d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff816f5d2a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff816fa408)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff81720fee)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff81732e3b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8176491b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff817a578f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817af6d6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/link_watch.c (ffffffff817c8eac)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f64a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff8185725b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81860ee7)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff8186d7d3)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff8187bae8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff818b97a8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c3845)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81013c42)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810624b7)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff8108910c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81090883)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81092154)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff8109eac9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810a5c22)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810a8e78)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810c0af9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810c3b36)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810c97b4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810c9df4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff810f0430)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/time/clocksource.c (ffffffff811043ec)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a912)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clockevents.c (ffffffff8110c5ac)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff811131cf)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81124c20)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8112ba8b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81133391)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8113fddb)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff811417a1)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff820c95b6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff8115c289)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff81175d3c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (ffffffff820cbc26)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/events/core.c (ffffffff811adbe5)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff811b2f1b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff811d67e2)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/percpu.c (ffffffff811e465e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/list_lru.c (ffffffff811ed485)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff81210129)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapoff
```
```
In mm/huge_memory.c (ffffffff8123622c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8123ccc2)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff81248824)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81253c65)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/char_dev.c (ffffffff812558aa)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8126d616)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff81270e48)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff81279465)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff81284e70)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff81286134)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8128d0ad)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffff8129147a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff81298f5d)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/notify/mark.c (ffffffff8129941f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c15f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8129f271)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff812a333d)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/aio.c (ffffffff812a716a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff812ae7c8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff812ba969)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff812c1b22)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff812de376)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff812df5c4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/configfs/symlink.c (ffffffff812e1716)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/ext4/extents_status.c (ffffffff812ef729)
Location: include/linux/list.h:156
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8131cf92)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff8131dcfb)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8132af7b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813436a5)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81353831)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff8136e5ac)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8137866f)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff8138ecd9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff813a35c1)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff813cb33d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9bb2)
Location: include/linux/list.h:156
Inline: True
```
```
In security/apparmor/policy.c (ffffffff813e4cdf)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6f96)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff813fe8f9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff8141ecd9)
Location: include/linux/list.h:156
Inline: True
```
```
In block/blk-core.c (ffffffff81426dc4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_dequeue_request
```
```
In block/blk-tag.c (ffffffff81427381)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-flush.c (ffffffff8142908d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8142a8e9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff8142df18)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-timeout.c (ffffffff8142e3a9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff814320cb)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81435d4e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffffffff8143909c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff81446f9e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff8144873e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/noop-iosched.c (ffffffff8144c65b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/noop-iosched.c:noop_dispatch
  - block/noop-iosched.c:noop_merged_requests
```
```
In block/deadline-iosched.c (ffffffff8144cbaa)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff81451dd4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_remove_request
```
```
In lib/dynamic_debug.c (ffffffff820e825c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In drivers/pwm/core.c (ffffffff814a2545)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff814fc68f)
Location: include/linux/list.h:156
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81501af4)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff815730b1)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff815a5a66)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff815de240)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff815ded68)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff815e03e5)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff815e1d6c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff815e4572)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff815f135a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff815f4c91)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_class.c (ffffffff815f7214)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff8160e81b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/nvdimm/bus.c (ffffffff8162da2d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163e6b9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641b43)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_error.c (ffffffff816485dc)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164d211)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164e2c3)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff816842ca)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff8168b916)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff816953ce)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff816afe2a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff816bd07a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816c766a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cfa7c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816dfc93)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e8dd6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff816eede7)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8647)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fc9a9)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/input/serio/serio.c (ffffffff81707b5d)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff8170b88a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff8170ff38)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff8173809e)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff8174bc1b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff81782fdb)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff817c39f2)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817cdfa6)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/link_watch.c (ffffffff817e7a5c)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81801852)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873127)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff8187adf2)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81885637)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/addrconf.c (ffffffff81892693)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff818a14f8)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff818e0194)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff818ea1aa)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff818ee29a)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff818f004b)
Location: include/linux/list.h:156
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014597)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81066607)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff8108fe64)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810976f3)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81098fe4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810a5313)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810ac1f2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810af6fe)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810c82c3)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810cb305)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810d0ff4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810d1614)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff810fa0f4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/time/clocksource.c (ffffffff8110f46c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81115a7f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clockevents.c (ffffffff811177fc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8111e769)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81130d60)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8113888b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81140041)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8114cc6b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8114e551)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff826d1df6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811692e9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff81183458)
Location: include/linux/list.h:157
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff826d4295)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/bpf/offload.c (ffffffff811b0537)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff811c1755)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
```
```
In kernel/padata.c (ffffffff811c6b6b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff811ebd02)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff812038d5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8122b8f7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapoff
```
```
In mm/huge_memory.c (ffffffff8125506f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8125c180)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812689f4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81275cea)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/char_dev.c (ffffffff81277a3a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8128ff3c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff81293778)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8129bea5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff812a78f0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff812a8bb4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff812aec4e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffff812b41ca)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff812bc2fd)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/notify/mark.c (ffffffff812bc78f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bf5ef)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff812c26e4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff812c66cd)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/aio.c (ffffffff812c9eaa)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff812d21b8)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff812de249)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff812e5881)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff81302cb6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81303f44)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/configfs/symlink.c (ffffffff81306056)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/ext4/extents_status.c (ffffffff81314229)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813415b2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff8134230b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8134f3db)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff81367cf2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81378451)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff813931cc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8139d50f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff813b4199)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff813c93c1)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff813f17cd)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff813ff742)
Location: include/linux/list.h:157
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8140bb15)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8140e19d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff81426eb9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814497b9)
Location: include/linux/list.h:157
Inline: True
```
```
In block/blk-core.c (ffffffff81451dd7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_start_request
```
```
In block/blk-tag.c (ffffffff81452981)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-flush.c (ffffffff8145417d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff81455ad9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814591a8)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-timeout.c (ffffffff814595b3)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff8145dc01)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff81465073)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff81473b81)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff814752f7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/noop-iosched.c (ffffffff81478d5b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/noop-iosched.c:noop_dispatch
  - block/noop-iosched.c:noop_merged_requests
```
```
In block/deadline-iosched.c (ffffffff814792aa)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff8147c9c4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_remove_request
```
```
In lib/dynamic_debug.c (ffffffff826f104e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In drivers/pwm/core.c (ffffffff814e1295)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff8153e4bf)
Location: include/linux/list.h:157
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81544784)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff815d87f4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff8160c366)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff81645240)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff81645d98)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff816474a5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff81648edc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff8164b842)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff8165892a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff8165cb8a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_class.c (ffffffff8165f144)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff8167709b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/nvdimm/bus.c (ffffffff816961ed)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a7539)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa920)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816b16ce)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b64cc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b7566)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff816edb2a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff816f5286)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff816fff3a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff8171ba5a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff81728a4a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81733ada)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c0c4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174c436)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817555c6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff8175b63a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8176523c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81769530)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817733dd)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81778d50)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff8177c89f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff817811b8)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff817aa8ce)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff817bdf9b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff817f939b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff8183d4b2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8184aca6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/link_watch.c (ffffffff8186299c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff818a8e4f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff818c1397)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3b37)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff818fb8d5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819067e7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81923e49)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff81965e97)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196f8f3)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff8197434a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff8197649b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810150d7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810691db)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff81093a1a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8109b01f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8109c7ea)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810ab58b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810b2b40)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810b6575)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810d0206)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810d29f5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810d9694)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810d9c24)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff81102765)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/time/clocksource.c (ffffffff8111ae61)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81122271)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clockevents.c (ffffffff81124428)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8112b3ee)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8113f453)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff811471ab)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff8114eac6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8115b6e4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff8115ce50)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff826fc5aa)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff81178269)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff81192724)
Location: include/linux/list.h:157
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff826fe9eb)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/bpf/offload.c (ffffffff811cb5ed)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff811e1acf)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff811e753b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff8120d49e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff81224595)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8124cb65)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff81278ece)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81280432)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff8128debd)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff81292f7b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_unregister
  - mm/hmm.c:hmm_release
```
```
In fs/super.c (ffffffff8129c252)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/char_dev.c (ffffffff8129ec6a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812b426c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812b97d6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812c1fde)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff812ce468)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff812cf550)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff812d725d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffff812db7fb)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff812e4f1d)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/notify/mark.c (ffffffff812e54cf)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e9833)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff812ec1f1)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff812ef809)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/aio.c (ffffffff812f3f3c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff812fe674)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff8130a489)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff81312efb)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff81330c04)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81331cd0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/configfs/symlink.c (ffffffff81334074)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/ext4/extents_status.c (ffffffff813420c7)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8136f5ee)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff81370163)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8137f148)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff81396588)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff813a6f09)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff813c38a0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff813cc8ec)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff813e4851)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff813fd903)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff81424b7a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff814305ee)
Location: include/linux/list.h:157
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8143d795)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8143fe25)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff8145a66f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff8147c29e)
Location: include/linux/list.h:157
Inline: True
```
```
In block/blk-core.c (ffffffff81485014)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_start_request
```
```
In block/blk-tag.c (ffffffff81485d6d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_end_tag
```
```
In block/blk-flush.c (ffffffff814875d7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff81488f25)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff8148c693)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-timeout.c (ffffffff8148cb03)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff814914fc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814989ae)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff814a7ff2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff814a9763)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/noop-iosched.c (ffffffff814ad4b1)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/noop-iosched.c:noop_dispatch
  - block/noop-iosched.c:noop_merged_requests
```
```
In block/deadline-iosched.c (ffffffff814addd5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
```
In block/cfq-iosched.c (ffffffff814b13a0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_remove_request
```
```
In lib/error-inject.c (ffffffff814f0242)
Location: include/linux/list.h:157
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff8271af97)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150d596)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_initial_sync
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81510a91)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff815743ef)
Location: include/linux/list.h:157
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8157a7d4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff81610c63)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff81645d46)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff8168068a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff816811ea)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff81682995)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff816844a2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff81686e42)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff816942ff)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff816988cf)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b7ae)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff816b30cb)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/nvdimm/bus.c (ffffffff816d22ec)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e3919)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6ed0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed9f8)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2689)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3872)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8172a446)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff817330ca)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff8173da39)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff8175aa06)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff8176789a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81773ec1)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c924)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178c396)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817983a6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff8179bedf)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a559f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817aa7c1)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3a13)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff817b9a29)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff817bd94e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff817c2bbe)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff817f656a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff8180623b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8184299b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81887d55)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81895086)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/link_watch.c (ffffffff818ae67c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff818fe06a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81916f4b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a447)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819526bc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8195d7b2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff8197c1e9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff819bf71d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c9005)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff819d0876)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff819d2c67)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810156d7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106ef97)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff8109bfbf)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a324f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810a8e1d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810b460b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810bbdc0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810bf805)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810d9a2f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810dc365)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810e3194)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810e37b4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff8110e16d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828ae3d9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff8112634e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d982)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clockevents.c (ffffffff8112fb28)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff81137153)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8114ae73)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff81152d2b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff8115b6a6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81168444)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81169cbd)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828b34c4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff81185629)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff8119fe64)
Location: include/linux/list.h:157
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828b5905)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811afd94)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b4ea8)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd913)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/bpf/offload.c (ffffffff811defad)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff811f1f3f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff811f845b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff8122006e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff812375e5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff81261080)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff8128d57e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81295912)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812a37ed)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812a84cb)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_unregister
  - mm/hmm.c:hmm_release
```
```
In fs/super.c (ffffffff812b1392)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/char_dev.c (ffffffff812b3c4a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812c952c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812cea26)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812d727e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff812e3768)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff812e48c0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff812ec8a0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffff812f0f8b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff812f9a3d)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/notify/mark.c (ffffffff812fa0ff)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fe323)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff81300431)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81304179)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/aio.c (ffffffff81308025)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff813140c0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff8131fc69)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff81329e8b)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff81347ff4)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813491d0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/configfs/symlink.c (ffffffff8134b3ee)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/ext4/extents_status.c (ffffffff813599c7)
Location: include/linux/list.h:157
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81387a7e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813885f3)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff81397998)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813af2f5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff813bfcf9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff813db08c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff813e5c1c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff813ff05e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/selinux/hooks.c (ffffffff81419504)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff814411ea)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8144d64e)
Location: include/linux/list.h:157
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8145a2d0)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8145ccff)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff81477bcf)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff8149a39e)
Location: include/linux/list.h:157
Inline: True
```
```
In block/blk-flush.c (ffffffff814a1789)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814a2dc5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814a62c3)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814aafac)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814b2afe)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff814bd767)
Location: include/linux/list.h:157
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c1c9c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff814c4593)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/mq-deadline.c (ffffffff814c7e65)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff81504162)
Location: include/linux/list.h:157
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828d2ec6)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff8150c67c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81522e0d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81526141)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff8158c00f)
Location: include/linux/list.h:157
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81592454)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff8162da33)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff81664046)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff816a011a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff816a0c7a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff816a25d5)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff816a4162)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff816a6ae2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff816b497f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff816b911f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc02e)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff816d432d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/nvdimm/bus.c (ffffffff816f375c)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81706bc9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a190)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81711518)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715189)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff8171626a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8174cc06)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81755b4a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff8176195a)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff8177ed46)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff8178d4f2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179bade)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2e84)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817b2b96)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817be876)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff817c229f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cb76f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d0771)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9f33)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff817e0e39)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff817e4dae)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff817e9ffe)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff8180587f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff818226ea)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffff818323cb)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8186e9ab)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff818a8865)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818b5b56)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff818c6642)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff818d28fc)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff8192c181)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff8194573d)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c400)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff8198558f)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819922f2)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1ec9)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/rfkill/core.c (ffffffff819f6aad)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a012da)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81a09e96)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81a0c2e7)
Location: include/linux/list.h:157
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810160d7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107304d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a06fb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7f23)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aec1e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810ba1d4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810c1f10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810c5938)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810e0cae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810e332a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810e9c51)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810ea2f1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff81117807)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828c6db6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff81130d6e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81138625)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
  - kernel/time/posix-cpu-timers.c:cleanup_timers
```
```
In kernel/time/clockevents.c (ffffffff8113a5d8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8113fd0a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8115adba)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8115f37b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81167df2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff811750b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81176a0d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828cc230)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff81192970)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811adbb3)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828ce874)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c0dbf)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c361e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd3de)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In kernel/bpf/offload.c (ffffffff811f4921)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff81209b47)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff8121097b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff8122f81e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff81248b95)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8127c2d2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812a7f0d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812b1937)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812bebf5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812c3f33)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffff812cde25)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffff812d095a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812e5e7c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812eb936)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812f56d2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs-writeback.c (ffffffff81301ea8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff813030ae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8130e034)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffff81312e7e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff8131a09c)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffff8131a835)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131eeab)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff813213c7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81325709)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffff81329ab5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8132f65c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff8133b9b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff813474d7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff813519f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff8137048a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81371b82)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
```
In fs/configfs/symlink.c (ffffffff81373da4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/ext4/extents_status.c (ffffffff81382a27)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813b1af2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813b26cb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813c18d7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813d981f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff813ea4f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff81406c6c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81411b8c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff8142b22e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8142d07e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff814470f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff8146edf7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8147b31e)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81487c7c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8148a321)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff814a587e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814c848e)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffff814cfa22)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814d0e75)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814d41c3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814d92b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814e0fc0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff814ebe1b)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f034e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff814f2d68)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/mq-deadline.c (ffffffff814f66f5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff815322c0)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828ecf11)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff8153ad9c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff815512de)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81555061)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff815bce25)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815c3357)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff816615e3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff816987e9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff816d8826)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff816d9bba)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff816db3a5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff816dd092)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff816dfb8e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff816ee831)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff816f3154)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f66b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff8170e4cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff8172d0b1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81741d9c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745996)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c958)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750980)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff81751a4b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81788b56)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81791c73)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff8179f63c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff817bd3a6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff817ca5ec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dabce)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e331f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817f066f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fe1d6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81801e22)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180bb39)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180e192)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a8d4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81821700)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81825812)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff8182a564)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff81847860)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff81864bda)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff81874bcf)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff818b2c5b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In drivers/soundwire/bus.c (ffffffff818c107a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_delete_slave
```
```
In net/core/net_namespace.c (ffffffff818f3e8e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818ff4b5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff8191271a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff8191fc02)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff8198f4e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9d34)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e5729)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819ef3af)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819fd93b)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffff819fe064)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81a203af)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffff81a6606f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a70417)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81a796e6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81a7bc47)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016a87)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074034)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a6cd3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810ae543)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b5235)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810c0654)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810c8470)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810cea18)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810eb33e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810edbc0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/sched/wait.c (ffffffff810f5621)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810f5cc1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff81123bdb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828cf3cb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff8113ccae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114430e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff81146248)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8114c134)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffffffff81166a6a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8116afdb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81173cb2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81180f28)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81182940)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828d4706)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e5f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811b9453)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828d6dc6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cc66f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cf717)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811d7820)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d85e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (ffffffff8120191d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff81216eb7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff8121d529)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff8123d9ee)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff81256fe5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8128bdad)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812b9401)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812c3327)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812d0b55)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812d5133)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffff812df86d)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffff812e250a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812f792c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812fd466)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff81307252)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffffffff8130cd05)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff81314fab)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff8131612e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff81321367)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffff81325dbe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff8132cecc)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffff8132d675)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331c5b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff813351b7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81338499)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffff8133c685)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81343539)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff81353f08)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff8135f647)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff81369d78)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff8138897a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81389fc2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/symlink.c (ffffffff8138bfe6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff8139af27)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813cab42)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813cb71b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813dac57)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813f380f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81404598)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff81420149)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8142b88d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff81444f7e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff81446dce)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81460c84)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff81488bf7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff81494fee)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814a1b2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814a41e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff814c052e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814e158e)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffff814e8d82)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814ea232)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814ed4e3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814f2674)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814fa3f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff815051db)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815097fb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff8150c308)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff81511424)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff81514525)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff81553100)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828f604a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff8155bbbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8157289e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff815766d1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff815de0e5)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815e4597)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff81683c33)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff816bb3f9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff816fc92b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff816fdb6a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff816ff375)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff81701142)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff81703dda)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff81712811)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff817175cf)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171aab4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff817327cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff817510f1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81765deb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769b21)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81770ad8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774bab)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff81775cce)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817ac756)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff817b5860)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff817c38cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff817ed686)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff817fb1a5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180baee)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812e43)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182155f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182f026)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81833052)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183caf9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183f282)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bf54)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81852b70)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81856d3e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff8185bef4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff8187919d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff8189691a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff818a69df)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff818e557b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81925e49)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81931815)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81944d7a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff81951e42)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff819c6221)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e09f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c759)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2627f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81a3452b)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffff81a34c54)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81a56ff6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffff81a9cbb4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa6c47)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81ab0a46)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81ab2fa7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101821a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107b155)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810acb90)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b60e3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b8025)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
```
In kernel/workqueue.c (ffffffff810c7dcc)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff810d0000)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810d88d8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810f5199)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810f74e4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
```
```
In kernel/sched/wait.c (ffffffff810fed61)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810ff4a1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f51f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff81131154)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/srcutree.c (ffffffff82cf0569)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff8114badd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153e1e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff81155f17)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/clockevents.c:clockevents_replace
```
```
In kernel/futex.c (ffffffff8115c8bf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff81177c05)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8117d12f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81185ab6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81192d92)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff81195dc7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:do_free_cleaned_kprobes
  - kernel/kprobes.c:do_unoptimize_kprobes
```
```
In kernel/trace/ftrace.c (ffffffff82cf5103)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7173)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_insert_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811d1b76)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff82cf69f0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_synth.c (ffffffff811def65)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ed460)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811f4170)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6477)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/arraymap.c (ffffffff8121a3e2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff81228cfd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff81242add)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff81249819)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/shmem.c (ffffffff8126af3e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff812856c5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff812becae)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812edf5f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812f8de7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff81307523)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81316615)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/char_dev.c (ffffffff81319784)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8133055c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff813378ce)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8134097a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff813466a1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff8134dc0a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/pnode.c (ffffffff8134fc9a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:umount_list
  - fs/pnode.c:umount_list
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8135ba92)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/block_dev.c (ffffffff8135f021)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff81366c84)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff81367425)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136bdcb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8136f066)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81372259)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/aio.c (ffffffff81376d3d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81384876)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:__io_timeout_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:io_req_link_next
  - fs/io_uring.c:io_req_link_next
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff8139e0cb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff813a5223)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/iomap/buffered-io.c (ffffffff813ab857)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813b17e1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff813d36ba)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813d49e2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff813d7326)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff813e6417)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/namei.c (ffffffff81416b30)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff81417887)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/ext4/super.c (ffffffff81427437)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff81440b38)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff814524e8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff8146ee89)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8147b63d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/pstore/inode.c (ffffffff814843bb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In security/keys/key.c (ffffffff81495e6e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8149867e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff814b5924)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff814dd785)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff814f0000)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/policy.c (ffffffff814fb952)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814feff8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff8152067e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff8154009e)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-flush.c (ffffffff81547d30)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff815491d2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff8154d0c3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff81551910)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff8155b3a0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff81565aab)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81569c0c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff8156d76a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff81572429)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff81575375)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff815dc41b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff82d0973e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff815e573c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In lib/kobject.c (ffffffff815eacc6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff815ed837)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81616c7c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff8161b1f8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff81688985)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8168f537)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff8173599d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff8176f739)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/iommu/iommu.c (ffffffff8178ff67)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff817b6311)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:fw_devlink_resume
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
  - drivers/base/core.c:device_link_add_missing_supplier_links
```
```
In drivers/base/bus.c (ffffffff817b75d5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff817b91c5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff817bb62d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff817bdfba)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
```
```
In drivers/base/power/main.c (ffffffff817ce031)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff817d26b6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6b20)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/block/xen-blkfront.c (ffffffff817ede3a)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8180f9be)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818272f1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bcec)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff818333a1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837f5f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff818392ae)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81872976)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff8187c7f7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81887d35)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff8188ba12)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff818bcc16)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff818cb269)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818dca51)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4eb1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f091e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819006a8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_isochronous_tds
```
```
In drivers/usb/host/xhci.c (ffffffff81904fc2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190f5a7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81913941)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e7cf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81924c82)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81929f9e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff8192eb94)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff81963b5a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff8197682f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff819b884b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff819f868b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81a06fbd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_poll
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81a15263)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_update_gc_list
```
```
In net/core/link_watch.c (ffffffff81a22ce2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff81ab5d99)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81acdfb2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81afcae6)
Location: include/linux/list.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0db19)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17c95)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81b2931a)
Location: include/linux/list.h:202
Inline: True
```
```
In net/unix/scm.c (ffffffff81b29a94)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4df8f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff81b979b4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba2ac7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810188ed)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685a6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107af65)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a8250)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b12d5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b32d5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
```
In kernel/workqueue.c (ffffffff810c2eec)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff810ca9f0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810d3a78)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810f324c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/rt.c (ffffffff810f56e4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
```
```
In kernel/sched/wait.c (ffffffff810fd664)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810fdfa4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c6df)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff8112c5c8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_del_holdout
```
```
In kernel/rcu/srcutree.c (ffffffff82fdcf04)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff81147f3d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f9e9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:handle_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff811520b7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/clockevents.c:clockevents_replace
```
```
In kernel/futex.c (ffffffff811585e6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:pi_state_update_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff81174905)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff81179f8f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81182bd6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8118ff02)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/kprobes.c (ffffffff81192a5a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:do_free_cleaned_kprobes
  - kernel/kprobes.c:do_unoptimize_kprobes
```
```
In kernel/seccomp.c (ffffffff811a3566)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff82fe1be2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4d33)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_insert_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811cf4f6)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff82fe34e1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dc285)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb5b0)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811f2b20)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e57)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/arraymap.c (ffffffff8121d002)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff8123083d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8124d22e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff812546a9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/shmem.c (ffffffff812758de)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff8128f9a5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff812ca88b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812f95cf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81304ce7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff81313263)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81321ae5)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/char_dev.c (ffffffff81324e64)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8133beec)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff8134320e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8134ca0a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff81352b91)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff8135aaa5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/pnode.c (ffffffff8135c958)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:umount_list
  - fs/pnode.c:umount_list
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8136a042)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/block_dev.c (ffffffff8136c7e2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
```
```
In fs/notify/notification.c (ffffffff81373fd4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff81374785)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137966b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8137b750)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff813800a9)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/aio.c (ffffffff813849e9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81392634)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_timeout_extract
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
```
```
In fs/locks.c (ffffffff813afa5b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff813b5f83)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/iomap/buffered-io.c (ffffffff813bc246)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813c2de1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff813e53fa)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813e6702)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff813e8fc6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff813f874b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/namei.c (ffffffff8142a0a5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff8142b387)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/ext4/super.c (ffffffff8143f227)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff81455c1a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/jbd2/commit.c (ffffffff8145cd6d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff8146e9c8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff814895f4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff814963bd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff8149824b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff8149d4f0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dax.c:inode_inline_reclaim_one_dmap
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/pstore/inode.c (ffffffff814a1a0b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In security/keys/key.c (ffffffff814b38ce)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff814b60ee)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff814d3607)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff814faba5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8150d480)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/policy.c (ffffffff8151899a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151c258)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff8153d50e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff8155c83e)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-flush.c (ffffffff81563a50)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff81564fb2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8156da60)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_done_softirq
```
```
In block/genhd.c (ffffffff815775e1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff81580a2b)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158451c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff81587dba)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff8158e700)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff815921b2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff815fa0bb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff82ff6c9c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff81609b1c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In lib/kobject.c (ffffffff8160f5dd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff81611f67)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163d5ac)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81641988)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff816a6555)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff816ad207)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/xen/events/events_base.c (ffffffff81733c01)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff81751b4d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff8178a679)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/iommu/iommu.c (ffffffff817bc367)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff817cb781)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff817cc2f5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff817cdf55)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff817d021d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff817d2d0a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
```
```
In drivers/base/power/main.c (ffffffff817e2941)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff817e6df6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb6c6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/block/xen-blkfront.c (ffffffff8180276a)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8181e8fe)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837d91)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cd5c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81843fa0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184887c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81849b2e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81881456)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff8188b147)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81895fd5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff81899ca7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff818c9917)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff818d6359)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e68e1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee381)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f9c3e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81908f78)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_isochronous_tds
```
```
In drivers/usb/host/xhci.c (ffffffff8190d847)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81917107)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191af66)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819262b6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff8192ca32)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff8193150e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81935f34)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff8196a44a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff8197b53f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff819bacae)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff819f811a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81a0856d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81a15553)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_remove_one
  - net/core/neighbour.c:neigh_update_gc_list
```
```
In net/core/link_watch.c (ffffffff81a23042)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff81ac10ef)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ad9fd4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81b0a966)
Location: include/linux/list.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bd29)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25d65)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81b37c4a)
Location: include/linux/list.h:202
Inline: True
```
```
In net/unix/scm.c (ffffffff81b383c4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5cc20)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff81ba7677)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb2347)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019c0c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106911b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107c142)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a9110)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810b2895)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810ba919)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
```
In kernel/workqueue.c (ffffffff810c4d14)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff810cd661)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810d574e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810f537e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/rt.c (ffffffff810f7816)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810ffa44)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff81100384)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e50b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff8112cdd6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
```
In kernel/rcu/srcutree.c (ffffffff831e7c62)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff811494ed)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150dc7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/time/clockevents.c (ffffffff811535a7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff81159866)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:pi_state_update_owner
```
```
In kernel/cgroup/cgroup.c (ffffffff811754d0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8117ab0f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81183d26)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81190e32)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81193989)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/seccomp.c (ffffffff811a419d)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff831ec0a8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3a3b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811cfb5e)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff831edc53)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dd775)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec980)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811f39b0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d47)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/arraymap.c (ffffffff81220b12)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff812349ed)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff81251aee)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff81258c49)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/shmem.c (ffffffff8127abfe)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff81295005)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff812d13cf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812ffb9d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8130bce7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff813183eb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81327bb5)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/char_dev.c (ffffffff8132b014)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8134237c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff813494ce)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff813535d9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff81359be1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff81361585)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/pnode.c (ffffffff8136354c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8136fbc1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/block_dev.c (ffffffff81373112)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
```
```
In fs/notify/notification.c (ffffffff8137a97f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff8137b135)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813801db)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff81381ed0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81386d59)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/aio.c (ffffffff8138b9d9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8139a331)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_sq_thread_finish
  - fs/io_uring.c:io_timeout_extract
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/io-wq.c (ffffffff813a2583)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wqe_hash_wake
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/locks.c (ffffffff813b6ceb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff813bd0d3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/iomap/buffered-io.c (ffffffff813c3724)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813ca040)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff813ec00a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813ed112)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff813efb36)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff813ff28b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/mballoc.c (ffffffff8141ba48)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/namei.c (ffffffff81430da5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff81431f9a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff81449db7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff8145b82d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/jbd2/commit.c (ffffffff81462779)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81473ef8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff8148ee84)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8149b44d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff8149d47b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff814a23f3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/pstore/inode.c (ffffffff814a7b3b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In security/keys/key.c (ffffffff814b96fe)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff814bbf5e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff814d9c3e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff81501a75)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff81513e90)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/policy.c (ffffffff8151f1d6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff815229bf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff81545bee)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff815650ce)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-flush.c (ffffffff8156c196)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8156d622)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8157722f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff8157f3be)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff8158859b)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158b31c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff8158ec0a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff81595460)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
```
```
In block/mq-deadline.c (ffffffff815992d5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff815dcc9b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff83201981)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff815ecd5c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In lib/kobject.c (ffffffff815f2d1d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff815f5657)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8162122c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81624855)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff816891e5)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff8168f827)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/xen/events/events_base.c (ffffffff817176b1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff81735f2d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff8176dd29)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/iommu/iommu.c (ffffffff8179f547)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff817af0f1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff817afc6a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff817b18e5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff817b3c42)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff817b671a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
```
```
In drivers/base/power/main.c (ffffffff817c6d21)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff817cb606)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/main.c (ffffffff817cf14e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cfea3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff817d03ab)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/block/xen-blkfront.c (ffffffff817e719a)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81801c6e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181b07c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182017c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81827110)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bc1d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182cf5e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81863ce6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff8186dab7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81878845)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff8187c457)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff818ad117)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff818b9815)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c79f3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1b81)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818dc9bc)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ed7e5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff818f0de2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818fa587)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fe12f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909986)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff8190fe31)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81914b4e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81919b64)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff8194f13a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff8195f76f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8199f4ce)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff819de683)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff819eeca5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff819fc0b3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff81a0a372)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff81aac09f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac5032)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81af80b0)
Location: include/linux/list.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b09a1c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1342b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81b258ea)
Location: include/linux/list.h:202
Inline: True
```
```
In net/unix/scm.c (ffffffff81b26064)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4ae39)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff81b96807)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1367)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In net/mptcp/protocol.c (ffffffff81bb0a69)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101c36f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073453)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8108a2a9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810bac00)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810c4a35)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810cd1c4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810d7953)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff810e0851)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810e896e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff8110efce)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/rt.c (ffffffff81111e65)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff8111bb13)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff8111c403)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_one
  - kernel/sched/swait.c:swake_up_all_locked
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112dc6b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff8114da9e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
```
In kernel/rcu/srcutree.c (ffffffff832cbd56)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff8116cead)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175197)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/time/clockevents.c (ffffffff81177c0f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8117e786)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/cgroup/cgroup.c (ffffffff8119ca2c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff811a250f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff811abeb3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff811b9d12)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff811bc89c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/seccomp.c (ffffffff811cd87c)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff832d0b30)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811dd9eb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811fc088)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_trigger.c (ffffffff832d28ca)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_eprobe.c (ffffffff812098b7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120cf84)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d9e0)
Location: include/linux/list.h:202
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81224c70)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227e27)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/arraymap.c (ffffffff81257cf2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff8126f53e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8128d310)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff8129486d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/shmem.c (ffffffff812b8c5e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff812d5665)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff81316ab8)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/kfence/core.c (ffffffff8133beb9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff813497ed)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81356fc7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff813648f3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff81375185)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/char_dev.c (ffffffff81378724)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff81392fd7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff8139721e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff813a1a29)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff813a8081)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff813afbe5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff813b1d4c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff813be870)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/notification.c (ffffffff813c75fc)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff813c7d97)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd911)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff813cf122)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff813d3fe9)
Location: include/linux/list.h:202
Inline: True
```
```
In fs/aio.c (ffffffff813d8f89)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff813e9a9c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_sq_thread_finish
  - fs/io_uring.c:io_timeout_extract
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_commit_cqring_flush
```
```
In fs/io-wq.c (ffffffff813f3078)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wqe_hash_wake
```
```
In fs/locks.c (ffffffff814069eb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff8140ce64)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/iomap/buffered-io.c (ffffffff81413d8c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff8141ab4c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff8143ddc5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8143f012)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff81441a26)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff8145189b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/mballoc.c (ffffffff8146ed78)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/page-io.c (ffffffff814857e9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8149de67)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff814af0f4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/ext4/orphan.c (ffffffff814b15bf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/commit.c (ffffffff814b7c6f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff814cab98)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff814e68f4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff814f2e9d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff814f4eed)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff814fb12c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/pstore/inode.c (ffffffff814ffe2b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In ipc/shm.c (ffffffff8150c53b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In security/keys/key.c (ffffffff81511f2e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff815147de)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81532b3e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff8155d0f5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff81571caa)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/policy.c (ffffffff8157d376)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81580c1e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff815a60fe)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff815c944e)
Location: include/linux/list.h:202
Inline: True
```
```
In block/blk-flush.c (ffffffff815d06d1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff815d1c12)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff815dbf8f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-rq-qos.c (ffffffff815ee23b)
Location: include/linux/list.h:202
Inline: True
```
```
In block/disk-events.c (ffffffff815ef19f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/disk-events.c:disk_del_events
```
```
In block/blk-cgroup.c (ffffffff815f034a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff815f4c6a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff815fc38d)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
```
```
In block/mq-deadline.c (ffffffff81601be4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In block/holder.c (ffffffff8160f96c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - block/holder.c:bd_unlink_disk_holder
```
```
In lib/error-inject.c (ffffffff816485fb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff832e9001)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff81659c0c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In lib/kobject.c (ffffffff8165fefd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff81662ab7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8169091c)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81693dcf)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff816fe625)
Location: include/linux/list.h:202
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81705287)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/xen/events/events_base.c (ffffffff81794ab3)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff817b68ed)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff817f34f9)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
```
```
In drivers/iommu/iommu.c (ffffffff81828537)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff81838313)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81838f2a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff8183ab92)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff8183d122)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff818412bc)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff818510fe)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff81855626)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/main.c (ffffffff81859833)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a6c2)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff8185abdb)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/block/loop.c (ffffffff8186fca6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81876fc4)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff8188c16e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a54fc)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa846)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff818b2ae0)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scsi_eh_complete_abort
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b77d1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b8cfe)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818f3026)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff818fdb03)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81909785)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff8190d9cd)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff819421b7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff8194f315)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8195f853)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c553)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819783ac)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81989ef5)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff8198d533)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81999315)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199d4a1)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa1f6)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff819b0d21)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff819b6cde)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff819bbf83)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff819f4647)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff81a050af)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff81a4c16e)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81a8e3ff)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81aa0016)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81aae11a)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff81abc882)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff81b6857f)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b83842)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81bb8e26)
Location: include/linux/list.h:202
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc9ab)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd732b)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81beb02b)
Location: include/linux/list.h:202
Inline: True
```
```
In net/unix/scm.c (ffffffff81bebccc)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81c12179)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff81c63137)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6edd7)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In net/mptcp/protocol.c (ffffffff81c7eb29)
Location: include/linux/list.h:202
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101eb3f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810808c3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a7b8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810d3046)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810dbd45)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810e5198)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810f2196)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff810fa620)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff811033ce)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff8112ae48)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8112efbe)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff8113bed3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:finish_swait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:__wait_for_common
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114ea3f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff81174822)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/srcutree.c (ffffffff8347f6c5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff8117c6a4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
```
```
In kernel/time/clocksource.c (ffffffff811a1339)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa46d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/time/clockevents.c (ffffffff811acc63)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex/core.c (ffffffff811b238d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811b4798)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cccf8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff811d2f7f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff811dd8cb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff811ecf1c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff811ef908)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/seccomp.c (ffffffff81201ff3)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff83484bbd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff81214c44)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff812363c9)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (ffffffff83486cfd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246097)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff81249663)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cfaf)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81264ae0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812671d4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/arraymap.c (ffffffff812a1284)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff812be86f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff812e2011)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff812e9aab)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/shmem.c (ffffffff813149ee)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff813348e5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff81381caa)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/kfence/core.c (ffffffff813aeb1f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/huge_memory.c (ffffffff813bff3f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813d00a5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff813dfe16)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff813f4495)
Location: include/linux/list.h:204
Inline: True
```
```
In fs/char_dev.c (ffffffff813f6ff0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff814146dd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff8141932c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff81425435)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff8142beb3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff81434765)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff81436d14)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff81444110)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/notification.c (ffffffff8144ea20)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff8144f635)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456028)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8145757e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_autoremove_wake_function
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff8145d3eb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_wake_function
```
```
In fs/aio.c (ffffffff8146339d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff8147b534)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff81481cb2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/iomap/buffered-io.c (ffffffff814899c3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff81490d2a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff814b96c4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff814bb170)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff814bd610)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff814cde19)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/mballoc.c (ffffffff814ef794)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_set_largest_free_order
```
```
In fs/ext4/page-io.c (ffffffff81508c83)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff81521911)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff815361a3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/ext4/orphan.c (ffffffff8153a0f8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/commit.c (ffffffff81541720)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81556b64)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff81574654)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff815828fd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff81584e0d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff8158b5fc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/pstore/inode.c (ffffffff81590fbb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In ipc/shm.c (ffffffff8159e4b3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In security/keys/key.c (ffffffff815a432e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff815a6e5e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff815c61fe)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff815f6d8b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8160eae1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/policy.c (ffffffff8161b9e7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161fd96)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff8164d4a1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff816744ce)
Location: include/linux/list.h:204
Inline: True
```
```
In block/blk-flush.c (ffffffff8167bed7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8167db32)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff816869bc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-rq-qos.c (ffffffff8169ea19)
Location: include/linux/list.h:204
Inline: True
```
```
In block/disk-events.c (ffffffff8169fb5f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/disk-events.c:disk_del_events
```
```
In block/blk-cgroup.c (ffffffff816a159a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff816a66c4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff816b0a92)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
```
```
In block/mq-deadline.c (ffffffff816b46d1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In block/holder.c (ffffffff816c42bf)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/holder.c:bd_unlink_disk_holder
```
```
In io_uring/io_uring.c (ffffffff81e920d7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_sq_thread_finish
  - io_uring/io_uring.c:io_timeout_extract
  - io_uring/io_uring.c:io_timeout_fn
  - io_uring/io_uring.c:io_arm_poll_handler
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_async_buf_func
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/io-wq.c (ffffffff816dbbed)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wqe_hash_wake
```
```
In lib/error-inject.c (ffffffff8175ea08)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff834a06f2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff8177233c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In lib/kobject.c (ffffffff817799dd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff8177c987)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff817afb53)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff817b47af)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f44c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
```
In drivers/acpi/glue.c (ffffffff8182bd9d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/acpi/glue.c:unregister_acpi_bus_type
```
```
In drivers/acpi/ec.c (ffffffff818333d7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/xen/events/events_base.c (ffffffff818cd736)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff818f195d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/iommu/iommu.c (ffffffff819684d3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff8197a687)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff8197b524)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff8197d142)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff8197fd2c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff81984689)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff81996bfc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff8199b899)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/main.c (ffffffff819a0433)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff819a100e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a1843)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
```
In drivers/block/loop.c (ffffffff819b6663)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff819bf1c6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff819d54fe)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ef116)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4746)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff819fdcff)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02f54)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a045d2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81a456f6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81a4f16d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81a5cdd5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff81a61d18)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a80fe0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a09d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff81aa8374)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ab9ce3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac69e5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad5c3c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5245)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81ae9771)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af62e7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afab31)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07e66)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81b0eb9f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81b1676e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81b1c303)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff81b57647)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff81b6cdff)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff81bba8be)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81c04322)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81c15aee)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81c28742)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_mark_dead
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/link_watch.c (ffffffff81c3731f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/route.c (ffffffff81cce42b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
```
```
In net/ipv4/tcp_input.c (ffffffff81cf76cd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d13f20)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81d4cd60)
Location: include/linux/list.h:204
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d626bb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6dd3c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81d83305)
Location: include/linux/list.h:204
Inline: True
```
```
In net/unix/scm.c (ffffffff81d841c8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/route.c (ffffffff81da0f13)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81dad6f4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff81e05ad7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e12974)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1aadc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
```
In net/mptcp/protocol.c (ffffffff81e242d8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810230cf)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093463)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b11ac)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810f1b77)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff810fbe55)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81105883)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff81112fc6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff8111d410)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff81128a5e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff81154875)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81158d8e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff811669f3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:finish_swait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117dbdf)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff811ab47a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_read_unlock_trace_special
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/srcutree.c (ffffffff83eababe)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811b673f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
```
```
In kernel/time/clocksource.c (ffffffff811e0279)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea4ba)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/time/clockevents.c (ffffffff811ed0e3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex/core.c (ffffffff811f320d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811f5838)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210294)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff81216eef)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff8122333b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff812334ac)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8123631d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/seccomp.c (ffffffff81249ca3)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff83eb3370)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff812603c4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff81282af1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:blk_trace_remove
```
```
In kernel/trace/trace_events_trigger.c (ffffffff83eb64f0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_eprobe.c (ffffffff81292fb7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff81298afa)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac23f)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812b6650)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b9244)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/helpers.c (ffffffff812f40fb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_list_pop_back
  - kernel/bpf/helpers.c:bpf_list_pop_front
```
```
In kernel/bpf/arraymap.c (ffffffff812fe054)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff81321b14)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8134a544)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:put_pmu_ctx
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff813538eb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/vmscan.c (ffffffff813870a5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813888de)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff813ab5e5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/vmalloc.c (ffffffff813e125e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff8140042c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/kfence/core.c (ffffffff8142f070)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memory-tiers.c (ffffffff820cc142)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
```
```
In mm/huge_memory.c (ffffffff8144222f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff814550f5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff81466c5f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff8147d525)
Location: include/linux/list.h:204
Inline: True
```
```
In fs/char_dev.c (ffffffff814802a0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff8149fbad)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff814a4d4c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff814b1bb5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff814b9593)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff814c2745)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff814c4d74)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff814d3260)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/notification.c (ffffffff814dd190)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff814ddec5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4fc8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff814e680e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_autoremove_wake_function
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff814eccfb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_wake_function
```
```
In fs/aio.c (ffffffff814f3a8d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff8150e0c4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff81514ad4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In fs/iomap/buffered-io.c (ffffffff8151d85f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff815248da)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff81550e54)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81552aa0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff81555290)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff815665a9)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/mballoc.c (ffffffff8158aa5e)
Location: include/linux/list.h:204
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a37e3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff815be5d1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff815d46a3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/ext4/orphan.c (ffffffff815d8668)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/commit.c (ffffffff815e0364)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff815f8714)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff81619f04)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8162882d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff8162af9d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff81631e41)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/pstore/inode.c (ffffffff8163858b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In ipc/shm.c (ffffffff81647b33)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In security/keys/key.c (ffffffff8164e07e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff81650e2e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81672e7e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff816a791b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff816c0da1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/audit.c (ffffffff816c1f14)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/policy.c (ffffffff816ceab0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff816d31e9)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In security/apparmor/notify.c (ffffffff816eb52f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
```
```
In crypto/algapi.c (ffffffff81706511)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff817301fe)
Location: include/linux/list.h:204
Inline: True
```
```
In block/blk-flush.c (ffffffff81738743)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8173a752)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff8174528c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-rq-qos.c (ffffffff8175d209)
Location: include/linux/list.h:204
Inline: True
```
```
In block/disk-events.c (ffffffff8175e57f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/disk-events.c:disk_del_events
```
```
In block/blk-cgroup.c (ffffffff8176040a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff817656d4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff817708f6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
```
```
In block/mq-deadline.c (ffffffff81774101)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In block/holder.c (ffffffff8178580b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/holder.c:bd_unlink_disk_holder
```
```
In io_uring/io_uring.c (ffffffff8178f3e8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/timeout.c (ffffffff81799f84)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff8179ab61)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_finish
```
```
In io_uring/poll.c (ffffffff8179d613)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
```
In io_uring/kbuf.c (ffffffff8179f5f6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_destroy_buffers
```
```
In io_uring/rw.c (ffffffff817a354c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/rw.c:io_async_buf_func
```
```
In io_uring/io-wq.c (ffffffff817a7cf9)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wqe_hash_wake
```
```
In lib/error-inject.c (ffffffff8188c268)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff83ed96bf)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff818a2bac)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff818c9363)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff818ceb3f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e1ec)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
```
In drivers/acpi/glue.c (ffffffff8195e868)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/acpi/glue.c:unregister_acpi_bus_type
```
```
In drivers/acpi/ec.c (ffffffff81966e67)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/xen/events/events_base.c (ffffffff81a1ed36)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff81a499dd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/iommu/iommu.c (ffffffff81ad2214)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff81ae74f7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81ae85c4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff81aea4f2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff81aed65c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff81af2829)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff81b079cc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff81b0ca79)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11fbe)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff81b12d0e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b135e3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
```
In drivers/block/loop.c (ffffffff81b2b873)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81b349bb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff81b4ff9e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c646)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71b76)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7c14f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b818c7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b831e2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81bcc026)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81bd6ca7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81be7995)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff81bed6c8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e60d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff81c2f394)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c430d3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50b95)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c60c4c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70e65)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81c75ad1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c83c77)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c88fa7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c977c6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81c9ee4f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81ca7ace)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81cae303)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff81cf14f7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff81d08f96)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff81d5fe5e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81db3a32)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81dc6ece)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81ddb35a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_mark_dead
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/link_watch.c (ffffffff81deab0f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/route.c (ffffffff81e8e63b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
```
```
In net/ipv4/tcp_input.c (ffffffff81ebc16d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ed9f40)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81f16600)
Location: include/linux/list.h:204
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d1bb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81f395cc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81f50995)
Location: include/linux/list.h:204
Inline: True
```
```
In net/unix/scm.c (ffffffff81f51a68)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/route.c (ffffffff81f70213)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7d164)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff81fdad77)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe9494)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1fbc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
```
In net/mptcp/protocol.c (ffffffff81ffbdb8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In lib/kobject.c (ffffffff820229ad)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff820393c7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81022dcf)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810963c3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b415c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810fdafa)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff81107ef5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff81111b25)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff81120c24)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:idle_cull_fn
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff8112a530)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff81135f0e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff811649b2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81169067)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff81176e63)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:finish_swait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e87f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff811bd39a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_read_unlock_trace_special
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/srcutree.c (ffffffff836d0a7e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811c716f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
```
```
In kernel/time/clocksource.c (ffffffff811f4779)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811febde)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/time/clockevents.c (ffffffff81201803)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex/core.c (ffffffff8120798d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a038)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81225ca4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8122c80f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81239b6b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8124a15e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8124d13d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/seccomp.c (ffffffff81260f93)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff836d8630)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff8127765d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff8129f794)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:blk_trace_remove
```
```
In kernel/trace/trace_events_trigger.c (ffffffff836db8d0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0137)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b594a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
```
```
In kernel/trace/trace_events_user.c (ffffffff812c52d8)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cea3f)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812d9b40)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc8a4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dff41)
Location: include/linux/list.h:204
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff8132115b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_list_pop_back
  - kernel/bpf/helpers.c:bpf_list_pop_front
```
```
In kernel/bpf/arraymap.c (ffffffff8132cc64)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff81352836)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_prog_dev_bound_destroy
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8137b584)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:put_pmu_ctx
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff81384aeb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/vmscan.c (ffffffff813b7511)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813bab0e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff813df985)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/vmalloc.c (ffffffff814160a0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_block
  - mm/vmalloc.c:find_unlink_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff8143328c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/zswap.c (ffffffff81437b0c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/kfence/core.c (ffffffff81464d80)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memory-tiers.c (ffffffff821503f2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
```
```
In mm/huge_memory.c (ffffffff81477b3a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8148aff5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff8149eca7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff814b22e5)
Location: include/linux/list.h:204
Inline: True
```
```
In fs/char_dev.c (ffffffff814b5000)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff814d4ec7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff814d9edc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff814e6c04)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:m_stop
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff814ee552)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff814f7b05)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff814fa1f8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8150a250)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/notification.c (ffffffff815139f0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff815146f5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b218)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
```
In fs/eventpoll.c (ffffffff8151da75)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:__ep_remove
```
```
In fs/userfaultfd.c (ffffffff81523989)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_wake_function
```
```
In fs/aio.c (ffffffff8152a85d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff81545897)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff8154c4e3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In fs/iomap/buffered-io.c (ffffffff81555b04)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff8155cd03)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff81588b34)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158a823)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff8158d030)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff8159e239)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/mballoc.c (ffffffff815c132e)
Location: include/linux/list.h:204
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815da273)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff815f52e1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff8160c293)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/ext4/orphan.c (ffffffff816101f7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/commit.c (ffffffff81617c10)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81630694)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff816520a4)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81660a5d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff816631bd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff8166a081)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/pstore/inode.c (ffffffff8167098b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In ipc/shm.c (ffffffff8168004e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In security/keys/key.c (ffffffff816868de)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8168970e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff816ab31e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff816e031b)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff816f98a0)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/audit.c (ffffffff816fab4d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/policy.c (ffffffff817076bc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8170c0da)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In security/apparmor/notify.c (ffffffff81725a30)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
```
```
In crypto/algapi.c (ffffffff81740701)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff8176c42e)
Location: include/linux/list.h:204
Inline: True
```
```
In block/blk-flush.c (ffffffff81774d83)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff81776e6a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff817811fc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-rq-qos.c (ffffffff8179bf69)
Location: include/linux/list.h:204
Inline: True
```
```
In block/disk-events.c (ffffffff8179d47f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/disk-events.c:disk_del_events
```
```
In block/blk-cgroup.c (ffffffff817a0ed7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-throttle.c (ffffffff817a4794)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff817af946)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
```
```
In block/mq-deadline.c (ffffffff817b43dc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
```
In block/holder.c (ffffffff817c5c75)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - block/holder.c:bd_unlink_disk_holder
```
```
In io_uring/io_uring.c (ffffffff817d0735)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/timeout.c (ffffffff817d9bf9)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff817dbc11)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_finish
```
```
In io_uring/poll.c (ffffffff817de843)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
```
In io_uring/kbuf.c (ffffffff817e0788)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_destroy_buffers
```
```
In io_uring/rw.c (ffffffff817e44ec)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/rw.c:io_async_buf_func
```
```
In io_uring/io-wq.c (ffffffff817e8b9c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_hash_wake
```
```
In lib/error-inject.c (ffffffff818ce6d8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff836ff0f1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_module_notify
```
```
In lib/sbitmap.c (ffffffff818e510c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190c423)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81911bba)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819826ec)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
```
In drivers/acpi/glue.c (ffffffff819a4c58)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/acpi/glue.c:unregister_acpi_bus_type
```
```
In drivers/acpi/ec.c (ffffffff819ad3eb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/xen/events/events_base.c (ffffffff81a67f16)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff81a93c0d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/iommu/iommu.c (ffffffff81b20ad8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff81b358e1)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81b36772)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff81b38882)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff81b3b9cb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff81b40a8a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff81b55a1c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff81b5aa79)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b602ae)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff81b60ffe)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b618f7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
```
In drivers/block/loop.c (ffffffff81b7bb7f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81b87e96)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff81ba346e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfcd6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc584e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcfe9f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd55cd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd6f12)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81c23ba6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81c2d6d7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81c3fd55)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff81c45bf8)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff81c8550d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff81c96604)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caa833)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb8115)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc800c)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8445)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81cdcbe5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81cea980)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf01b5)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfeaf6)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81d0618f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81d0efde)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81d158f3)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff81d59797)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/dm-uevent.c (ffffffff81d72116)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff81dcaf5e)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81e240e2)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81e366be)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81e4be2f)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_mark_dead
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/link_watch.c (ffffffff81e5c2ef)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/route.c (ffffffff81eecd52)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
```
```
In net/ipv4/tcp_input.c (ffffffff81f1a5fd)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f39020)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff81f762b0)
Location: include/linux/list.h:204
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8ccbb)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81f990ac)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81fb0305)
Location: include/linux/list.h:204
Inline: True
```
```
In net/unix/scm.c (ffffffff81fb1418)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/route.c (ffffffff81fd032a)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd371)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff82056a67)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff82065714)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e1bc)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
```
In net/mptcp/protocol.c (ffffffff82078188)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/handshake/request.c (ffffffff8209380d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_next
```
```
In lib/kobject.c (ffffffff820a2a1d)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff820b76e7)
Location: include/linux/list.h:204
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81028eff)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109d933)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page_from_node
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bb5bc)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff811056cc)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:__exit_signal
```
```
In kernel/ptrace.c (ffffffff81111895)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8111b4c5)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff8112a4d4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:idle_cull_fn
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (ffffffff81134bc0)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff811410be)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff81171651)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117715e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff81184e23)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:finish_wait
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:finish_swait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:swake_up_all
  - kernel/sched/build_utility.c:swake_up_one
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
  - kernel/sched/build_utility.c:complete_all
  - kernel/sched/build_utility.c:complete
  - kernel/sched/build_utility.c:complete_on_current_cpu
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119d22f)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/rcu/update.c (ffffffff811cd9df)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_read_unlock_trace_special
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/srcutree.c (ffffffff83901f1e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811d768f)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
```
```
In kernel/time/clocksource.c (ffffffff8120a8b9)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214fdf)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/time/clockevents.c (ffffffff81217ca3)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex/core.c (ffffffff8121eb9d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff81221558)
Location: include/linux/list.h:285
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d934)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff812448cf)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8124b74f)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:remote_partition_disable
```
```
In kernel/stop_machine.c (ffffffff8125383b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8126406e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8126703d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/seccomp.c (ffffffff8127b187)
Location: include/linux/list.h:285
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8390abc0)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff812904a1)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff812baec4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:blk_trace_remove
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8390de70)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cc6a7)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d1fba)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1d2a)
Location: include/linux/list.h:285
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec43f)
Location: include/linux/list.h:285
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812f7aa0)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa984)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fdd61)
Location: include/linux/list.h:285
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff813437b4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_list_pop_back
  - kernel/bpf/helpers.c:bpf_list_pop_front
```
```
In kernel/bpf/arraymap.c (ffffffff81350fb4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_poke_untrack
```
```
In kernel/bpf/offload.c (ffffffff81379d16)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_prog_dev_bound_destroy
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff813a4784)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:put_pmu_ctx
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff813adefb)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
```
```
In mm/vmscan.c (ffffffff813e03a1)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813e514e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff8140a095)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/vmalloc.c (ffffffff81442b78)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_block
  - mm/vmalloc.c:find_unlink_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff8146c6ac)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/kfence/core.c (ffffffff814939d0)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/memory-tiers.c (ffffffff82233232)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
```
```
In mm/huge_memory.c (ffffffff814a72ba)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:folio_undo_large_rmappable
```
```
In mm/memcontrol.c (ffffffff814ba8f5)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff814ce425)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:fix_fullness_group
```
```
In fs/super.c (ffffffff814e39b5)
Location: include/linux/list.h:285
Inline: True
```
```
In fs/char_dev.c (ffffffff814e72c0)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_dynamic_release
  - fs/char_dev.c:cdev_default_release
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff81507202)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/inode.c (ffffffff8150c65c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8151aa44)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs-writeback.c (ffffffff8152c255)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/pnode.c (ffffffff8152eab7)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8153f1f0)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/notification.c (ffffffff81547e80)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff81548bc5)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154f818)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
```
In fs/eventpoll.c (ffffffff81552055)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:__ep_remove
```
```
In fs/userfaultfd.c (ffffffff81557fa9)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_wake_function
```
```
In fs/aio.c (ffffffff8155f72d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/locks.c (ffffffff8157adf7)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/mbcache.c (ffffffff81582313)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In fs/iomap/buffered-io.c (ffffffff8158bde6)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff81592def)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff815c1707)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c34f3)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/symlink.c (ffffffff815c5d76)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff815d6dc9)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/mballoc.c (ffffffff815f972e)
Location: include/linux/list.h:285
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81612a33)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff8162f22d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/ext4/fast_commit.c (ffffffff81645053)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
  - fs/ext4/fast_commit.c:ext4_fc_del
```
```
In fs/ext4/orphan.c (ffffffff81648fb7)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/commit.c (ffffffff81650b01)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff81669b44)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff8168b6b4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8169a91d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In fs/fuse/inode.c (ffffffff8169d32d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
```
In fs/fuse/dax.c (ffffffff816a43c1)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
  - fs/fuse/dax.c:dmap_reinit_add_to_free_pool
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In fs/debugfs/inode.c (ffffffff816a6076)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/pstore/inode.c (ffffffff816ac87b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
```
```
In ipc/shm.c (ffffffff816bc43e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In security/keys/key.c (ffffffff816c2d4e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff816c5c0e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff816e83ae)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff8171cf9b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff81736640)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/audit.c (ffffffff8173775d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_destroy
```
```
In security/apparmor/policy.c (ffffffff8174514c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81749e1d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In security/apparmor/notify.c (ffffffff81766c30)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_listener_unotif_recv
  - security/apparmor/notify.c:aa_listener_unotif_response
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:__listener_del_knotif
```
```
In crypto/algapi.c (ffffffff817815a1)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff817ae61e)
Location: include/linux/list.h:285
Inline: True
```
```
In block/blk-flush.c (ffffffff817b70bb)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff817b909a)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-mq.c (ffffffff817c3a5c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-rq-qos.c (ffffffff817df9c9)
Location: include/linux/list.h:285
Inline: True
```
```
In block/disk-events.c (ffffffff817e0ecf)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/disk-events.c:disk_del_events
```
```
In block/blk-cgroup.c (ffffffff817e4a24)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-throttle.c (ffffffff817e8364)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff817f3756)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
```
```
In block/mq-deadline.c (ffffffff817f838c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
```
In block/holder.c (ffffffff8180a965)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - block/holder.c:bd_unlink_disk_holder
```
```
In io_uring/io_uring.c (ffffffff81813f58)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/timeout.c (ffffffff8181e0dc)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff8181ff91)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_finish
```
```
In io_uring/poll.c (ffffffff81822c13)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
```
```
In io_uring/rw.c (ffffffff818285bc)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/rw.c:io_async_buf_func
```
```
In io_uring/waitid.c (ffffffff8182a5d2)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_wait
```
```
In io_uring/io-wq.c (ffffffff8182e94c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_hash_wake
```
```
In lib/error-inject.c (ffffffff819204b8)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - lib/error-inject.c:ei_module_callback
```
```
In lib/dynamic_debug.c (ffffffff83932a21)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_module_notify
```
```
In lib/sbitmap.c (ffffffff8192c10c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81954013)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9e66)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
```
In drivers/acpi/glue.c (ffffffff819ed5a8)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/acpi/glue.c:unregister_acpi_bus_type
```
```
In drivers/acpi/ec.c (ffffffff819f786b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/pmdomain/core.c (ffffffff81aa2539)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_remove_device
```
```
In drivers/xen/events/events_base.c (ffffffff81ab8e60)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/tty/tty_io.c (ffffffff81ae667d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/iommu/iommu.c (ffffffff81b77728)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
```
In drivers/base/core.c (ffffffff81b8d301)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:device_links_supplier_sync_state_resume
  - drivers/base/core.c:device_links_flush_sync_list
```
```
In drivers/base/bus.c (ffffffff81b8e192)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff81b90342)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff81b9351b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff81b9892a)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff81badfdc)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3cee)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff81bb4a8e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb5387)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
```
In drivers/block/loop.c (ffffffff81bcfb7f)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81bdbd46)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff81bf765e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c14456)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a22e)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81c24b02)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a225)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2bbb2)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_bridge.c (ffffffff81c80c6c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_bridge.c:devm_drm_bridge_add
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c85a50)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_unregister
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b095)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_closefb
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb_work_fn
```
```
In drivers/gpu/drm/drm_managed.c (ffffffff81ca0707)
Location: include/linux/list.h:285
Inline: True
```
```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca8d01)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_unlock_all
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81caec91)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_mode_destroyblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_property_destroy_user_blobs
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb0af9)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
```
```
In drivers/gpu/drm/drm_vblank_work.c (ffffffff81cb798a)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_cancel_sync
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_schedule
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_cancel_pending_works
  - drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works
```
```
In drivers/gpu/drm/drm_panel.c (ffffffff81cb98a9)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_panel.c:drm_panel_remove_follower
  - drivers/gpu/drm/drm_panel.c:drm_panel_remove
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81cd5466)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff81ce00c7)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81cf5355)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:unregister_mii_tstamp_controller
```
```
In drivers/net/tun.c (ffffffff81cfb508)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff81d39f0d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffffffff81d4b0e4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:reap_as
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d5f4e3)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6ce85)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7d54c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d455)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81d91c09)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da012b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da59d5)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3bf6)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81dbbd8f)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff81dc4cfe)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81dcb573)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/md/md.c (ffffffff81e10857)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/dm-uevent.c (ffffffff81e291e6)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff81e83ace)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81ee2042)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81ef49ae)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81f0ab3f)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_mark_dead
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/link_watch.c (ffffffff81f1b6df)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_sync_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/route.c (ffffffff81fb0de2)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
```
```
In net/ipv4/tcp_input.c (ffffffff81fdedcd)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff100)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/nexthop.c (ffffffff8203ca80)
Location: include/linux/list.h:285
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a64b)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff8206640c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8207d965)
Location: include/linux/list.h:285
Inline: True
```
```
In net/unix/scm.c (ffffffff8207eb40)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/route.c (ffffffff8209d8ba)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab4b1)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/rfkill/core.c (ffffffff82129127)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff821388b4)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8214223c)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
```
In net/mptcp/protocol.c (ffffffff8214d3e2)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/handshake/request.c (ffffffff8216a0bd)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_next
```
```
In lib/kobject.c (ffffffff8217aa9d)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
  - lib/kobject.c:kobject_add_internal
```
```
In lib/plist.c (ffffffff82191ff7)
Location: include/linux/list.h:285
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/eventfd.c (ffff8000100c0918)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/exit.c (ffff8000100fdb74)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffff800010108534)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff8000101114cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffff80001011d028)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffff800010128990)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffff80001012e8cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffff80001014b2f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffff80001014dd54)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
```
```
In kernel/sched/wait.c (ffff800010158cb8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffff800010159848)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffff800010188eb0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffff800011446aec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffff8000101a6de8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae880)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffff8000101b0810)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffff8000101b83d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8840)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffff8000101df1d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffff8000101e8028)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffff8000101f6494)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/trace/ftrace.c (ffff80001144ce9c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffff8000102171f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffff8000102368bc)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffff80001144f6d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffff80001024c36c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffff80001024fed8)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (ffff800010257b80)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffff8000102588e4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (ffff800010289ad0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffff8000102a10bc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffff8000102a9c1c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffff8000102cf448)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffff8000102ee964)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffff8000103272b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffff800010359d20)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffff800010366760)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffff80001037592c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffff80001037b028)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffff800010386768)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffff800010389d4c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffff8000103a597c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffff8000103adebc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffff8000103baad0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffff8000103c2038)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffff8000103cb198)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffff8000103ccafc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffff8000103d85a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffff8000103dff78)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffff8000103e8b2c)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffff8000103e9638)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103eef28)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffff8000103f214c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffff8000103f6c70)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffff8000103fe004)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff80001040520c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffff8000104165b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffff80001042529c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffff800010431f80)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffff800010458cb0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045a4ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/symlink.c (ffff80001045d778)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffff80001046d9bc)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffff8000104a273c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffff8000104a37a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffff8000104b1a80)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffff8000104ce9a4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffff8000104e312c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffff800010502b4c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffff80001050f6e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffff80001052dd84)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffff80001053056c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffff80001054e7cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffff80001057b78c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffff80001058b024)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffff8000105976f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffff800010599f18)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffff8000105b9bec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffff8000105de51c)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffff8000105e6d14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffff8000105e853c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffff8000105ec028)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffff8000105f1f18)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffff8000105fbfdc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffff8000106071c4)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060c5d8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffff800010610358)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffff8000106152b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffff8000106192e4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffff80001065f408)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffff800011470340)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffff80001066a094)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/bus/fsl-mc/fsl-mc-allocator.c (ffff800010683dbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_resource_allocate
```
```
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca660)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffff8000106d7a14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffff80001076a4a4)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffff800010770770)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/amba/bus.c (ffff8000107b9e98)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_deferred_retry_func
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080b2e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
```
In drivers/tty/tty_io.c (ffff800010850980)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffff8000108add8c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d973c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
```
```
In drivers/base/core.c (ffff8000108e7348)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffff8000108e87e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffff8000108ea468)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffff8000108ec980)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffff8000108f0d3c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffff8000109033f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffff800010909b20)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090dff0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffff800010929db4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffff800010951a90)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966db4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b3f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffff800010973f88)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffff800010978fa8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffff80001097b9f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffff8000109be370)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffff8000109c918c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffff8000109db900)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f5888)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:free_init_resources
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f7238)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_memac.c:free_init_resources
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f8444)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:free_init_resources
```
```
In drivers/usb/core/hcd.c (ffff800010a1c628)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/devio.c (ffff800010a2ce1c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a43ff8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4bf6c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5c034)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a69958)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffff800010a705d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7a988)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7dbf8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8a688)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffff800010a92e44)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffff800010a95f7c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffff800010a9c424)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffff800010ac0bac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffff800010aea764)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffff800010afbbc0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffff800010b4ab60)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffff800010bc10e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffff800010bd0160)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffff800010be61b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/link_watch.c (ffff800010bf3e10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffff800010c79b28)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffff800010c947e4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd89a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5d18)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffff800010cf4b34)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffff800010cf54a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffff800010d1bb30)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffff800010d6ca8c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffff800010d79c00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffff800010d8aa94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffff800010d8d258)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/probes/kprobes/opt-arm.c (c0ea132c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/opt-arm.c:arch_optimize_kprobes
```
```
In kernel/exit.c (c035ad28)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c0361ef0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c0368b10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (c0373084)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (c037a040)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (c037e38c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (c0399164)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (c039cb04)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
```
```
In kernel/sched/wait.c (c03a5d68)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (c03a6708)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (c03d7724)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c152118c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (c03f1e18)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
```
```
In kernel/time/posix-cpu-timers.c (c03f9938)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (c03fb558)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (c0402e74)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
```
```
In kernel/cgroup/cgroup.c (c041b494)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (c0420b40)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (c04283cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (c0434ad8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (c0437fbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (c15273ec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (c045687c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
```
```
In kernel/trace/blktrace.c (c04737e4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (c1529f4c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_kprobe.c (c0482d64)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (c048acf8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c048b848)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (c04b9328)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (c04d1234)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (c04d7e60)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (c04f8c90)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/list_lru.c (c0512750)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (c053e8d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (c055789c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (c0560f88)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (c05658d4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (c056f228)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (c05715c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (c0587078)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (c058e09c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (c0598844)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (c059dda0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (c05a7580)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (c05a8658)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (c05b1708)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (c05b89b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (c05c0360)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (c05c0a30)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (c05c4a5c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (c05c7cc0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (c05cb370)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (c05d1788)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c05d4b40)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (c05e2070)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (c05ede10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (c05fa0ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (c061a9f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c240)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dirent
```
```
In fs/configfs/symlink.c (c061e4ec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (c062ee00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/namei.c (c06649c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (c066567c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (c0675098)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (c0691880)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (c06a2278)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (c06bea58)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (c06caf94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (c06e6510)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (c06e83dc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (c06fe340)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (c072bbfc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (c073bbb4)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (c0748880)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (c074b0a0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (c0768540)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (c078b774)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (c0793a78)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (c0794f80)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (c0798460)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (c079dff0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (c07a701c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (c07b2444)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (c07b7d48)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (c07ba5f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (c07bf62c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (c07c3c14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/dynamic_debug.c (c1549454)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (c081197c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pwm/core.c (c087495c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/amba/bus.c (c08e5e0c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_deferred_retry_func
```
```
In drivers/dma/ipu/ipu_idmac.c (c0927640)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
```
In drivers/tty/tty_io.c (c095bbd8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (c09a80f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
```
```
In drivers/iommu/rockchip-iommu.c (c09c6468)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
```
```
In drivers/iommu/exynos-iommu.c (c09c9344)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
```
```
In drivers/base/core.c (c09d5940)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (c09d6bfc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (c09d8534)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (c09da81c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (c09dd1a4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (c09ed7d4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (c09f1854)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (c09f6f30)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/dma-buf/dma-fence.c (c0a3cbac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (c0a40fe0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (c0a48a2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (c0a4cc44)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (c0a4dcec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (c0a8c234)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/mtd/mtd_blkdevs.c (c0a987c0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
```
```
In drivers/spi/spi.c (c0ab2bb4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (c0ac3470)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0c10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_find_ts
  - drivers/net/ethernet/ti/cpts.c:cpts_find_ts
  - drivers/net/ethernet/ti/cpts.c:cpts_systim_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
```
```
In drivers/usb/core/hcd.c (c0af3fbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (c0b02528)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (c0b168a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1e2e4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (c0b2ea0c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (c0b3b5a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (c0b418ec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (c0b4e29c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (c0b50f58)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e100)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/gadget/udc/core.c (c0b7319c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:check_pending_gadget_drivers
```
```
In drivers/input/serio/serio.c (c0b75800)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (c0b78c34)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (c0b7e320)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (c0ba29b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (c0bc5780)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (c0bdc0f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (c0c33730)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5bec0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_done
```
```
In sound/core/init.c (c0c83990)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - sound/core/init.c:snd_disconnect_release
```
```
In sound/core/jack.c (c0c8b4fc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - sound/core/jack.c:snd_jack_dev_free
```
```
In sound/core/timer.c (c0c8bb9c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_dev_disconnect
  - sound/core/timer.c:snd_timer_clear_callbacks
  - sound/core/timer.c:snd_timer_process_callbacks
  - sound/core/timer.c:snd_timer_stop_slave
  - sound/core/timer.c:snd_timer_stop_slave
  - sound/core/timer.c:snd_timer_stop1
  - sound/core/timer.c:snd_timer_stop1
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_close_locked
```
```
In sound/core/pcm.c (c0c9010c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_dev_disconnect
  - sound/core/pcm.c:snd_pcm_dev_register
```
```
In sound/soc/soc-core.c (c0ca0904)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - sound/soc/soc-core.c:soc_cleanup_component
```
```
In sound/soc/soc-dapm.c (c0ca9f3c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_power_widgets
```
```
In net/core/net_namespace.c (c0cdc258)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (c0ce63e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (c0cfea5c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_mark_dead
```
```
In net/core/link_watch.c (c0d0c400)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (c0d8a124)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (c0da30f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (c0de2584)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (c0decdbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (c0dfb7c4)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (c0dfbfd4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (c0e20f98)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (c0e6afec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (c0e755fc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (c0e85258)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (c0e87764)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/optprobes.c (c000000000057dc0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/powerpc/kernel/optprobes.c:arch_optimize_kprobes
```
```
In kernel/exit.c (c000000000144bd0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c00000000014fb18)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c000000000158e88)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (c0000000001672e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/kthread.c (c000000000171be4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (c0000000001776cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (c00000000019da14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (c0000000001a08a8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
```
```
In kernel/sched/wait.c (c0000000001acdf8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (c0000000001ad868)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (c0000000001e3164)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c00000000136ba2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (c00000000020967c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
```
```
In kernel/time/posix-cpu-timers.c (c000000000212e2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (c000000000215300)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (c00000000021f2f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:put_pi_state
```
```
In kernel/cgroup/cgroup.c (c000000000245a10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (c00000000024d494)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (c000000000258cf0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (c000000000269974)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (c00000000026eb10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (c00000000137312c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (c000000000299c24)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (c0000000002c3ca0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (c0000000013767ec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (c0000000002e7824)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (c0000000002eda94)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (c0000000002f9b00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbc80)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (c000000000335258)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (c0000000003532c0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (c00000000035cd94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (c00000000038cdbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (c0000000003b2b68)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (c0000000003fdf20)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (c0000000004432f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (c000000000452b70)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (c000000000466790)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (c00000000046ed2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (c00000000047c8b0)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (c000000000480984)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (c00000000049ee20)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (c0000000004a8f34)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (c0000000004b8348)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (c0000000004c0044)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (c0000000004ccd14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/pnode.c (c0000000004ce55c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (c0000000004dcdc8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (c0000000004e5478)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (c0000000004ef61c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_queued_event
```
```
In fs/notify/mark.c (c0000000004f0150)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5cb4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (c0000000004fa304)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (c0000000004fed38)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (c000000000504b70)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c00000000050dc1c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (c000000000525380)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (c0000000005344f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (c0000000005430f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (c000000000573904)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c000000000575da8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_dirent
```
```
In fs/configfs/symlink.c (c000000000579440)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (c00000000058d954)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/namei.c (c0000000005cf5d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (c0000000005d06f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (c0000000005e4a94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (c000000000607924)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (c0000000006201c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (c000000000646a6c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (c000000000656d04)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (c00000000067a3e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (c00000000067d5a0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (c0000000006ae878)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (c0000000006e6780)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (c0000000006fc424)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (c00000000070d958)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (c00000000071110c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (c0000000007401b0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (c000000000770370)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (c00000000077b5ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (c00000000077d178)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (c000000000781604)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (c000000000788f90)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (c000000000795418)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (c0000000007a3b58)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (c0000000007a9428)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (c0000000007ad554)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (c0000000007b3c94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (c0000000007b86ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (c000000000811f14)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (c0000000013a0900)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (c00000000081e7ec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pwm/core.c (c00000000084e92c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/tty/tty_io.c (c0000000008efe44)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (c000000000943a64)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (c00000000097d614)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (c00000000097ef74)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (c000000000981574)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (c000000000984374)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (c000000000989120)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (c0000000009a1c04)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (c0000000009a90fc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009aeae0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/nvdimm/bus.c (c0000000009fd99c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1d898)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (c000000000a23de4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (c000000000a2dce0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (c000000000a33400)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_del_cmd_from_list
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (c000000000a34c40)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (c000000000a7f290)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (c000000000a8ad58)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (c000000000a9f4e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (c000000000ad6674)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (c000000000aea174)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (c000000000b06c50)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b13010)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b28c14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3a748)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (c000000000b40fd4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (c000000000b524c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (c000000000b56264)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b660fc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (c000000000b6f16c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (c000000000b755bc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (c000000000b7ce88)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (c000000000ba2e0c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (c000000000bcd394)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (c000000000be9a60)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (c000000000c3f004)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (c000000000c9bbe0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (c000000000caceac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (c000000000cc8368)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (c000000000cd9140)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (c000000000d81d00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (c000000000da4ffc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (c000000000df91fc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (c000000000e06e8c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (c000000000e1ab44)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (c000000000e1b6a0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (c000000000e4a454)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (c000000000eaadbc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (c000000000eb94e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (c000000000ecbb70)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (c000000000ecf4c0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c6284)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffe0000cbeb8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffe0000d0df6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffe0000d7630)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffe0000dedd4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffe0000e251c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffe0000f4ccc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffe0000f6a64)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:__delist_rt_entity
```
```
In kernel/sched/wait.c (ffffffe0000fec08)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffe0000ff3c0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffe00011e228)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffe000008596)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffe000132eae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000138300)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffe000139a1e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffe00013d636)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffffffe0001517e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffe0001562b6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffe00015d3c0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffe0001694be)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/trace/ftrace.c (ffffffe00000d5f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffe000176ea2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
```
```
In kernel/trace/blktrace.c (ffffffe00018e808)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/trace_events_trigger.c (ffffffe00000faf4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/bpf/offload.c (ffffffe0001bdd04)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffe0001d049e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffe0001d2ece)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffe0001ecd12)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/list_lru.c (ffffffe000202966)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffe0002272be)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memcontrol.c (ffffffe000244456)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffe00024e67e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffe0002518ea)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffe000258d98)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffe00025be68)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffe00026bd36)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffe000272770)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffe00027cef8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffffffe000281ce6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffe0002890ba)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffe00028a01e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffe00029278c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:__remove_assoc_queue
```
```
In fs/block_dev.c (ffffffe000296db4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffe00029d708)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffe00029e096)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1e3c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffe0002a488c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffe0002a6ef0)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffe0002ac394)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffe0002af316)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffe0002bd5e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffe0002c4428)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffe0002ce4ea)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffe0002e9c8e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffe0002eaf30)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_dirent
```
```
In fs/configfs/symlink.c (ffffffe0002ed784)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffe0002fac28)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffe0003243d4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffe00032507e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffe0003314e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffe00034670c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffe000356982)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffe00036fa44)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffe000379fe8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffe00038f8a0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffe000391804)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffe0003a82b2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffe0003cd55c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffe0003dbaf6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
```
```
In security/apparmor/policy.c (ffffffe0003e40ea)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e65aa)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffe0003fffc6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffe000421198)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffe000427e00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffe000429182)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffe00042bc4c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffe000430872)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffe000437f98)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffe000441ef0)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000445090)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffe000447d42)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffe00044c980)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffe00044eeb6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/dynamic_debug.c (ffffffe00002a6b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffe000494102)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/pwm/core.c (ffffffe0004b11f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/tty/tty_io.c (ffffffe00052e85a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffe0005609b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
```
```
In drivers/base/core.c (ffffffe00057baf6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffe00057ca9e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffe00057e2e2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffe00057fc46)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffe000582268)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/domain.c (ffffffe00058fb24)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe000592a4a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1386)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2cb8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d66f6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dccde)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e050a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e1582)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffe000611c4c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffe000619340)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffe000628cac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffe000640866)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffe00064e072)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffe0006606b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668d8c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00067444a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000684ab4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffe0006866b2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000691fae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006948c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f6b6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffe0006a542e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffe0006a7a16)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffe0006acb38)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c21d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffe0006dea34)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-uevent.c (ffffffe0006ecd92)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffe00071d82a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffe00074de38)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffe00075a1f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffe00076b43c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffe000775442)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffe0007dbf96)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3be6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828ea8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffe000832206)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffe000840878)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffe000840fd8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffe00085fb46)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffe00089f2f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a89c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffe0008b3fe2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffe0008b5efc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016a87)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073034)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a05f3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a88b3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810af5a5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810ba9c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810c27f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810c8d98)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810e549e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810e7b56)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810eea21)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810ef0c1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff8111c1bb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828b80c3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff8113545e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113cabe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff8113e9f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff81144754)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f08a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff811635fb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff8116c2d2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81179548)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8117af60)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828bd5b7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff81196c10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811b1a73)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828bfc77)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c4c8f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c7d37)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811cfe40)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0c01)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (ffffffff811f9f3d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8120f507)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff81215b79)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff8123603e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff8124f635)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8128438d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812b19e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812bb907)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812c9135)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812cd713)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffff812d7e4d)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffff812daaea)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812eff0c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812f5a46)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812ff832)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffffffff813052e5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff8130d58b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff8130e70e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff81319947)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffff8131e39e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff813254ac)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffff81325c55)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8132a23b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8132d797)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81330a79)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffff81334c65)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8133bb19)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff8134c4e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff81357c27)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff81362358)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff81380f5a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813825a2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/symlink.c (ffffffff813845c6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff81393507)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813c3122)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813c3cfb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813d3237)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813ebdef)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff813fcb78)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff81418729)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81423e6d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff8143d55e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8143f3ae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81459264)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff814811d7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8148d5ce)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8149a10c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8149c7c1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff814b8b0e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814d9b6e)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffff814e1362)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814e2812)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814e5ac3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814eac54)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814f29d0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff814fd7bb)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81501ddb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff815048e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff81509a04)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff8150cb05)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff8154b6e0)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828deefe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff815541ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8156805e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff8156b4e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff815d05c5)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d6487)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff816496b3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff81680e59)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff816c211b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff816c335a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff816c4b65)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff816c6932)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff816c952a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff816d8b91)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff816dd8ff)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e0de4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff816f877d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff817057e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171a4db)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e211)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff817251c8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172929b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172a3be)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/nvme/host/core.c (ffffffff81745ead)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_free_ns_head
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81771276)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff8177a340)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff817883ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff817a5a66)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff817b3585)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c3ece)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cb223)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d993f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e7406)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff817eb432)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f4ea9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f7632)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/input/serio/serio.c (ffffffff81807c50)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff8180bd4e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81810f04)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff8182170d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff8183c79a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff8184c85f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8188870b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff818c5e49)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff818d1815)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff818e4d4a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff818f1e12)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff81966091)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff81980864)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbde9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819c590f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819d3bbb)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffff819d42e4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff819f6686)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffff81a3bf44)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a45fd7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81a4f896)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81a51df7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015eb7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810630b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff8108ef4d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81097283)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff8109dee9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810a9304)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810b1040)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810b75b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810d4645)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810d6f10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/sched/wait.c (ffffffff810deab1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810df141)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff8110d297)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828b0343)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff81127ebe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f549)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff81131518)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff81136f7e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffffffff8115231a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8115684b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff8115f4d2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff8116c6e8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff8116e100)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828b5c66)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff81189f00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811a4a13)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828b8317)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b7a6f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bab17)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811c2c10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c39d1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (ffffffff811ecc8d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff812022a1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff812088d9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff8122909e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff812425d5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8127621d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812a2db1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812aca77)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812ba175)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812be583)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffff812c8acd)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffff812cb76a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812e0b3c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812e6666)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812f0452)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffffffff812f5f05)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff812fe19b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff812ff31e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff8130a507)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffff8130ef3e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff8131604c)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffff813167f5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131addb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8131dadd)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81321669)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffff813255f2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8132c7f9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff8133d1c8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff813488d7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff81352ff8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff813719ea)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81373032)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/symlink.c (ffffffff81375056)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff81383f97)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813b3bb2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813b477b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813c3cb7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813dc86f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff813ed5f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff814091a9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff814148ed)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff8142dfce)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8142fe1e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81449c94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff81471bf7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8147dfee)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8148ab2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8148d1e1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff814a952e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814ca51e)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffff814d1cf2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814d31a2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814d5ff7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814db1a4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814e2f00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff814edccb)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f22eb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff814f4da8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff814f9eb4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff814fcf35)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff8153b9c0)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828d761a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff8154442c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81558eae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/acpi/glue.c (ffffffff815ba185)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815c0047)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff81629b13)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff8165ecd9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff8169d3cb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff8169e60a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff8169fde5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff816a1b92)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff816a485a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff816b31d1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff816b7f6f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb424)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/nvdimm/bus.c (ffffffff816d9261)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f393b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f7531)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe5f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff817026cb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff817037de)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/nvme/host/core.c (ffffffff81727b3d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_free_ns_head
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817510c6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff8175a0f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff81767cfc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff81797440)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff817a4fb5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/host/xhci.c (ffffffff817b0542)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ba049)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bc7d2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c94a4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff817cf350)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff817d34be)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff817d8644)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e8dad)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff81803dfa)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff81813e7f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff8184008b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff8187fd89)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8188b69f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff8189eb8a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff818abc42)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff8191fb81)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a324)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978bd9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819826ff)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8199097b)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffff819910a4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff819b3446)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffff819f8b64)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a02bc7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81a0c996)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81a0eef7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016a47)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072fe4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a05a3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a7e13)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810aeb05)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810b9f24)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810c1d40)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810c82c8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810e186e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810e40f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/sched/wait.c (ffffffff810ebb51)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810ec1f1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff8111a0ab)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828cafff)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/time/clocksource.c (ffffffff8113317e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a7de)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff8113c718)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff81142604)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffffffff8115ce5a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff811613cb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff8116a0a2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81177318)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81178d30)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828d033a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811949e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811af843)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828d29fa)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c2a5f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5b07)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811cdc10)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce9d1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (ffffffff811f7d0d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8120d2a7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff81213919)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff81233dde)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff8124d3d5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff8128219d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812af7f1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812b9717)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812c6f45)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812cb523)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffff812d5c5d)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffff812d88fa)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812edd1c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff812f3856)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff812fd622)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffffffff813030d5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff8130b37b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff8130c4fe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff81317417)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffff8131be6e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff81322f7c)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffff81323725)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81327d0b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8132b267)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff8132e549)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffff81332735)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff813395e9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff81349fb8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff813556f7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff8135fe28)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff8137ea2a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81380072)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/symlink.c (ffffffff81382096)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff81390e67)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813c05b2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813c118b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813d06c7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813e916f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff813f9ef8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff814148c9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8142000d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff814396fe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8143b54e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81455304)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff8147d277)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff8148966e)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814961ac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81498861)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff814b4b9e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814d5bfe)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffff814dd3f2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814de8a2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814e1b53)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814e6ce4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff814eea60)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff814f984b)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814fde6b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff81500978)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff81505a94)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff81508b95)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff81547420)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828f1c9d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff8154feec)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81566bce)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff8156a421)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff815d23c5)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815d8877)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff81677a73)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff816af239)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff816f05eb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff816f182a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff816f3035)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff816f4e02)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff816f7a9a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff817064d1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff8170b28f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e4b4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff81725c8c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff817445b1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817592ab)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175cfe1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81763f98)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff8176806b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176918e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817a15d6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff817aa6e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff817b874c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff817e2506)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff817f0025)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180096e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81807cc3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818163df)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81823ea6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81827ed2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81831979)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81834102)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840dd4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff81846d00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff8184aece)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff81850084)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186e64d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff8188bdca)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff8189be8f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff818da3db)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81916e49)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81922815)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff81935d7a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff81942e42)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff819d0861)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb034)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26869)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3038f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81a3e63b)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffff81a3ed64)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81a61106)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffff81aa7df4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab1e87)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81abbc86)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81abe1e7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016c87)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81075044)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In kernel/exit.c (ffffffff810a852e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810aff43)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffff810b6dac)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In kernel/workqueue.c (ffffffff810c2f24)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:destroy_worker
```
```
In kernel/kthread.c (ffffffff810ca320)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
```
```
In kernel/async.c (ffffffff810d07f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/fair.c (ffffffff810ed342)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:account_entity_dequeue
```
```
In kernel/sched/rt.c (ffffffff810f0366)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/wait.c (ffffffff810f6bb1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/swait.c (ffffffff810f7241)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff8112580c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff828d03f8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff81129373)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
```
```
In kernel/time/clocksource.c (ffffffff8113fb9e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114729e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/time/clockevents.c (ffffffff81149076)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/futex.c (ffffffff8114e682)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
```
```
In kernel/cgroup/cgroup.c (ffffffff81169f7a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:css_set_move_task
```
```
In kernel/cgroup/rdma.c (ffffffff8116e81b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
```
```
In kernel/stop_machine.c (ffffffff81177779)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/audit_tree.c (ffffffff81184be8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
```
```
In kernel/kprobes.c (ffffffff81186600)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff828d575b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_command
```
```
In kernel/trace/ring_buffer.c (ffffffff811a25f0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/blktrace.c (ffffffff811bd8c3)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffffffff828d7e1b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:unregister_event_command
```
```
In kernel/trace/trace_events_hist.c (ffffffff811d0aff)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d3d67)
Location: include/linux/list.h:188
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811dbe70)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcc41)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/bpf/offload.c (ffffffff8120628d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
```
In kernel/events/core.c (ffffffff8121c153)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:perf_group_detach
```
```
In kernel/padata.c (ffffffff812228d7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shmem.c (ffffffff812433ae)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/shmem.c:synchronous_wake_function
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/list_lru.c (ffffffff8125cd95)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_isolate
  - mm/list_lru.c:list_lru_del
```
```
In mm/swapfile.c (ffffffff81291e95)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/huge_memory.c (ffffffff812bfb31)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff812c9d97)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
```
```
In mm/zsmalloc.c (ffffffff812d62b3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
```
In mm/hmm.c (ffffffff812dc283)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
```
```
In fs/super.c (ffffffff812e6c7d)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/char_dev.c (ffffffff812e8e7a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
```
```
In fs/dcache.c (ffffffff812fed3c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/dcache.c:d_shrink_del
```
```
In fs/inode.c (ffffffff81304c86)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/inode.c:dispose_list
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8130e980)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:finish_automount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/libfs.c (ffffffff8131414a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs-writeback.c (ffffffff8131cb3b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:sb_clear_inode_writeback
```
```
In fs/pnode.c (ffffffff8131dd2e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/buffer.c (ffffffff81329007)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffff8132dc4e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/block_dev.c:bd_unlink_disk_holder
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/notification.c (ffffffff81334cbc)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/notify/mark.c (ffffffff81335293)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813392cc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
```
```
In fs/eventpoll.c (ffffffff8133c777)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_remove
```
```
In fs/userfaultfd.c (ffffffff81340f79)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/aio.c (ffffffff813458a9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8134be14)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/locks.c (ffffffff8135ccd7)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
  - fs/locks.c:locks_dispose_list
```
```
In fs/mbcache.c (ffffffff81368ce9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/quota/dquot.c (ffffffff813728e6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_commit
```
```
In fs/configfs/inode.c (ffffffff8139252a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81393b62)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/symlink.c (ffffffff81395bba)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
```
```
In fs/ext4/extents_status.c (ffffffff813a4cf7)
Location: include/linux/list.h:188
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813d56e2)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/page-io.c (ffffffff813d62eb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffffffff813e4062)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/commit.c (ffffffff813fea54)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fat/cache.c (ffffffff8140fb38)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fuse/dev.c (ffffffff8142b139)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81436d8d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush_writepages
```
```
In security/keys/key.c (ffffffff814508ee)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/key.c:unregister_key_type
```
```
In security/keys/keyring.c (ffffffff8145269e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/selinux/hooks.c (ffffffff81467894)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/tomoyo/common.c (ffffffff814928f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_answer
```
```
In security/apparmor/apparmorfs.c (ffffffff814a12ce)
Location: include/linux/list.h:188
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814ae23b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814b09b1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/algapi.c (ffffffff814cd61e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_remove_final
```
```
In block/elevator.c (ffffffff814ee8fe)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-flush.c (ffffffff814f6252)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff814f7702)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-softirq.c (ffffffff814faa13)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffffffff814ffc93)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/genhd.c (ffffffff81507b00)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/blk-rq-qos.c (ffffffff815128ab)
Location: include/linux/list.h:188
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8151764b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff815197b8)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-iocost.c (ffffffff8151eb34)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_wake_fn
```
```
In block/mq-deadline.c (ffffffff81522295)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
```
```
In lib/error-inject.c (ffffffff81561270)
Location: include/linux/list.h:188
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff828f709e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
```
```
In lib/sbitmap.c (ffffffff81569d2c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_del_wait_queue
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81580aee)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/pwm/core.c (ffffffff81584921)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
```
In drivers/acpi/glue.c (ffffffff815ec285)
Location: include/linux/list.h:188
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff815f2737)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/tty/tty_io.c (ffffffff81692f13)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
```
In drivers/char/random.c (ffffffff816c9899)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/core.c (ffffffff8170ae2b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/bus.c (ffffffff8170c06a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
```
```
In drivers/base/dd.c (ffffffff8170d865)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_deferred_probe_del
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/class.c (ffffffff8170f692)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
```
```
In drivers/base/devres.c (ffffffff8171233a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
```
```
In drivers/base/power/main.c (ffffffff81720ee1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_remove
```
```
In drivers/base/power/domain.c (ffffffff81724d3f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817290d4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
```
In drivers/block/xen-blkfront.c (ffffffff817410dc)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/nvdimm/bus.c (ffffffff8175fa01)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8177478b)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778411)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f618)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
```
```
In drivers/scsi/scsi_lib.c (ffffffff817837a9)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_scan.c (ffffffff817848fe)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817bb456)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_host_unregister
```
```
In drivers/spi/spi.c (ffffffff817c45b0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/tun.c (ffffffff817d168c)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/usb/core/hcd.c (ffffffff817fc33d)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
```
```
In drivers/usb/core/devio.c (ffffffff8180a265)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_getcompleted
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181aa7e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821dd3)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8183042f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b5e6)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
```
```
In drivers/usb/host/xhci.c (ffffffff81841e8f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184bb59)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184e3f4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b2c4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/input/serio/serio.c (ffffffff818615e0)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffffffff8186611e)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/input.c:input_unregister_handler
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/mousedev.c (ffffffff8186af24)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_disconnect
```
```
In drivers/media/cec/cec-adap.c (ffffffff818885cd)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
```
In drivers/md/md.c (ffffffff818a371a)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:autorun_devices
  - drivers/md/md.c:autorun_devices
```
```
In drivers/md/dm-uevent.c (ffffffff818b804f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/md/dm-uevent.c:dm_send_uevents
```
```
In drivers/leds/led-triggers.c (ffffffff818f6efb)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
```
In net/core/net_namespace.c (ffffffff81938059)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff819439e5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:dev_close_many
```
```
In net/core/neighbour.c (ffffffff819574b5)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (ffffffff81964732)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_input.c (ffffffff819da3f1)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f4eb4)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31d19)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3bc8f)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81a4a0f9)
Location: include/linux/list.h:188
Inline: True
```
```
In net/unix/scm.c (ffffffff81a4a822)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6d5ca)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/rfkill/core.c (ffffffff81ab4194)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abe237)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
```
```
In lib/kobject.c (ffffffff81ac8116)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/plist.c (ffffffff81aca687)
Location: include/linux/list.h:188
Inline: True
Inline callers:
  - lib/plist.c:plist_del
  - lib/plist.c:plist_del
```
</details>
</li>
</ul>

## Differences
