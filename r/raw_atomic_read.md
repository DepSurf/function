# Function: <code>raw_atomic_read</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810083da)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/events/intel/core.c (ffffffff810104c0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024d01)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102728f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102baa5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/xen/smp.c (ffffffff81043816)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/spinlock.c (ffffffff8104486e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/irq.c (ffffffff810513b5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:arch_irq_stat
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/ioport.c (ffffffff81051d65)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8105218d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e241)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8105e300)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81060f03)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/tboot.c (ffffffff8106961c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213ed77)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c24a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff836a26d5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81087fa7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931ce)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096e6c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8109a6b9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b204)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/smp.c (ffffffff8109b62c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad4e4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f7ae)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109fa35)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a29b6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/ftrace.c (ffffffff810adef4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b6261)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff810b785a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/tlb.c (ffffffff810cbeeb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff836c0645)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d71da)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:mmiotrace_printk
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8e86)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/fork.c (ffffffff810f57ef)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:free_task
  - kernel/fork.c:vm_area_dup
```
```
In kernel/panic.c (ffffffff810f5b27)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:warn_count_show
```
```
In kernel/cpu.c (ffffffff810fa557)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/exit.c (ffffffff810fd3a7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:oops_count_show
```
```
In kernel/softirq.c (ffffffff810ffe01)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In kernel/umh.c (ffffffff8111bc1a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
```
```
In kernel/workqueue.c (ffffffff8111c787)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/cred.c (ffffffff81133dc0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:get_task_cred
  - kernel/cred.c:__put_cred
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/async.c (ffffffff811362c0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/sched/core.c (ffffffff8114e3d3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff81166484)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_policy.c (ffffffff81169de4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:account_idle_ticks
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8117eb05)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_get_registrations
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:membarrier_update_current_mm
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/locking/mutex.c (ffffffff8118db45)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155bcb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/spinlock.c (ffffffff82158e5c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/osq_lock.c (ffffffff8118ee3c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff82159b0b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8215a13a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81194025)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/power/swap.c (ffffffff8119af1d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/power/swap.c:hib_wait_io
```
```
In kernel/printk/printk.c (ffffffff8119e91b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_wait
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
```
```
In kernel/irq/manage.c (ffffffff811ab7a7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:synchronize_irq
```
```
In kernel/irq/spurious.c (ffffffff811abc99)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
```
```
In kernel/irq/chip.c (ffffffff811ae204)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/irq/migration.c (ffffffff811b474b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/rcu/update.c (ffffffff811ba843)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_gp_is_expedited
```
```
In kernel/rcu/tree.c (ffffffff811c89b7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/rcu/tree.c:rcu_dynticks_zero_in_eqs
  - kernel/rcu/tree.c:rcu_dynticks_zero_in_eqs
```
```
In kernel/module/main.c (ffffffff811da38e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:show_refcnt
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:trace_event_raw_event_module_refcnt
```
```
In kernel/stacktrace.c (ffffffff811e6cdf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/clocksource.c (ffffffff811f4adf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81202e95)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/futex/core.c (ffffffff81207a20)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a71c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/futex/requeue.c (ffffffff8120bd46)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff8120c665)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake
```
```
In kernel/smp.c (ffffffff836d3cd1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ed39)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
```
```
In kernel/cgroup/rstat.c (ffffffff81227017)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229714)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
```
In kernel/stop_machine.c (ffffffff8123a36c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/audit.c (ffffffff8123dd77)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_lost
```
```
In kernel/audit_tree.c (ffffffff8124a04d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff81251476)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/debug/gdbstub.c (ffffffff81252e91)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81256ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff8125d542)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/watchdog.c (ffffffff8125e7d5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/seccomp.c (ffffffff81262229)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/trace/trace_clock.c (ffffffff8126811e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81273d99)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_record_is_set_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_is_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace.c (ffffffff8127c124)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_save_cmdline
```
```
In kernel/trace/trace_functions.c (ffffffff812919f2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/blktrace.c (ffffffff8129e19a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_dropped_read
```
```
In kernel/trace/fgraph.c (ffffffff812a1ec3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_return_to_handler
```
```
In kernel/trace/trace_events_hist.c (ffffffff812ba129)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/trace_events_user.c (ffffffff812c71d5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_event_free
  - kernel/trace/trace_events_user.c:user_event_is_busy
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8d17)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/trace/rpm-traces.c (ffffffff812d5732)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
  - kernel/trace/rpm-traces.c:trace_event_raw_event_rpm_internal
  - kernel/trace/rpm-traces.c:trace_event_raw_event_rpm_internal
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d6250)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_busy
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/trace/rethook.c (ffffffff812deb27)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
  - kernel/trace/rethook.c:rethook_try_get
```
```
In kernel/irq_work.c (ffffffff812e5080)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/helpers.c (ffffffff81321354)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/task_iter.c (ffffffff81324629)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/hashtab.c (ffffffff81326aaf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff813359db)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81348c82)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/memalloc.c (ffffffff8134bf5d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
```
```
In kernel/bpf/devmap.c (ffffffff8134cd1a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_mem_usage
```
```
In kernel/bpf/offload.c (ffffffff8135128e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In kernel/bpf/net_namespace.c (ffffffff813537bc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff813550e5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c831)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff8137b692)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_text_poke
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:perf_event_comm
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137cc31)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/callchain.c (ffffffff8137d9e1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/events/callchain.c:perf_event_max_stack_handler
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137fb9e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In kernel/events/uprobes.c (ffffffff813834d6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:uprobe_munmap
  - kernel/events/uprobes.c:build_map_info
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff81386bac)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In kernel/context_tracking.c (ffffffff82142086)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
```
```
In mm/filemap.c (ffffffff8138be10)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/oom_kill.c (ffffffff8139603b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_killer_disable
```
```
In mm/page-writeback.c (ffffffff8139cb84)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/swap.c (ffffffff813a31e6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff813a387e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813b253d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813c0803)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/vmstat.c (ffffffff813c813a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/compaction.c (ffffffff813daea3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/list_lru.c (ffffffff813dffce)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/debug.c (ffffffff813e1fb7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e7e0a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f12e9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813f94c8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff8140025f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mmu_gather.c (ffffffff81401ed2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff81402cb5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff8140952e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8140bb9a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/rmap.c:set_tlb_ubc_flush_pending
  - mm/rmap.c:set_tlb_ubc_flush_pending
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/vmalloc.c (ffffffff81410df5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (ffffffff81423c28)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_page_is_bad_report
  - mm/page_alloc.c:free_page_is_bad_report
```
```
In mm/memory_hotplug.c (ffffffff82147a8a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427ada)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_update_vma
```
```
In mm/swap_state.c (ffffffff8142d106)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8142dac7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_open
  - mm/swapfile.c:swaps_poll
  - mm/swapfile.c:swaps_poll
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__del_from_avail_list
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (ffffffff814347dd)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81436cdc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff814464e3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff814494dc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/mmu_notifier.c (ffffffff8144f4fd)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8145531d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_cow
```
```
In mm/slub.c (ffffffff8145a259)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/core.c (ffffffff814659be)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/migrate.c (ffffffff8146bbd1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e4f2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147932c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:shrink_huge_zero_page_count
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81480ba2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff81484d2a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
  - mm/memcontrol.c:obj_cgroup_release
```
```
In mm/memory-failure.c (ffffffff81497422)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff8149b1f3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zpool.c (ffffffff8149b409)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/zpool.c:zpool_unregister_driver
```
```
In mm/zsmalloc.c (ffffffff8149ed8d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814a00d4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/secretmem.c:secretmem_active
```
```
In mm/userfaultfd.c (ffffffff814a26c3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814a283f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814a62e2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63a7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In mm/page_reporting.c (ffffffff814a76aa)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/open.c (ffffffff814a87d3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814b1243)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/super.c (ffffffff814b34e4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff814b8635)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
  - fs/exec.c:do_open_execat
```
```
In fs/pipe.c (ffffffff814bcdf7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c1f0e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/dcache.c (ffffffff814d3d37)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff814d6d42)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:inode_add_lru
```
```
In fs/file.c (ffffffff814dc109)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
```
In fs/fs-writeback.c (ffffffff814f6ea5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/kernel_read_file.c (ffffffff815063c1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/buffer.c (ffffffff81509957)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/fsnotify.c (ffffffff815130eb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/notification.c (ffffffff81513a8f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/group.c (ffffffff81513e26)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/mark.c (ffffffff81514d2f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/dnotify/dnotify.c (ffffffff815163cc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516fb5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81518025)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c837)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/userfaultfd.c (ffffffff81526213)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff81528d84)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/aio.c:read_events
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_ring_mremap
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff815306aa)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/crypto/crypto.c (ffffffff836efa05)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/crypto/keyring.c (ffffffff815368ca)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/verity/enable.c (ffffffff8153c008)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/verify.c (ffffffff836efd15)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/locks.c (ffffffff8153f9c9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:trace_event_raw_event_generic_add_lease
  - fs/locks.c:trace_event_raw_event_generic_add_lease
  - fs/locks.c:trace_event_raw_event_generic_add_lease
```
```
In fs/mbcache.c (ffffffff8154c63d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (ffffffff8154d493)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/iomap/buffered-io.c (ffffffff815559a6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/quota/dquot.c (ffffffff8155de02)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff81565c19)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81568c2a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156ae0a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/generic.c (ffffffff8157108e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
```
```
In fs/proc/array.c (ffffffff815743e8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_seccomp
```
```
In fs/proc/meminfo.c (ffffffff81576ba5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/stat.c (ffffffff81577265)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/proc/proc_sysctl.c (ffffffff8157a398)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
```
```
In fs/proc/proc_net.c (ffffffff8157c840)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/proc/page.c (ffffffff8157fb1d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/kernfs/dir.c (ffffffff81582a04)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_get_active
  - fs/kernfs/dir.c:kernfs_get_parent
```
```
In fs/kernfs/file.c (ffffffff81585427)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_should_drain_open_files
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_show
```
```
In fs/configfs/inode.c (ffffffff81588b66)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158a99c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8158d05f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/configfs/item.c (ffffffff8158d686)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8158fdb9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/file.c (ffffffff815a162a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff815a8c89)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b04ea)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff815cd4d5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
  - fs/ext4/mballoc.c:ext4_mb_pa_put_free
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_callback
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81600e35)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/sysfs.c (ffffffff81604ce7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/fast_commit.c (ffffffff8160eab2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff8161117f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_empty
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/transaction.c (ffffffff81616544)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81617c2b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81619f55)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff81623bd7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/squashfs/decompressor_multi.c (ffffffff8162aa75)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_max_decompressors
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebd6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164e895)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81655c61)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8165c2fc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff81662ffb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/control.c (ffffffff81665aaa)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_waiting_read
```
```
In fs/fuse/dax.c (ffffffff8166a1f1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/file.c (ffffffff8166ceb5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_get
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816752cd)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/sem.c (ffffffff8167d830)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In ipc/shm.c (ffffffff81680018)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff81686161)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff816883a9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8168a286)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff8169160a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/selinux/avc.c (ffffffff816a56bd)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In security/selinux/hooks.c (ffffffff816aeac5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
```
```
In security/tomoyo/common.c (ffffffff816e63ee)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/tomoyo/condition.c (ffffffff816e7107)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff816ed619)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff816ee51c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff816f817a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816fbb30)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff817049a1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff817074de)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0f2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In security/apparmor/procattr.c (ffffffff8170c534)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff836f88f9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff81714a80)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff817170b6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8171a9d6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171e444)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8172000a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8172120d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff8172425a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff81726835)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/fs.c (ffffffff8172d99b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In security/integrity/ima/ima_main.c (ffffffff8172fe14)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_check_last_writer
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8173a8aa)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
```
In crypto/algapi.c (ffffffff81740750)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff81741522)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In crypto/ahash.c (ffffffff81744c9e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817461b3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e1f4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
```
```
In block/bdev.c (ffffffff81767243)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/bdev.c:sync_bdevs
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_get_whole
```
```
In block/bio.c (ffffffff8176a2f5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
```
```
In block/blk-core.c (ffffffff81771549)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-flush.c (ffffffff81774fc6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8177dc65)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81786e4d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
```
In block/partitions/core.c (ffffffff8179133f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_del_partition
```
```
In block/blk-rq-qos.c (ffffffff8179bfb5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/bsg-lib.c (ffffffff8179e9dc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In block/blk-cgroup.c (ffffffff817a2d2a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-iocost.c (ffffffff817afbb0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:current_hweight
```
```
In block/mq-deadline.c (ffffffff817b13cc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
```
In block/blk-wbt.c (ffffffff817b9f20)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_show
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
```
In block/blk-mq-debugfs.c (ffffffff817bb4d8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
  - block/blk-mq-debugfs.c:hctx_active_show
  - block/blk-mq-debugfs.c:queue_pm_only_show
```
```
In block/blk-crypto-profile.c (ffffffff817c4192)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
```
```
In block/blk-crypto-fallback.c (ffffffff817c49a2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/io_uring.c (ffffffff817d32c4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wake_function
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_put_task_remote
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/timeout.c (ffffffff817daf1b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff817dbb6f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In io_uring/tctx.c (ffffffff817dcc5a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff817de45c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_can_finish_inline
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/io-wq.c (ffffffff817e7ccf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/lockref.c (ffffffff8180a3c4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_mark_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_put_return
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/rhashtable.c (ffffffff818197ef)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/refcount.c (ffffffff8181aa50)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
```
```
In lib/rcuref.c (ffffffff8181ad60)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
```
```
In lib/percpu_counter.c (ffffffff818ce2d5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/syscall.c (ffffffff818ce940)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/sbitmap.c (ffffffff818e586c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff818e9cc4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908c43)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
```
```
In drivers/pci/pci.c (ffffffff81924f78)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pci_enable_bridge
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac29)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192c5d9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:enable_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/setup-bus.c (ffffffff81935900)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/pcie/aer.c (ffffffff8193e8e4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:find_device_iter
```
```
In drivers/pci/slot.c (ffffffff81944797)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff819508fb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952f5c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819546e1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
```
In drivers/video/console/dummycon.c (ffffffff81975565)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197ae58)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197eada)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:framebuffer_release
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81983875)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
```
In drivers/acpi/acpi_processor.c (ffffffff819abd90)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff82143df9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a3048f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff81a3f353)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e2b2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/grant-table.c (ffffffff81a623a7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/events/events_base.c (ffffffff81a66987)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:select_target_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a72ab9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:jiffies_eoi_delayed_show
  - drivers/xen/xenbus/xenbus_probe.c:spurious_events_show
  - drivers/xen/xenbus/xenbus_probe.c:events_show
  - drivers/xen/xenbus/xenbus_probe.c:event_channels_show
```
```
In drivers/reset/core.c (ffffffff81a9150c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f1b5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_space_avail
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa7404)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81aa7db5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/tty/vt/vt.c (ffffffff81ab6c85)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba3f5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe7b2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81ada960)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
```
In drivers/tty/serdev/core.c (ffffffff81adbbe0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81ae71c8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81ae827a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_acquire
```
```
In drivers/char/agp/generic.c (ffffffff81aea0f7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_copy_info
  - drivers/char/agp/generic.c:agp_allocate_memory
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0beda)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23a97)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/iommu/iova.c (ffffffff81b26b35)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b28323)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0a4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/connector/cn_queue.c (ffffffff81b2aef8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_free_dev
```
```
In drivers/connector/cn_proc.c (ffffffff81b2c0bf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/core.c (ffffffff81b3352b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff81b39065)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:driver_probe_done
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a3ca)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:runtime_active_kids_show
  - drivers/base/power/sysfs.c:runtime_usage_show
```
```
In drivers/base/power/runtime.c (ffffffff81b50311)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/runtime.c:rpm_check_suspend_allowed
  - drivers/base/power/runtime.c:rpm_check_suspend_allowed
```
```
In drivers/base/power/main.c (ffffffff81b52f77)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/wakeup.c (ffffffff81b575e6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_save_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_wakeup_pending
```
```
In drivers/base/power/domain.c (ffffffff81b5bcc0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/block/loop.c (ffffffff81b7b9c1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/block/xen-blkfront.c (ffffffff8371e555)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4c97)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba5a4c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
```
```
In drivers/nvdimm/region.c (ffffffff81babd20)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/security.c (ffffffff81bb832e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bbffd8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_signaled
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc08d7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1f00)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5cdd)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/cxl/core/suspend.c (ffffffff81bc7145)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active
```
```
In drivers/scsi/scsi.c (ffffffff81bc950d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81bcab94)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd0db5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd79aa)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bd98d9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:show_iostat_iotmo_cnt
  - drivers/scsi/scsi_sysfs.c:show_iostat_ioerr_cnt
  - drivers/scsi/scsi_sysfs.c:show_iostat_iodone_cnt
  - drivers/scsi/scsi_sysfs.c:show_iostat_iorequest_cnt
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_blocked
```
```
In drivers/scsi/sr.c (ffffffff81bee93d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
```
```
In drivers/scsi/sg.c (ffffffff81bf2427)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
```
```
In drivers/spi/spi.c (ffffffff81c2e547)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fe2c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c4659b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/virtio_net.c (ffffffff81c51bf8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83af4ac0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff83720fe2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
  - drivers/net/xen-netfront.c:xennet_get_ethtool_stats
```
```
In drivers/cdrom/cdrom.c (ffffffff81c73c05)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c80987)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c852c8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/urb.c (ffffffff81c89222)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff81c8dad1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/sysfs.c (ffffffff81c93a49)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:urbnum_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f7c4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb814f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5fd5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d3712e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d3764a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3dab5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_external_power_changed
  - drivers/power/supply/power_supply_core.c:power_supply_property_is_writeable
  - drivers/power/supply/power_supply_core.c:power_supply_set_property
  - drivers/power/supply/power_supply_core.c:power_supply_set_battery_charged
```
```
In drivers/thermal/thermal_core.c (ffffffff81d49061)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52f75)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:x86_thermal_enabled
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/md/md.c (ffffffff81d60cce)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:mdstat_poll
  - drivers/md/md.c:md_seq_open
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:status_resync
  - drivers/md/md.c:status_resync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:sync_speed_show
  - drivers/md/md.c:max_corrected_read_errors_show
  - drivers/md/md.c:errors_show
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81d71578)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81d7a478)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_get_event_nr
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_lock_for_deletion
```
```
In drivers/md/dm-stripe.c (ffffffff81d7ee42)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
  - drivers/md/dm-stripe.c:stripe_status
  - drivers/md/dm-stripe.c:stripe_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81d81785)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
  - drivers/md/dm-ioctl.c:dm_open
  - drivers/md/dm-ioctl.c:dev_arm_poll
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84668)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
```
In drivers/md/dm-stats.c (ffffffff81d875cd)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/md/dm-stats.c:dm_stats_cleanup
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8df29)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:instance_npe_count_show
  - drivers/edac/edac_pci_sysfs.c:instance_pe_count_show
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ec33)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9dfe3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3d68)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/mmc/core/core.c (ffffffff81db125e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc2fb4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a9e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81dcb7c8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/firmware/efi/efi.c (ffffffff82148a07)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de327a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/ras/debugfs.c (ffffffff81df86c5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:ras_userspace_consumers
```
```
In net/core/sock.c (ffffffff81e0e5eb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/request_sock.c (ffffffff81e0fb43)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81e14c20)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81e200e7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81e23ad0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e371cc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/neighbour.c (ffffffff81e45a71)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_show
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/rtnetlink.c (ffffffff81e59422)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/filter.c (ffffffff81e701c8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e77289)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (ffffffff81e78dcf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/core/gso.c (ffffffff81e7d7d0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/net-sysfs.c (ffffffff81e81b4c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:carrier_down_count_show
  - net/core/net-sysfs.c:carrier_up_count_show
  - net/core/net-sysfs.c:carrier_changes_show
  - net/core/net-sysfs.c:carrier_changes_show
```
```
In net/core/page_pool.c (ffffffff81e82922)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/netpoll.c (ffffffff81e85916)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e87542)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81e91caf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh_create
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_rcvqueue_full
```
```
In net/core/selftests.c (ffffffff81e9bdfb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81e9ef5d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81e9fa3f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81ea3277)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/core/sock_map.c (ffffffff81ea6165)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_mem_usage
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea88cf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81eae65b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_frag.c (ffffffff81eaf5c7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_api.c (ffffffff81eb2214)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81eb8f5b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81ebe511)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
```
In net/netlink/af_netlink.c (ffffffff83734358)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netlink/genetlink.c (ffffffff81ecc45a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9934)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ef2aec)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81ef30d8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81ef3d62)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5cda)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6518)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81efc1e5)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02551)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04bf1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06e4f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81f101d7)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81f18fdf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f28e6e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:skb_still_in_host_queue
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81f294bb)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ba3f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32881)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_twsk_purge
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f3558e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f388f0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38a9d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3b61f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3ed5d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81f49c4c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff81f4c164)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/devinet.c (ffffffff81f4e13c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv4/af_inet.c (ffffffff81f54c74)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5dfc1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63d09)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69a70)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ping.c (ffffffff81f6ae6b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6eee6)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/nexthop.c (ffffffff81f74e23)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/proc.c (ffffffff81f78f80)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff81f7bd65)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/syncookies.c (ffffffff81f85032)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87466)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88319)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8ac0a)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b5b2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9077d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a9a3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1965)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa806f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff81fa8e96)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_show_fdinfo
  - net/unix/af_unix.c:unix_show_fdinfo
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff81fb0ad9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb8109)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbdb3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81fbd513)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/route.c (ffffffff81fccba8)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdaa47)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ndisc.c (ffffffff81fe6c6c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
```
```
In net/ipv6/udp.c (ffffffff81fe7ba3)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81feceef)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa5d0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ping.c (ffffffff81fff631)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
```
In net/ipv6/exthdrs.c (ffffffff82001dd2)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff82004975)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8200572b)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ioam6.c (ffffffff8200a354)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200ff10)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/xfrm6_input.c (ffffffff820124b0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff82013ed4)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/proc.c (ffffffff8201566c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/syncookies.c (ffffffff8201681f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff82017d39)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a59f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201bbbf)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201fa87)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020dd9)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_icmp.c (ffffffff82022200)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/ip6_offload.c (ffffffff82022e15)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202476f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff8202787e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:__packet_rcv_has_room
  - net/packet/af_packet.c:prb_retire_current_block
```
```
In net/devlink/leftover.c (ffffffff8203e450)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_del_doit
```
```
In net/devlink/core.c (ffffffff82042264)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/strparser/strparser.c (ffffffff82048db1)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8204a50e)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/netlabel/netlabel_kapi.c (ffffffff8204e245)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_enabled
```
```
In net/rfkill/core.c (ffffffff82057853)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_remove_epo_lock
  - net/rfkill/core.c:rfkill_restore_states
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:rfkill_switch_all
```
```
In net/xdp/xsk.c (ffffffff8206a836)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xskmap.c (ffffffff8206cd75)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_mem_usage
```
```
In net/mptcp/protocol.c (ffffffff82073c7d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:mptcp_rfree
```
```
In net/mptcp/subflow.c (ffffffff8207b85f)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff8207df5d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_dss
```
```
In net/mptcp/token.c (ffffffff8207fbac)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/af_mctp.c (ffffffff8208dc64)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff8208e87d)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff82091084)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In net/handshake/request.c (ffffffff82092dbc)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In lib/bug.c (ffffffff8209ebd0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
```
In lib/cpumask.c (ffffffff8209f8d0)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/dec_and_lock.c (ffffffff8209fb60)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/is_single_threaded.c (ffffffff820a189c)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/is_single_threaded.c:current_is_single_threaded
  - lib/is_single_threaded.c:current_is_single_threaded
```
```
In lib/klist.c (ffffffff820a1d51)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
```
```
In lib/kobject.c (ffffffff820a2861)
Location: include/linux/atomic/atomic-arch-fallback.h:442
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/entry/common.c (ffffffff8221b9a7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff8100dafa)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/events/intel/core.c (ffffffff81015c00)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102ae61)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_constraint
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102d3ef)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_get_constraint
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_get_shared_reg
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81031c05)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pcu_get_constraint
  - arch/x86/events/intel/uncore_snbep.c:__snbep_cbox_get_constraint
```
```
In arch/x86/xen/smp.c (ffffffff81049d16)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/spinlock.c (ffffffff8104ad9e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_qlock_wait
```
```
In arch/x86/kernel/irq.c (ffffffff810585e5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:arch_irq_stat
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
```
```
In arch/x86/kernel/ioport.c (ffffffff81058f85)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810593ad)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff82220231)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff810653c0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81067fb3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/tboot.c (ffffffff81070a8c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220d97)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff838d27d5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108f087)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a63e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e3dc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810a1ee9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2844)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/smp.c (ffffffff810a2bec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff838ddb43)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6c3e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a6f9a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a962f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/ftrace.c (ffffffff810b4a74)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bd6a1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_nmi_handler
```
```
In arch/x86/kernel/hpet.c (ffffffff810bec9a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/tlb.c (ffffffff810d457b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff838f1165)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810dfa3a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:mmiotrace_printk
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1107)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
```
In kernel/fork.c (ffffffff810feb9f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:free_task
  - kernel/fork.c:vm_area_dup
```
```
In kernel/panic.c (ffffffff810feed7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:warn_count_show
```
```
In kernel/cpu.c (ffffffff81103977)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/exit.c (ffffffff81106217)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:oops_count_show
```
```
In kernel/softirq.c (ffffffff81109521)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In kernel/umh.c (ffffffff8112573a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:__usermodehelper_disable
```
```
In kernel/workqueue.c (ffffffff81126117)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/async.c (ffffffff811415df)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_dev_nocall
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/sched/core.c (ffffffff8115a213)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff8116f945)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_policy.c (ffffffff81177484)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:vtime_task_switch_generic
  - kernel/sched/build_policy.c:account_idle_ticks
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:pull_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8118fa90)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_update_current_mm
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/locking/mutex.c (ffffffff8119c4f5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238a0b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/spinlock.c (ffffffff8223c6dc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/osq_lock.c (ffffffff8119d7ec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d38b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8223d9ba)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811a2a15)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/power/swap.c (ffffffff811a8fa0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:hib_wait_io
  - kernel/power/swap.c:hib_wait_io
```
```
In kernel/printk/printk.c (ffffffff811adadb)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/printk/printk.c:__printk_cpu_sync_wait
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
  - kernel/printk/printk.c:console_trylock_spinning
```
```
In kernel/printk/nbcon.c (ffffffff811b3987)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:__nbcon_context_update_unsafe
  - kernel/printk/nbcon.c:nbcon_can_proceed
  - kernel/printk/nbcon.c:nbcon_context_can_proceed
```
```
In kernel/irq/manage.c (ffffffff811bb3a7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
```
```
In kernel/irq/spurious.c (ffffffff811bb899)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
```
```
In kernel/irq/chip.c (ffffffff811bde04)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/irq/migration.c (ffffffff811c45cb)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/rcu/update.c (ffffffff811ca773)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_gp_is_expedited
  - kernel/rcu/update.c:rcu_async_should_hurry
```
```
In kernel/rcu/tree.c (ffffffff811d3f1f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:param_get_do_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_dynticks_zero_in_eqs
  - kernel/rcu/tree.c:rcu_dynticks_zero_in_eqs
```
```
In kernel/entry/common.c (ffffffff82223d5c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter_from_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_prepare
  - kernel/entry/common.c:syscall_enter_from_user_mode_prepare
```
```
In kernel/module/main.c (ffffffff811f003e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:show_refcnt
  - kernel/module/main.c:perf_trace_module_refcnt
  - kernel/module/main.c:trace_event_raw_event_module_refcnt
```
```
In kernel/stacktrace.c (ffffffff811fca2f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/clocksource.c (ffffffff8120ac1f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81219455)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8121ca51)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_task_switch
  - kernel/time/tick-sched.c:__tick_nohz_task_switch
  - kernel/time/tick-sched.c:check_tick_dependency
```
```
In kernel/futex/core.c (ffffffff8121ec30)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff81221c7c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/futex/requeue.c (ffffffff812232db)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
```
```
In kernel/futex/waitwake.c (ffffffff81223a42)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake
```
```
In kernel/smp.c (ffffffff83905cb1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/cgroup/cgroup.c (ffffffff812369c9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_advance
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
```
```
In kernel/cgroup/rstat.c (ffffffff8123ed95)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81241564)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
```
In kernel/stop_machine.c (ffffffff8125403c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/audit.c (ffffffff81257c95)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_lost
```
```
In kernel/audit_tree.c (ffffffff81263f5d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff8126b2c6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/debug/gdbstub.c (ffffffff8126cd01)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81270975)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_debugger.c (ffffffff81277482)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/watchdog.c (ffffffff8127876a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/seccomp.c (ffffffff8127c469)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_poll
  - kernel/seccomp.c:recv_wait_event
  - kernel/seccomp.c:recv_wait_event
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/trace/trace_clock.c (ffffffff8128238e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e3ac)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_record_is_set_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_is_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace.c (ffffffff81296e14)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:trace_save_cmdline
```
```
In kernel/trace/trace_functions.c (ffffffff812ad002)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/blktrace.c (ffffffff812b987a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_dropped_read
```
```
In kernel/trace/fgraph.c (ffffffff812bd5f3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_return_to_handler
```
```
In kernel/trace/trace_events.c (ffffffff812c3110)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_file_put
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d6779)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3b65)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl
  - kernel/trace/trace_events_user.c:user_event_free
  - kernel/trace/trace_events_user.c:user_event_is_busy
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5ce7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/trace/rpm-traces.c (ffffffff812f3242)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
  - kernel/trace/rpm-traces.c:trace_event_raw_event_rpm_internal
  - kernel/trace/rpm-traces.c:trace_event_raw_event_rpm_internal
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3d60)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_busy
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/irq_work.c (ffffffff81303130)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/helpers.c (ffffffff813439e4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/task_iter.c (ffffffff81349875)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
```
```
In kernel/bpf/hashtab.c (ffffffff8134b0ff)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8135a03b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136f3b2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/memalloc.c (ffffffff81371dde)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
```
```
In kernel/bpf/devmap.c (ffffffff8137423b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_mem_usage
```
```
In kernel/bpf/offload.c (ffffffff813786ee)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In kernel/bpf/net_namespace.c (ffffffff8137acac)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
```
In kernel/bpf/stackmap.c (ffffffff8137dab5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385b2f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/events/core.c (ffffffff813a4892)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:account_event
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_text_poke
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:perf_event_comm
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_event_fork
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a5e91)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/callchain.c (ffffffff813a6c41)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/events/callchain.c:perf_event_max_stack_handler
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a8dae)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In kernel/events/uprobes.c (ffffffff813ac8f0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:uprobe_munmap
  - kernel/events/uprobes.c:build_map_info
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff813b0097)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In kernel/context_tracking.c (ffffffff82224542)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_exit
  - kernel/context_tracking.c:__ct_user_enter
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
```
```
In mm/filemap.c (ffffffff813b5980)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/oom_kill.c (ffffffff813bfe03)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_killer_disable
```
```
In mm/page-writeback.c (ffffffff813c6864)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/swap.c (ffffffff813cce53)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff813cd3e4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813dbae2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shrinker.c (ffffffff813e4dc4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff813eb490)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/vmstat.c (ffffffff813f2bd8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/compaction.c (ffffffff81404d9a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/shmem_quota.c (ffffffff81408cea)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_release_dquot
```
```
In mm/list_lru.c (ffffffff8140a87e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/debug.c (ffffffff8140c7ca)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81412a77)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141bebf)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff81425065)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff8142cbe8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mmu_gather.c (ffffffff8142e522)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/mprotect.c (ffffffff8142f41d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81435d1e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff81438451)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/vmalloc.c (ffffffff8143d5e5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (ffffffff81450b65)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_page_is_bad_report
  - mm/page_alloc.c:free_page_is_bad_report
```
```
In mm/memory_hotplug.c (ffffffff8222a13e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff81455329)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/madvise.c (ffffffff814612ed)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_update_vma
```
```
In mm/swap_state.c (ffffffff81466847)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81467587)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_open
  - mm/swapfile.c:swaps_poll
  - mm/swapfile.c:swaps_poll
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__del_from_avail_list
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (ffffffff8146dbd7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81470937)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_current_get
```
```
In mm/hugetlb.c (ffffffff8147ff83)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81482f37)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/mmu_notifier.c (ffffffff814891dd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8148f223)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:unmerge_ksm_pages
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_cow
```
```
In mm/kfence/core.c (ffffffff81494c9e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/kfence/core.c:__kfence_alloc
```
```
In mm/migrate.c (ffffffff8149ab9d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ee82)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8892)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:shrink_huge_zero_page_count
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814aeb7f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff814b425a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:obj_cgroup_release
```
```
In mm/memory-failure.c (ffffffff814c671d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:has_extra_refcount
```
```
In mm/page_isolation.c (ffffffff814ca8d3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zpool.c (ffffffff814caae9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/zpool.c:zpool_unregister_driver
```
```
In mm/zsmalloc.c (ffffffff814ce4fd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814cf604)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/secretmem.c:__ia32_sys_memfd_secret
  - mm/secretmem.c:__x64_sys_memfd_secret
  - mm/secretmem.c:secretmem_active
```
```
In mm/userfaultfd.c (ffffffff814d2782)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814d36dc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814d7232)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d72f7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In mm/page_reporting.c (ffffffff814d86da)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/open.c (ffffffff814d9961)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff814e40af)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
  - fs/super.c:get_bdev_super
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff814eab45)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
  - fs/exec.c:do_open_execat
```
```
In fs/pipe.c (ffffffff814ef2a7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f43ce)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/dcache.c (ffffffff815063fc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/inode.c (ffffffff815091e2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:inode_add_lru
```
```
In fs/file.c (ffffffff8150e429)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
```
In fs/fs-writeback.c (ffffffff8152b5e5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/kernel_read_file.c (ffffffff8153b0e1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/buffer.c (ffffffff8153e787)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/fsnotify.c (ffffffff8154759b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/notification.c (ffffffff81547f1f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/group.c (ffffffff815482f6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/mark.c (ffffffff8154910f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a78a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b3a5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154c405)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550d76)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/userfaultfd.c (ffffffff81559454)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff8155cd88)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_ring_mremap
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff8156558a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_disassociate_entry
```
```
In fs/crypto/crypto.c (ffffffff83922a85)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/crypto/keyring.c (ffffffff8156b951)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/verity/enable.c (ffffffff815712e8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/verify.c (ffffffff83922da5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/locks.c (ffffffff81574ea9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:trace_event_raw_event_generic_add_lease
  - fs/locks.c:trace_event_raw_event_generic_add_lease
  - fs/locks.c:trace_event_raw_event_generic_add_lease
```
```
In fs/mbcache.c (ffffffff8158246d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (ffffffff815832c3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/iomap/buffered-io.c (ffffffff8158be6a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:ifs_free
```
```
In fs/quota/dquot.c (ffffffff815944e3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/dquot.c:dquot_release
```
```
In fs/proc/task_mmu.c (ffffffff8159dbf8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815a124a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a37ea)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/generic.c (ffffffff815a9a2e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_misc_d_delete
  - fs/proc/generic.c:proc_misc_d_revalidate
```
```
In fs/proc/array.c (ffffffff815ace74)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_seccomp
```
```
In fs/proc/meminfo.c (ffffffff815af4f5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/stat.c (ffffffff815afb75)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/proc/proc_sysctl.c (ffffffff815b2ca8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
```
```
In fs/proc/proc_net.c (ffffffff815b5160)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/proc/page.c (ffffffff815b852d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/kernfs/dir.c (ffffffff815bb634)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_get_active
  - fs/kernfs/dir.c:kernfs_get_parent
```
```
In fs/kernfs/file.c (ffffffff815bded7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_should_drain_open_files
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_show
```
```
In fs/configfs/inode.c (ffffffff815c1739)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c366f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815c5da5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/configfs/item.c (ffffffff815c63c6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff815c8948)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/file.c (ffffffff815da3ea)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_release_file
```
```
In fs/ext4/ialloc.c (ffffffff815e198f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815e92d7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81605d55)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
  - fs/ext4/mballoc.c:ext4_mb_pa_put_free
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_callback
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_seq_mb_stats_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81639b85)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/sysfs.c (ffffffff8163d9a7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_show
```
```
In fs/ext4/fast_commit.c (ffffffff81647872)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
```
In fs/ext4/orphan.c (ffffffff81649f3f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_empty
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/transaction.c (ffffffff8164f364)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_wait_updates
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81650b18)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81652eb5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/journal.c (ffffffff8165cc77)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
```
```
In fs/squashfs/decompressor_multi.c (ffffffff81663dc5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_max_decompressors
```
```
In fs/hugetlbfs/inode.c (ffffffff8166809c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/miscdev.c (ffffffff81687df5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8168f3c1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8169605c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_sync_release
```
```
In fs/fuse/inode.c (ffffffff8169cb68)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/control.c (ffffffff8169fd8a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_waiting_read
```
```
In fs/fuse/dax.c (ffffffff816a4531)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_break_layouts
  - fs/fuse/dax.c:fuse_dax_inode_cleanup
```
```
In fs/debugfs/inode.c (ffffffff816a603c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/debugfs/inode.c:remove_one
```
```
In fs/debugfs/file.c (ffffffff816a7465)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_get
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816b168d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/sem.c (ffffffff816b9bfe)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In ipc/shm.c (ffffffff816bc408)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/gc.c (ffffffff816c2574)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff816c2eb9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816c6786)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/proc.c (ffffffff816cdbda)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_keys_show
```
```
In security/selinux/avc.c (ffffffff816e20fd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_get_hash_stats
```
```
In security/selinux/hooks.c (ffffffff816e8e57)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_peerlbl_enabled
  - security/selinux/hooks.c:selinux_secmark_enabled
```
```
In security/tomoyo/common.c (ffffffff8172309e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/tomoyo/condition.c (ffffffff81723e17)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff8172a3e9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/memory.c (ffffffff8172b2ec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ef0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8173922a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8174225a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81744f6e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/policy_unpack.c (ffffffff81747bf2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In security/apparmor/procattr.c (ffffffff8174a28f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8392bee1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81753493)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755c19)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81759486)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175ce84)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea40)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fd30)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817623d0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81765560)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff81767a55)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/fs.c (ffffffff8176e061)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In security/integrity/ima/ima_main.c (ffffffff817707a2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_check_last_writer
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b3da)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
```
In crypto/algapi.c (ffffffff817815f0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_unregister_template
  - crypto/algapi.c:crypto_unregister_alg
```
```
In crypto/proc.c (ffffffff817823c2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - crypto/proc.c:c_show
```
```
In crypto/ahash.c (ffffffff817874d4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817887f3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bdev.c (ffffffff817a8f13)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/bdev.c:sync_bdevs
  - block/bdev.c:bdev_release
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:blkdev_get_whole
  - block/bdev.c:bdev_thaw
```
```
In block/bio.c (ffffffff817ac755)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
```
```
In block/blk-core.c (ffffffff817b3889)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-flush.c (ffffffff817b72ed)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c02d2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff817c952d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
```
In block/partitions/core.c (ffffffff817d4984)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
```
```
In block/blk-rq-qos.c (ffffffff817dfa15)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/bsg-lib.c (ffffffff817e248c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In block/blk-cgroup.c (ffffffff817e686a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-iocost.c (ffffffff817f39c0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:current_hweight
```
```
In block/mq-deadline.c (ffffffff817f51dc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_owned_by_driver_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
```
In block/blk-wbt.c (ffffffff817fe690)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_show
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
```
In block/blk-mq-debugfs.c (ffffffff817ffbd8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
  - block/blk-mq-debugfs.c:hctx_active_show
  - block/blk-mq-debugfs.c:queue_pm_only_show
```
```
In block/blk-crypto-profile.c (ffffffff81808e22)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
```
```
In block/blk-crypto-fallback.c (ffffffff81809691)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/io_uring.c (ffffffff818170d4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wake_function
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_put_task_remote
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/timeout.c (ffffffff8181f20b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff8181feef)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In io_uring/tctx.c (ffffffff81820f3c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff8182282c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_can_finish_inline
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_wake
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/waitid.c (ffffffff8182a95d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_cb
  - io_uring/waitid.c:io_waitid_complete
```
```
In io_uring/io-wq.c (ffffffff8182dac0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/lockref.c (ffffffff81850c60)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In lib/rhashtable.c (ffffffff8185eb3f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/refcount.c (ffffffff8185fdd0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
```
```
In lib/rcuref.c (ffffffff818600e0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
```
```
In lib/percpu_counter.c (ffffffff8191ffa6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_limited_add
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/syscall.c (ffffffff81920720)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/closure.c (ffffffff81925ba0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In lib/stackdepot.c (ffffffff819289af)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:depot_fetch_stack
```
```
In lib/sbitmap.c (ffffffff8192c86c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_queue_wake_all
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff81931164)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950145)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
```
```
In drivers/pci/pci.c (ffffffff8196d648)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pci_disable_enabled_device
  - drivers/pci/pci.c:pci_enable_bridge
```
```
In drivers/pci/pci-driver.c (ffffffff819734b9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/pci-sysfs.c (ffffffff81974f09)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:enable_show
  - drivers/pci/pci-sysfs.c:enable_store
```
```
In drivers/pci/setup-bus.c (ffffffff8197e6b2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/pcie/aer.c (ffffffff81987816)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:find_device_iter
```
```
In drivers/pci/slot.c (ffffffff8198da97)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_destroy_slot
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999d5b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199c3ec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199db71)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
```
In drivers/video/console/dummycon.c (ffffffff819bf5d5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
```
```
In drivers/video/fbdev/core/fb_info.c (ffffffff819c353a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_info.c:framebuffer_release
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c4388)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cd8f5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
  - drivers/video/fbdev/core/fbcon.c:fbcon_register_existing_fbs
  - drivers/video/fbdev/core/fbcon.c:store_rotate_all
  - drivers/video/fbdev/core/fbcon.c:store_rotate
  - drivers/video/fbdev/core/fbcon.c:fbcon_new_modelist
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_blanked
  - drivers/video/fbdev/core/fbcon.c:do_fb_registered
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechange_possible
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_all_vcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_modechanged
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_palette
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_def_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_leave
  - drivers/video/fbdev/core/fbcon.c:fbcon_debug_enter
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_resize
  - drivers/video/fbdev/core/fbcon.c:fbcon_scroll
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_putcs
  - drivers/video/fbdev/core/fbcon.c:fbcon_clear
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f6130)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff82226519)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b99f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff81a8ac83)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a99f52)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/pmdomain/core.c (ffffffff81aa37c0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_power_on
  - drivers/pmdomain/core.c:genpd_power_on
```
```
In drivers/xen/grant-table.c (ffffffff81ab4bd7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/events/events_base.c (ffffffff81ab95d7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:select_target_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac4c19)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:jiffies_eoi_delayed_show
  - drivers/xen/xenbus/xenbus_probe.c:spurious_events_show
  - drivers/xen/xenbus/xenbus_probe.c:events_show
  - drivers/xen/xenbus/xenbus_probe.c:event_channels_show
```
```
In drivers/reset/core.c (ffffffff81ae3e7c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1c57)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_alloc
  - drivers/tty/tty_buffer.c:tty_buffer_space_avail
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9e94)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81afa845)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/tty/vt/vt.c (ffffffff81b09985)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_register_con_driver
  - drivers/tty/vt/vt.c:con_is_bound
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:con_install
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:csi_J
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_allocate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:save_screen
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:set_origin
  - drivers/tty/vt/vt.c:hide_cursor
  - drivers/tty/vt/vt.c:add_softcursor
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:complement_pos
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:invert_screen
  - drivers/tty/vt/vt.c:con_scroll
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d135)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11532)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2dc90)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
```
In drivers/tty/serdev/core.c (ffffffff81b2ef40)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a598)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81b3b6ea)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_backend_acquire
```
```
In drivers/char/agp/generic.c (ffffffff81b3d587)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_copy_info
  - drivers/char/agp/generic.c:agp_allocate_memory
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b5fc7a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79557)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free_locked
```
```
In drivers/iommu/iova.c (ffffffff81b7e1e0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_depot_work_func
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f293)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81274)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/connector/cn_queue.c (ffffffff81b821d8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_free_dev
```
```
In drivers/connector/cn_proc.c (ffffffff81b8381f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/core.c (ffffffff81b8ae6a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff81b90b25)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:driver_probe_done
```
```
In drivers/base/power/sysfs.c (ffffffff81ba27ba)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:runtime_active_kids_show
  - drivers/base/power/sysfs.c:runtime_usage_show
```
```
In drivers/base/power/runtime.c (ffffffff81ba8891)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/runtime.c:rpm_check_suspend_allowed
  - drivers/base/power/runtime.c:rpm_check_suspend_allowed
```
```
In drivers/base/power/main.c (ffffffff81bab317)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/wakeup.c (ffffffff81bafbd6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_save_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_wakeup_pending
```
```
In drivers/block/loop.c (ffffffff81bcf9c1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/block/xen-blkfront.c (ffffffff83951f25)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8f14)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9ccc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:state_show
```
```
In drivers/nvdimm/region.c (ffffffff81c00060)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/security.c (ffffffff81c0c97e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14758)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_signaled
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15057)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16690)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a6ec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/cxl/core/suspend.c (ffffffff81c1bcb5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/cxl/core/suspend.c:cxl_mem_active
```
```
In drivers/scsi/scsi.c (ffffffff81c1e0fd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7c4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25a25)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_enable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2ba61)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_rescan_device
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2e609)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:show_iostat_iotmo_cnt
  - drivers/scsi/scsi_sysfs.c:show_iostat_ioerr_cnt
  - drivers/scsi/scsi_sysfs.c:show_iostat_iodone_cnt
  - drivers/scsi/scsi_sysfs.c:show_iostat_iorequest_cnt
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_blocked
```
```
In drivers/scsi/sr.c (ffffffff81c4407d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
```
```
In drivers/scsi/sg.c (ffffffff81c47d17)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87464)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_connector.c:drm_connector_list_iter_next
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c972b5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_file.c:drm_release
  - drivers/gpu/drm/drm_file.c:drm_file_free
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b17a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_print_info
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_remove
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c44c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca41b0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fe3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb6b27)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_restore
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_restore
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_on
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_put
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_enable
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_arm_vblank_event
  - drivers/gpu/drm/drm_vblank.c:vblank_disable_fn
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_disable_and_save
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In drivers/gpu/drm/drm_vblank_work.c (ffffffff81cb7cc8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_cancel_pending_works
  - drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cb9d59)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_gem_one_name_info
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbb208)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_poll
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc887a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_flip_work.c:drm_can_sleep
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd2783)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_check_var
```
```
In drivers/spi/spi.c (ffffffff81ce0f97)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2cec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cfbeab)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/virtio_net.c (ffffffff81d07e6e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - drivers/net/virtio_net.c:xmit_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff83d508c0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_cleanup
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff83954df2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
  - drivers/net/xen-netfront.c:xennet_get_ethtool_stats
```
```
In drivers/cdrom/cdrom.c (ffffffff81d285c5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d35357)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81d39cc8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/urb.c (ffffffff81d3dc72)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/driver.c (ffffffff81d42511)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/sysfs.c (ffffffff81d48509)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:urbnum_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5441b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6cebf)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/usb/host/xhci.c (ffffffff81d9b085)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded366)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded8ca)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df4405)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_external_power_changed
  - drivers/power/supply/power_supply_core.c:power_supply_property_is_writeable
  - drivers/power/supply/power_supply_core.c:power_supply_set_property
  - drivers/power/supply/power_supply_core.c:power_supply_set_battery_charged
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09cd5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:x86_thermal_enabled
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/md/md.c (ffffffff81e179d0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_spares_need_change
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:mdstat_poll
  - drivers/md/md.c:md_seq_open
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:status_resync
  - drivers/md/md.c:status_resync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:sync_speed_show
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:max_corrected_read_errors_show
  - drivers/md/md.c:errors_show
  - drivers/md/md.c:super_1_sync
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81e28628)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:write_file_page
  - drivers/md/md-bitmap.c:write_file_page
```
```
In drivers/md/dm.c (ffffffff81e31618)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_get_event_nr
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_lock_for_deletion
```
```
In drivers/md/dm-stripe.c (ffffffff81e36462)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
  - drivers/md/dm-stripe.c:stripe_status
  - drivers/md/dm-stripe.c:stripe_status
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38df5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
  - drivers/md/dm-ioctl.c:dm_open
  - drivers/md/dm-ioctl.c:dev_arm_poll
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3be28)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
```
In drivers/md/dm-stats.c (ffffffff81e3ecdd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/md/dm-stats.c:dm_stats_cleanup
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45809)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:instance_npe_count_show
  - drivers/edac/edac_pci_sysfs.c:instance_pe_count_show
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46543)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55d63)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bdf8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/mmc/core/core.c (ffffffff81e695ee)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7b874)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_hw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d37e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81e84308)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/firmware/efi/efi.c (ffffffff8222b427)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e9936a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/ras/debugfs.c (ffffffff81eaedd5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:ras_userspace_consumers
```
```
In net/core/sock.c (ffffffff81ecb07b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sk_get_meminfo
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_kmalloc
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:sock_wmalloc
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_clear_memalloc
```
```
In net/core/request_sock.c (ffffffff81ecc5f3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81ed2219)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_ensure_writable_head_tail
  - net/core/skbuff.c:skb_vlan_untag
  - net/core/skbuff.c:skb_reorder_vlan_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:__skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_cow_data
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:__skb_checksum_complete
  - net/core/skbuff.c:__skb_checksum_complete_head
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:__skb_pad
  - net/core/skbuff.c:skb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skbmem
```
```
In net/core/datagram.c (ffffffff81eddfc7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/stream.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81ee1a30)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81ef51ec)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/neighbour.c (ffffffff81f04701)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_show
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/rtnetlink.c (ffffffff81f1874f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/filter.c (ffffffff81f2a429)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81f37249)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (ffffffff81f38c9f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/core/gso.c (ffffffff81f3e74d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/gso.c:__skb_gso_segment
```
```
In net/core/net-sysfs.c (ffffffff81f42b2c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:carrier_down_count_show
  - net/core/net-sysfs.c:carrier_up_count_show
  - net/core/net-sysfs.c:carrier_changes_show
  - net/core/net-sysfs.c:carrier_changes_show
```
```
In net/core/page_pool.c (ffffffff81f44ab3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
  - net/core/page_pool.c:page_pool_inflight
```
```
In net/core/netpoll.c (ffffffff81f47846)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81f49552)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/net-traces.c (ffffffff81f5406e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:trace_event_raw_event_neigh__update
  - net/core/net-traces.c:trace_event_raw_event_neigh_update
  - net/core/net-traces.c:trace_event_raw_event_neigh_create
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_exceed_buf_limit
  - net/core/net-traces.c:trace_event_raw_event_sock_rcvqueue_full
```
```
In net/core/selftests.c (ffffffff81f5e55b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_loopback_validate
```
```
In net/core/lwt_bpf.c (ffffffff81f616cd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/core/gro_cells.c (ffffffff81f622af)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/core/skmsg.c (ffffffff81f65590)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_return_zero
```
```
In net/core/sock_map.c (ffffffff81f68c25)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_mem_usage
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b38f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_charge
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffff81f710d6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_frag.c (ffffffff81f72047)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/sch_api.c (ffffffff81f74cc4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/sched/cls_api.c (ffffffff81f7c0ab)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_unbind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_bind
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/cls_api.c:__tcf_chain_put
```
```
In net/sched/act_api.c (ffffffff81f8423a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_action_destroy
  - net/sched/act_api.c:tcf_idrinfo_destroy
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffffffff839688f6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_trim
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/netlink/genetlink.c (ffffffff81f8f996)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6d3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb6a7c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7068)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_input.c (ffffffff81fb7cf2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_options
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9c8a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_forward.c (ffffffff81fba4ab)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fc0034)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc82a7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8ef9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb16f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81fd4f6d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_window_clamp
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd7d0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_get_syncookie_mss
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_grow_window
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fed917)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81fedffb)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_out_of_resources
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff077f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8941)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_twsk_purge
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb72b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe9d0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_should_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffeb7d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8200173f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_seq_show
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820050bd)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp4_seq_show
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff8200fd6c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
  - net/ipv4/arp.c:arp_solicit
```
```
In net/ipv4/icmp.c (ffffffff82012274)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_ndo_send
```
```
In net/ipv4/devinet.c (ffffffff8201426c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv4/af_inet.c (ffffffff8201aee4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv4/af_inet.c:inet_sock_destruct
```
```
In net/ipv4/igmp.c (ffffffff8201ee74)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_frontend.c (ffffffff82024581)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_semantics.c (ffffffff8202a2d9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
```
In net/ipv4/inet_fragment.c (ffffffff820300f0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ping.c (ffffffff8203151b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_v4_seq_show
  - net/ipv4/ping.c:ping_close
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035618)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/nexthop.c (ffffffff8203b760)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/proc.c (ffffffff8203f640)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/ipmr.c (ffffffff82042455)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/syncookies.c (ffffffff8204b74d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204d301)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eae6)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa39)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8205231a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_delattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_skbuff_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_validate
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_walk
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052cb9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:__xfrm4_udp_encap_rcv
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205e4e0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d03)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff8206ec85)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff8207532c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/unix/af_unix.c (ffffffff82076396)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_show_fdinfo
  - net/unix/af_unix.c:unix_show_fdinfo
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff8207e179)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff820856f8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff820891e3)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff8208a944)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/ipv6/route.c (ffffffff8209a388)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff820a849e)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/ndisc.c (ffffffff820b4acc)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
```
```
In net/ipv6/udp.c (ffffffff820b5b93)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff820baaef)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8240)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ping.c (ffffffff820ce341)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
```
In net/ipv6/exthdrs.c (ffffffff820d0bd2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff820d3745)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d453b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ioam6.c (ffffffff820d92f5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820deea0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e0ec9)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:__xfrm6_udp_encap_rcv
```
```
In net/ipv6/netfilter.c (ffffffff820e302b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
```
```
In net/ipv6/proc.c (ffffffff820e47ac)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/syncookies.c (ffffffff820e584b)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e6d09)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_skbuff_delattr
  - net/ipv6/calipso.c:calipso_skbuff_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_validate
  - net/ipv6/calipso.c:calipso_doi_walk
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_getdef
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e955c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820eab7f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eebb7)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820eff06)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
```
In net/ipv6/ip6_icmp.c (ffffffff820f1320)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:icmpv6_ndo_send
```
```
In net/ipv6/ip6_offload.c (ffffffff820f1f35)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_hopopt_jumbo_remove
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3a7f)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/packet/af_packet.c (ffffffff820f70de)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:__packet_rcv_has_room
  - net/packet/af_packet.c:prb_retire_current_block
```
```
In net/devlink/core.c (ffffffff82100bd4)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/devlink/rate.c (ffffffff821195a0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_del_doit
```
```
In net/strparser/strparser.c (ffffffff8211b131)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/strparser/strparser.c:__strp_recv
  - net/strparser/strparser.c:__strp_recv
```
```
In net/8021q/vlan_core.c (ffffffff8211c97a)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/netlabel/netlabel_kapi.c (ffffffff821208c5)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_enabled
```
```
In net/rfkill/core.c (ffffffff8212a353)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_remove_epo_lock
  - net/rfkill/core.c:rfkill_restore_states
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:rfkill_switch_all
```
```
In net/xdp/xsk.c (ffffffff8213e467)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xskmap.c (ffffffff82140c15)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_mem_usage
```
```
In net/mptcp/protocol.c (ffffffff821481c8)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:dfrag_clear
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:mptcp_rfree
```
```
In net/mptcp/subflow.c (ffffffff82151393)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
```
```
In net/mptcp/options.c (ffffffff82153470)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_dss
```
```
In net/mptcp/token.c (ffffffff8215509c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/af_mctp.c (ffffffff82164124)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/device.c (ffffffff82164d6d)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff821675a2)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In net/handshake/request.c (ffffffff8216966c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In lib/bug.c (ffffffff82176bd0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
```
In lib/cpumask.c (ffffffff821777c0)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/dec_and_lock.c (ffffffff82177b30)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/is_single_threaded.c (ffffffff8217991c)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/is_single_threaded.c:current_is_single_threaded
  - lib/is_single_threaded.c:current_is_single_threaded
```
```
In lib/klist.c (ffffffff82179dd1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
```
```
In lib/kobject.c (ffffffff8217a8e1)
Location: include/linux/atomic/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
