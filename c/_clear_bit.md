# Function: <code>_clear_bit</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/elf.c:elf_set_personality
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_clear_event_idx
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_clear_event_idx
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_get_event_idx
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_clear_event_idx
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_clear_event_idx
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_get_event_idx
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
  - arch/arm/mach-imx/platsmp.c:imx_smp_init_cpus
  - arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/exit.c:release_task
  - kernel/softirq.c:tasklet_kill
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:flush_signals
  - kernel/sys.c:__se_sys_prctl
  - kernel/kthread.c:kthread_unpark
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/topology.c:rq_attach_root
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/chip.c:irq_percpu_disable
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/profile.c:profile_dead_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/cpuset.c:cpuset_css_offline
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/auditsc.c:audit_alloc
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/trace/trace.c:trace_filter_add_remove_task
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:xol_free_insn_slot
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/oom_kill.c:exit_oom_victim
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/rmap.c:page_referenced_one
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:drain_all_pages
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/frontswap.c:__frontswap_invalidate_page
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:drain_local_stock
  - mm/zsmalloc.c:reset_page
  - mm/zsmalloc.c:reset_page
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/coredump.c:do_coredump
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_decr_space
  - fs/quota/dquot.c:dquot_decr_inodes
  - fs/quota/dquot.c:dquot_release
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
  - fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/fuse/dev.c:end_requests
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - security/keys/gc.c:key_garbage_collector
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - block/blk-core.c:blk_queue_flag_clear
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq-sched.c:blk_mq_sched_restart
  - lib/irq_poll.c:irq_poll_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
  - drivers/gpio/gpiolib.c:gpiochip_disable_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
  - drivers/pci/controller/pci-tegra.c:tegra_msi_free
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_teardown_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-ast2600.c:aspeed_cc_g6_of_clk_init_driver
  - drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver
  - drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_of_clk_init_driver
  - drivers/clk/meson/meson8b.c:meson8m2_clkc_of_clk_init_driver
  - drivers/clk/meson/meson8b.c:meson8b_clkc_of_clk_init_driver
  - drivers/clk/meson/meson8b.c:meson8_clkc_of_clk_init_driver
  - drivers/clk/renesas/r7s9210-cpg-mssr.c:cpg_mstp_clks_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos5250.c:exynos5250_clk_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos5420.c:exynos5800_clk_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos5420.c:exynos5420_clk_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos5250_clkout_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos4210_clkout_of_clk_init_driver
  - drivers/dma/dmaengine.c:dma_release_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/ti/edma.c:edma_free_slot
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_free
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/tty_ioctl.c:tty_unthrottle_safe
  - drivers/tty/tty_ldisc.c:tty_ldisc_close
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_ldisc.c:tty_ldisc_unlock
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/keyboard.c:kbd_keycode
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/char/misc.c:misc_deregister
  - drivers/char/misc.c:misc_register
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_open
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_free_context
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/dax/super.c:dax_write_cache
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/ata/libata-scsi.c:ata_sas_free_tag
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/net/tun.c:tun_net_open
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:tun_attach
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_resume_data_pass
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/devio.c:driver_disconnect
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_resume_noirq
  - drivers/media/cec/cec-core.c:cec_devnode_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:dm_cancel_deferred_remove
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_handle_poke
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:led_blink_set
  - drivers/leds/led-core.c:set_brightness_delayed
  - drivers/leds/led-core.c:led_timer_function
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
  - drivers/firmware/arm_scmi/driver.c:scmi_version_get
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
  - drivers/of/dynamic.c:__of_attach_node
  - drivers/of/irq.c:of_irq_init
  - drivers/perf/arm-cci.c:cci_pmu_del
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - sound/core/init.c:snd_card_disconnect
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_write_space
  - net/core/dev.c:napi_disable
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:__dev_open
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_poll_dev
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_output.c:tcp_tasklet_func
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
c0e7c094-c0e7c0cc: _clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
