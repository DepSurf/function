# Function: <code>atomic64_or</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d1652)
Location: arch/x86/include/asm/atomic64_64.h:260
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907ee7)
Location: arch/x86/include/asm/atomic64_64.h:252
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81991fae)
Location: arch/x86/include/asm/atomic64_64.h:247
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee641)
Location: include/asm-generic/atomic-instrumented.h:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a29265)
Location: include/asm-generic/atomic-instrumented.h:183
Inline: True
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
In kernel/locking/mutex.c (ffffffff81a9a1fa)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810f86c7)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81ad1b4a)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110450f)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81bc9e01)
Location: include/asm-generic/atomic-instrumented.h:1325
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110f0e1)
Location: include/asm-generic/atomic-instrumented.h:1325
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81c42c49)
Location: include/asm-generic/atomic-instrumented.h:1325
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110c27d)
Location: include/asm-generic/atomic-instrumented.h:1325
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81c348f8)
Location: include/asm-generic/atomic-instrumented.h:1325
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110e0c2)
Location: include/asm-generic/atomic-instrumented.h:1325
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff8000100874a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:sve_probe_vqs
  - arch/arm64/kernel/fpsimd.c:sve_set_vector_length
  - arch/arm64/kernel/fpsimd.c:sve_setup
```
```
In arch/arm64/kernel/process.c (ffff800010089848)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:set_tagged_addr_ctrl
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008e7cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:sve_set
```
```
In arch/arm64/kernel/signal.c (ffff800010092020)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In arch/arm64/kernel/stacktrace.c (ffff8000100939b0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:unwind_frame
```
```
In arch/arm64/kernel/cpuinfo.c (ffff8000100980a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu
  - arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099e98)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:update_cpu_capabilities
```
```
In arch/arm64/kernel/smp.c (ffff800011435d24)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/smp.c:smp_init_cpus
```
```
In arch/arm64/kernel/acpi_numa.c (ffff800011436bb0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100ac034)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In arch/arm64/mm/numa.c (ffff8000100b217c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_update_cpu
  - arch/arm64/mm/numa.c:numa_add_memblk
  - arch/arm64/mm/numa.c:node_set_online
```
```
In virt/kvm/kvm_main.c (ffff8000100b9f70)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_enable_nolock
  - virt/kvm/kvm_main.c:kvm_vcpu_check_block
  - virt/kvm/kvm_main.c:mark_page_dirty_in_slot
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In virt/kvm/arm/arm.c (ffff8000100c4544)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_set_mpstate
```
```
In virt/kvm/arm/psci.c (ffff8000100ce5a0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_hvc_call_handler
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d5554)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:reset_sys_reg_descs
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dadc0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd488)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:vgic_kick_vcpus
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e07a0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_doorbell_handler
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef204)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_set_counter_event_type
  - virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow
```
```
In arch/arm/xen/enlighten.c (ffff80001143abbc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:fdt_find_hyper_node
```
```
In kernel/fork.c (ffff8000100f467c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffff8000100f61ac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In kernel/cpu.c (ffff8000114422dc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/exit.c (ffff8000100fd2d8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff80001010713c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_resume
```
```
In kernel/signal.c (ffff80001010e4fc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_wake_up_state
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/sys.c (ffff80001011a0cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:__arm64_sys_prctl
```
```
In kernel/workqueue.c (ffff800011443054)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/kthread.c (ffff800010128560)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/sched/core.c (ffff80001013d4a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffff80001013f994)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/idle.c:idle_inject_timer_fn
```
```
In kernel/sched/fair.c (ffff80001014c3e4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffff80001014e9c8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffff800010152c68)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/sched/cpupri.c (ffff800010159f0c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffff80001015a7e0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffff80001015c388)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffff800010da3594)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffff800010169df4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/irq/irqdesc.c (ffff800011446690)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/manage.c (ffff80001017b544)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_set_thread_affinity
```
```
In kernel/irq/resend.c (ffff80001017d624)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/chip.c (ffff80001017f7b4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/generic-chip.c (ffff800010181508)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In kernel/irq/affinity.c (ffff80001018824c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffff80001018c820)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/profile.c (ffff800010198c14)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3c44)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/tick-sched.c (ffff8000101b5df4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_oneshot_notify
  - kernel/time/tick-sched.c:tick_clock_notify
```
```
In kernel/module.c (ffff8000101c4d60)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:flush_module_icache
  - kernel/module.c:flush_module_icache
```
```
In kernel/kexec_core.c (ffff8000101c87c8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4f70)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc9f4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/freezer.c (ffff8000101dd354)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffff80001144b3ec)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
  - kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag
```
```
In kernel/auditsc.c (ffff8000101f1900)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_alloc
```
```
In kernel/seccomp.c (ffff800010209d48)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/tracepoint.c (ffff80001020ec60)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/ring_buffer.c (ffff80001021d068)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffff8000102278a0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_filter_add_remove_task
```
```
In kernel/trace/trace_hwlat.c (ffff800010231fa4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_events.c (ffff80001023b228)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_count_probe
  - kernel/trace/trace_events.c:event_enable_probe
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
  - kernel/trace/trace_events.c:trace_event_enable_tgid_record
  - kernel/trace/trace_events.c:trace_event_enable_cmd_record
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d5e0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242208)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger
  - kernel/trace/trace_events_trigger.c:update_cond_flag
```
```
In kernel/bpf/cgroup.c (ffff80001028e0b8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
```
```
In kernel/events/core.c (ffff8000102a15f4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/ring_buffer.c (ffff8000102a2b44)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffff8000102a3a38)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffff8000102a8624)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_dup_mmap
  - kernel/events/uprobes.c:uprobe_dup_mmap
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_munmap
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/rseq.c (ffff8000102ac6a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/rseq.c:__arm64_sys_rseq
```
```
In mm/filemap.c (ffff8000102aefac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/oom_kill.c (ffff8000102b7ac0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/maccess.c (ffff8000102b9f98)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page-writeback.c (ffff8000102bbe4c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
  - mm/page-writeback.c:__writepage
```
```
In mm/readahead.c (ffff8000102bf634)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffff8000102c1070)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_drain_all
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/truncate.c (ffff8000102c4c8c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/vmscan.c (ffff8000102cccb0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d5800)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffff8000114534c4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/backing-dev.c (ffff8000102de108)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_get_create
```
```
In mm/percpu.c (ffff8000114539fc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
```
```
In mm/workingset.c (ffff8000102f036c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffff8000102f11e0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffff8000103022fc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/rmap.c (ffff80001030a560)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffff800010313880)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/shuffle.c (ffff800010da019c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/page_io.c (ffff80001032098c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:swap_slot_free_notify
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffff8000103224dc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010324d2c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/frontswap.c (ffff80001032aacc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (ffff80001032c718)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff800010336120)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffff80001033c3f4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffff800010342060)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff800010344c90)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:get_map
```
```
In mm/memory_hotplug.c (ffff800010d9d170)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffff800010353058)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff800010354aa4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:setup_transparent_hugepage
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:defrag_store
  - mm/huge_memory.c:single_hugepage_flag_store
  - mm/huge_memory.c:enabled_store
  - mm/huge_memory.c:enabled_store
```
```
In mm/khugepaged.c (ffff80001035db04)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff80001036b8f4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:memcg_set_shrinker_bit
```
```
In mm/memory-failure.c (ffff8000103707a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In mm/zsmalloc.c (ffff80001037444c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In mm/userfaultfd.c (ffff8000103786a0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffff800010379328)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/read_write.c (ffff800010381794)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
```
```
In fs/exec.c (ffff80001038db84)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
```
```
In fs/libfs.c (ffff8000103c0a9c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
```
```
In fs/fs-writeback.c (ffff8000103cb128)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/splice.c (ffff8000103cfa64)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
```
```
In fs/buffer.c (ffff8000103d9b1c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/block_dev.c (ffff8000103e0b74)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/mpage.c (ffff8000103e64a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffff8000103fb1f8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffff8000104060a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/dax.c (ffff8000104096e0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/crypto/crypto.c (ffff80001040b304)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffff800010410e94)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffff800010413978)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffff800010421140)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104249ec)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/iomap/buffered-io.c (ffff80001042ab60)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/quota/dquot.c (ffff8000104307a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_acquire
  - fs/quota/dquot.c:dquot_acquire
```
```
In fs/proc/base.c (ffff80001043ec44)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
```
```
In fs/proc/proc_sysctl.c (ffff80001044a0f8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
```
In fs/ext4/balloc.c (ffff800010460a88)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffff80001046309c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (ffff800010463e98)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/extents.c (ffff800010465368)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff8000104757dc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010476bc4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffff80001047cca8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_destroy_inline_data
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff800010489898)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffff80001048c8ac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffff8000104940ac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/migrate.c (ffff800010498784)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/move_extent.c (ffff80001049a030)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffff8000104a0cec)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/page-io.c (ffff8000104a4064)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffff8000104a4e60)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/resize.c (ffff8000104a6e10)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffff8000104b9030)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/xattr.c (ffff8000104c6fec)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/verity.c (ffff8000104c8930)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
```
In fs/jbd2/transaction.c (ffff8000104cc984)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ceb98)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
```
In fs/jbd2/recovery.c (ffff8000104d0948)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffff8000104d247c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffff8000104d8c90)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffff8000104dbe28)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffff8000104ddcd4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffff8000104de2d8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ramfs/inode.c (ffff8000104e03a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1ad0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_set_page_dirty
```
```
In fs/fat/dir.c (ffff8000104e4a30)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffff8000104e8edc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/inode.c (ffff8000104ed02c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In fs/ecryptfs/mmap.c (ffff8000104f62b0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffff8000104f66a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff8000105051cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:request_wait_answer
```
```
In fs/fuse/dir.c (ffff800010506aac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_readpage
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffff80001050e950)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/readdir.c (ffff800010514ba0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
```
```
In security/keys/gc.c (ffff80001052d838)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffff80001052e198)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/request_key.c (ffff800010535a9c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:cache_requested_key
```
```
In security/tomoyo/common.c (ffff80001057c228)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/integrity/iint.c (ffff8000105ac9e8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In security/integrity/ima/ima_main.c (ffff8000105aec78)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffff8000105b4b54)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In block/blk-core.c (ffff8000105e0eac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
```
```
In block/blk-mq.c (ffff8000105f2854)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - block/blk-mq.c:blk_mq_hctx_mark_pending
```
```
In block/blk-mq-sched.c (ffff8000105f6c94)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/blk-cgroup.c (ffff80001060e31c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In block/blk-zoned.c (ffff80001061fef8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/bitmap.c (ffff80001062be34)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/cpu_rmap.c (ffff8000106628bc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/irq_poll.c (ffff800010667bc0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffff80001066a444)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472c28)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674484)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010675bd0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067725c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067acdc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067bbac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_chip_unmask_irq
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067c964)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067eaec)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a4340)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106af2b4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffff8000106c5418)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiochip_enable_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_direction_output
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-legacy.c (ffff8000106c7438)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9958)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pwm/core.c (ffff8000106d8670)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/bus.c (ffff8000106dcc9c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071ac80)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e3b8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722808)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff80001072333c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725798)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107262ac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727d50)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff800010729830)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072bd3c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_alloc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072f5ec)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/rapidio/rio.c (ffff80001073be70)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c1c4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760738)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/acpi/ec.c (ffff800010772bfc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/sysfs.c (ffff80001147de7c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
```
```
In drivers/acpi/numa.c (ffff80001147e65c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a3b30)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffff8000107a6490)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:initiator_cmp
  - drivers/acpi/hmat/hmat.c:initiator_cmp
```
```
In drivers/acpi/battery.c (ffff8000107a8188)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_add
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8d5c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/clk/clk.c (ffff8000114833d8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_init
```
```
In drivers/dma/dmaengine.c (ffff8000107fd56c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
  - drivers/dma/dmaengine.c:dma_get_slave_channel
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/dma/amba-pl08x.c (ffff8000108026d0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804700)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff8000108080b8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff80001080921c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148ef78)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f530)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810fd8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff8000108115c8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/fsl/qbman/bman.c (ffff8000108123cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816750)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c618)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
```
```
In drivers/xen/cpu_hotplug.c (ffff80001082b744)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/xen/grant-table.c (ffff80001082cd8c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/events/events_2l.c (ffff800010832dc4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_mask
  - drivers/xen/events/events_2l.c:evtchn_2l_set_pending
  - drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu
```
```
In drivers/xen/events/events_fifo.c (ffff8000108340c8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_mask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_set_pending
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083e38c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/regulator/core.c (ffff800010846954)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_balance_voltage
```
```
In drivers/tty/tty_io.c (ffff800010852900)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/n_tty.c (ffff800010857254)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_receive_char_special
```
```
In drivers/tty/tty_ioctl.c (ffff80001085bb24)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle_safe
```
```
In drivers/tty/tty_ldisc.c (ffff80001085c52c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
```
In drivers/tty/tty_port.c (ffff80001085ef34)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085fe6c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/tty/pty.c (ffff800010861ac4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_open
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_unthrottle
  - drivers/tty/pty.c:pty_close
  - drivers/tty/pty.c:pty_close
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/sysrq.c (ffff8000108647d4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffff80001086bcf0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffff800010880fa0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088b960)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (ffff80001089573c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_probe
```
```
In drivers/tty/serial/max310x.c (ffff800010899a80)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aa680)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_buf
```
```
In drivers/char/misc.c (ffff8000108b24ac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d758c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
```
```
In drivers/base/core.c (ffff8000108e61a0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/base/cacheinfo.c (ffff8000108f4704)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/base/power/domain.c (ffff800010909a04)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffff800010919ac8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/base/arch_topology.c (ffff80001092003c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
```
```
In drivers/nvdimm/bus.c (ffff800010951cc4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010954590)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095adf8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffff80001095f36c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/nvdimm/security.c (ffff800010962344)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
```
```
In drivers/dax/super.c (ffff800010963a88)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:alloc_dax
  - drivers/dax/super.c:run_dax
  - drivers/dax/super.c:dax_write_cache
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966840)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/scsi/scsi_error.c (ffff800010971794)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f084)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported
  - drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change
```
```
In drivers/ata/libata-scsi.c (ffff8000109a2f00)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/net/tun.c (ffff8000109de628)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4634)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea79c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fa078)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_close
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a01e28)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffff800010a09758)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hub.c (ffff800010a18c9c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
```
```
In drivers/usb/core/hcd.c (ffff800010a1dad8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/sysfs.c (ffff800010a2b56c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
```
```
In drivers/usb/core/devio.c (ffff800010a2c7cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:claimintf
```
```
In drivers/usb/core/port.c (ffff800010a35e40)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a422cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
```
```
In drivers/usb/host/ehci-hcd.c (ffff80001149c36c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/ohci-hcd.c (ffff80001149c550)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_init
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffff80001149c67c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (ffff800010a71718)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7e0a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a869cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e008)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
```
In drivers/input/mousedev.c (ffff800010a9cae8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa3144)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
```
```
In drivers/input/misc/uinput.c (ffff800010aa5d9c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abc944)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_suspend_noirq
```
```
In drivers/media/cec/cec-core.c (ffff800010abde6c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffff800010acd97c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/thermal/thermal_core.c (ffff800010ad5608)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adf890)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1b08)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
```
In drivers/md/md.c (ffff800010ae8530)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_wakeup_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:add_new_disk
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:consistency_policy_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:resync_start_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:recovery_start_store
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
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_1_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_90_validate
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffff800010af92f0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_load
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_write_all
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffff800010afe4d8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_suspend_noflush
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_lock_for_deletion
```
```
In drivers/md/dm-io.c (ffff800010b0a0b0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0be5c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/opp/cpu.c (ffff800010b1aee8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/opp/of.c (ffff800010b1b568)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b215e4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/leds/led-core.c (ffff800010b48cb0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4be4c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_event_handler
  - drivers/firmware/arm_sdei.c:sdei_event_handler
```
```
In drivers/firmware/ti_sci.c (ffff800010b51ab4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_get_free_resource
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56eac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
```
```
In drivers/firmware/efi/efi.c (ffff8000114a5d10)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:parse_efi_cmdline
```
```
In drivers/firmware/efi/memattr.c (ffff8000114a605c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_init
```
```
In drivers/firmware/efi/memmap.c (ffff8000114a66d8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
```
In drivers/firmware/efi/secureboot.c (ffff8000114a7164)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a748c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:uefi_init
  - drivers/firmware/efi/arm-init.c:uefi_init
```
```
In drivers/firmware/efi/arm-runtime.c (ffff8000114a79a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67ba4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/of/base.c (ffff800010b694cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_get_alias_list
```
```
In drivers/of/platform.c (ffff800010b6de7c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_populate
  - drivers/of/platform.c:of_platform_bus_create
```
```
In drivers/of/dynamic.c (ffff800010b709a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/dynamic.c:of_changeset_destroy
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/dynamic.c:__of_detach_node
```
```
In drivers/of/fdt.c (ffff800010b7210c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/fdt.c:__unflatten_device_tree
```
```
In drivers/of/irq.c (ffff8000114ac148)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/irq.c:of_irq_init
```
```
In drivers/of/overlay.c (ffff800010b7787c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/overlay.c:dup_and_fixup_symbol_prop
```
```
In drivers/of/of_numa.c (ffff8000114aca10)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/of/of_numa.c:of_numa_init
```
```
In drivers/perf/arm-cci.c (ffff800010b91d5c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In drivers/perf/arm_pmu_platform.c (ffff800010b95834)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
```
```
In drivers/perf/arm_pmu_acpi.c (ffff800010b95df4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96a58)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_get_event_idx
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97e6c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_get_event_idx
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99c14)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a8a0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c664)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
  - drivers/perf/xgene_pmu.c:xgene_perf_add
```
```
In net/socket.c (ffff800010ba2d40)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:__arm64_sys_setsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
```
```
In net/core/sock.c (ffff800010bac584)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/datagram.c (ffff800010bbc638)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/stream.c (ffff800010bbd5ac)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
```
```
In net/core/sysctl_net_core.c (ffff800010bc5a04)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffff800010bcb1b0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/dev.c:init_dummy_netdev
  - net/core/dev.c:init_dummy_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_alloc_name_ns
```
```
In net/core/neighbour.c (ffff800010be37cc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffff800010c0b884)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:show_rps_map
```
```
In net/core/skmsg.c (ffff800010c0f814)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/gro_cells.c (ffff800010c30d48)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c3a0a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/genetlink.c (ffff800010c5242c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74d10)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
  - net/ipv4/tcp.c:tcp_poll
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_output.c (ffff800010c82248)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca1f98)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffff800010ca9b80)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/ipmr.c (ffff800010ccbcb0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd41a8)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf1de4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_accept
```
```
In net/ipv6/addrconf.c (ffff800010d00b24)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/ndisc.c (ffff800010d2270c)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/dns_resolver/dns_key.c (ffff8000114b5ba0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
```
In net/dns_resolver/dns_query.c (ffff800010d730a4)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/dns_resolver/dns_query.c:dns_query
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76d40)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
```
```
In net/ncsi/ncsi-manage.c (ffff800010d7aba0)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
```
In lib/vsprintf.c (ffff800010d983fc)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5a70)
Location: arch/powerpc/include/asm/atomic.h:385
Inline: True
```
```
In kernel/locking/rwsem.c (c0000000001c1c50)
Location: arch/powerpc/include/asm/atomic.h:385
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffe0008c6e7a)
Location: arch/riscv/include/asm/atomic.h:79
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffe00010afd4)
Location: arch/riscv/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81a709ba)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810fd81f)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81a2cdaa)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810eda13)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81adcdca)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810fa9df)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/mutex.c (ffffffff81ae90a6)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff81105ba2)
Location: include/asm-generic/atomic-instrumented.h:1324
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
</details>
</li>
</ul>

## Differences
