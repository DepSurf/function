# Function: <code>rdtsc</code>

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
In init/main.c (ffffffff81f59bcd)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff81009cec)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_del
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f67331)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff81037767)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_tsc
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043560)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:collect_tscs
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/smpboot.c (ffffffff810516ae)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810528d9)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052c39)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105b7b7)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff81f740e7)
Location: arch/x86/include/asm/msr.h:120
Inline: True
```
```
In arch/x86/kernel/pvclock.c (ffffffff81065169)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_flags
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/sched/idle.c (ffffffff810c3db3)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In mm/slub.c (ffffffff811eaa61)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff812ce210)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In arch/x86/lib/delay.c (ffffffff813f642f)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:read_current_timer
```
```
In lib/random32.c (ffffffff81f9e498)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff815118b9)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/iommu/dmar.c (ffffffff815334c3)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535cdc)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c918)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba959)
Location: arch/x86/include/asm/msr.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
  - drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func
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
In init/main.c (ffffffff81f81bc8)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff81009fad)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f8f1cf)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff81036977)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043690)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:collect_tscs
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105185b)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810529f9)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81054173)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105b7c7)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff81f9c93c)
Location: arch/x86/include/asm/msr.h:161
Inline: True
```
```
In arch/x86/kernel/pvclock.c (ffffffff81064f35)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/sched/idle.c (ffffffff810c7a95)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In mm/slub.c (ffffffff8120a006)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff812fd800)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff813efabd)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In arch/x86/lib/delay.c (ffffffff8143d21b)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/kaslr.c (ffffffff8143e0b0)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In lib/random32.c (ffffffff81fc9961)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff81566485)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff81587a55)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158a45f)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81591599)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c1af)
Location: arch/x86/include/asm/msr.h:161
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In init/main.c (ffffffff81fbdbff)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff81009fed)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102bb03)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:read_hv_clock_tsc
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81fca55e)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff81036697)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810450e0)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:collect_tscs
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81fd0d22)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff810541ae)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055309)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056e73)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105e757)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff81fd7e87)
Location: arch/x86/include/asm/msr.h:175
Inline: True
```
```
In arch/x86/kernel/pvclock.c (ffffffff81068465)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/sched/idle.c (ffffffff810cdd4d)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In mm/slub.c (ffffffff8121c076)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81313880)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8140933d)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In arch/x86/lib/delay.c (ffffffff8145a19b)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_mwaitx
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/kaslr.c (ffffffff8145b030)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In lib/random32.c (ffffffff820068e4)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff81592be5)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815b5115)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b7acf)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bee59)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f57e)
Location: arch/x86/include/asm/msr.h:175
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
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
In init/main.c (ffffffff8209dc8b)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff8100a49d)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81029ecf)
Location: arch/x86/include/asm/msr.h:186
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff820aad04)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff820acb10)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046ba9)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810493bb)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff8104b87f)
Location: arch/x86/include/asm/msr.h:186
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104bd10)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:collect_tscs
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff820b1848)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053afe)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054c29)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810567d2)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8105dde7)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff820b8cc4)
Location: arch/x86/include/asm/msr.h:186
Inline: True
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067795)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/sched/idle.c (ffffffff810ca6ad)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In mm/slub.c (ffffffff81227ad9)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8130b15e)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81416a15)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff820e7940)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff815a6b3e)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff815cafcd)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cdbaf)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4a48)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176da3c)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid
```
```
In arch/x86/lib/delay.c (ffffffff818fbf5b)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/kaslr.c (ffffffff818fcdce)
Location: arch/x86/include/asm/msr.h:186
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff826a3c93)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff8100a97d)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a05f)
Location: arch/x86/include/asm/msr.h:187
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826b1486)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff826b337e)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a619)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104cdfb)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff8104f29f)
Location: arch/x86/include/asm/msr.h:187
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826b8099)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057868)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810589e9)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105a50e)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826bdc06)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81061aa7)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff826bf50e)
Location: arch/x86/include/asm/msr.h:187
Inline: True
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106b9f5)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/sched/idle.c (ffffffff810d1ebd)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In mm/slub.c (ffffffff81243c16)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8132fbee)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814411fd)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff826f06ae)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff8160d43e)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff81631d9d)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816349ef)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b7dd)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2a68)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81982db6)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/kaslr.c (ffffffff8198487e)
Location: arch/x86/include/asm/msr.h:187
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff826ccd32)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff8100b129)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ab05)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826dab3f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff826dcb46)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104ccac)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104fa9b)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff8105200f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826e1d87)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a74d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b909)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105c5bc)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e79ba)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/trace_clock.c (ffffffff81064ba7)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff826e92ea)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106e685)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/sched/idle.c (ffffffff810c464d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In mm/slub.c (ffffffff81266355)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8135de1e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814740f5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff8271ab17)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff816464bd)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff8166d12d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8166ff4f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676dc6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182bc61)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff819df2d2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/kaslr.c (ffffffff819e0dae)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff82882d4a)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/msr.c (ffffffff8100b089)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a67f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b195)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82890f21)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff82892d9e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:read_tsc
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a318)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104d30b)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8104f66f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105ca37)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828986c0)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff810603cd)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061589)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106223d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e503)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/trace_clock.c (ffffffff8106a817)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/trace_clock.c:trace_clock_x86_tsc
```
```
In arch/x86/kernel/hpet.c (ffffffff8289fea6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/pvclock.c (ffffffff810746a5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In mm/slub.c (ffffffff8127b090)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81375d8e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81491c65)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828d2a3a)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff8166510d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff8168b53e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e46f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695e76)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81857c51)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81a1a202)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1bd5e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff8289a042)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c48f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828a848c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff828aa3cd)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d498)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105024b)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810527cf)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b029a)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063caa)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810658ed)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b637d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff828b7ee2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In mm/slub.c (ffffffff81296a29)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8139f26c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814bf2c5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828eca61)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828f9e31)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816c2f6e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c5adf)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce7b6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189b036)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81a89ee6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81a8bb2c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff8289d027)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cb6f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ab4ec)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff828ad430)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de38)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050bbb)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810530bf)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b3621)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064359)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8039)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9840)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff828be3e0)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097b03)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In mm/slub.c (ffffffff812a67e2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813b80d7)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814d8115)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828f5bb2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff82902d34)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816e5e5e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e8b0f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f25f6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cd1e6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81ac11a6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81ac2dec)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff82cc358c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102f33f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b3de)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In arch/x86/kernel/tsc.c (ffffffff82cd2743)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe3e6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055fae)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810580b2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82cd84b0)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106adf8)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd231)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdea24)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff82ce297c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109a861)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
  - arch/x86/platform/uv/tlb_uv.c:check_enable
  - arch/x86/platform/uv/tlb_uv.c:disable_for_period
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In mm/slub.c (ffffffff812daf98)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff81403ca7)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815378e5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff82d09245)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In arch/x86/lib/delay.c (ffffffff815fd606)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff815ff47d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff8177116c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c73e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179faa6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7723)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aab3f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a08a2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
In init/main.c (ffffffff82faf643)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bd3b9a)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In arch/x86/kernel/tsc.c (ffffffff82fbe58a)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36d2a)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81054eae)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81056d82)
Location: arch/x86/include/asm/msr.h:199
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82fc4882)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82fc95c5)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcae92)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff82fcfc19)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In mm/slub.c (ffffffff812e7888)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff81416eff)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815547a5)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff82ff67f6)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - lib/random32.c:prandom_init_early
```
```
In arch/x86/lib/delay.c (ffffffff81622336)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff8162444d)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff8178c19c)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa40e)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ad646)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b35c3)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b709f)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3752)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
In init/main.c (ffffffff831b9667)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff831c6d2f)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff831c8c27)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c291d8)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105643e)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810576c2)
Location: arch/x86/include/asm/msr.h:199
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff831cf146)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d3e20)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5729)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff831da70f)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In kernel/entry/common.c (ffffffff8113ce29)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
```
In mm/slub.c (ffffffff812eeff8)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff8141db1f)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8155cf15)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff832014de)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - lib/random32.c:prandom_init_early
```
```
In arch/x86/lib/delay.c (ffffffff81605c16)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81607e3d)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff817714ea)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d1ae)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8178ffd6)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817966f3)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a38f)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81988382)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
In init/main.c (ffffffff832999e9)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff832a7bf3)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff832a9f9c)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d479b8)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f04e)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8106052e)
Location: arch/x86/include/asm/msr.h:199
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff832b14a1)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b69ac)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b835e)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd8fc)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In kernel/entry/common.c (ffffffff8115ff46)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
```
In mm/slub.c (ffffffff81337308)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff81471099)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815be245)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff832e8b21)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - lib/random32.c:prandom_init_early
```
```
In arch/x86/lib/delay.c (ffffffff81674506)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81676a7d)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff817f709a)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel/dmar.c (ffffffff8181450e)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81817846)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e683)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818229cf)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a32412)
Location: arch/x86/include/asm/msr.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
In init/main.c (ffffffff83447c1e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83456f94)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff8345985e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f161ed)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b84e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8106cd65)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83462783)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8346849a)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a068)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f2ec)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In kernel/entry/common.c (ffffffff8118a42b)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
```
In mm/slub.c (ffffffff813a8c08)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/kfence/core.c (ffffffff83492687)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In fs/ext4/mballoc.c (ffffffff814f276f)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81667e15)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In arch/x86/lib/delay.c (ffffffff8178ec66)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff817918b5)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff81ec2cb2)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff8195535e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff819587ca)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ea53)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8196267f)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b97359)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9e7fe)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
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
In arch/x86/kernel/tsc.c (ffffffff83e790e1)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd7bd)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107b83e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107ce54)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84bd1)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8c936)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8ecc5)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff83e9590d)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In kernel/entry/common.c (ffffffff811c69ab)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
```
In mm/slub.c (ffffffff81429cea)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff8158c53c)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff817224b5)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In drivers/char/random.c (ffffffff81a94d12)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abb95e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf95a)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac64c3)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb3ff)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d381c9)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fd8e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In arch/x86/lib/delay.c (ffffffff8204c656)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff8204f595)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/tsc.c (ffffffff8369b531)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213f210)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107daee)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107f204)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff836a80d8)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b01c6)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b2565)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff836b947d)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In kernel/entry/common.c (ffffffff811d95cb)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
```
In mm/slub.c (ffffffff8145f0ca)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff815c2677)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8175dd65)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In drivers/char/random.c (ffffffff81ae0532)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0823e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b12b8a)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b130a3)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17e0f)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da25c9)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa8fe)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In arch/x86/lib/delay.c (ffffffff820caf66)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff820cde15)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/tsc.c (ffffffff838cb206)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:quick_pit_calibrate
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221230)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81084f9e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81086d14)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff838d8616)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e07e1)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e2e45)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff838e9da2)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In kernel/entry/common.c (ffffffff82223e63)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In mm/slub.c (ffffffff8145a239)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In fs/ext4/mballoc.c (ffffffff815fb2f7)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8179fc45)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In drivers/char/random.c (ffffffff81b33932)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5c25e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
  - drivers/iommu/intel/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b679ca)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_enable_translation
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:iommu_disable_protect_mem_regions
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d74f)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a699)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_sample
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e62a3e)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sample
```
```
In arch/x86/lib/delay.c (ffffffff821a5796)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff821a8635)
Location: arch/x86/include/asm/msr.h:180
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8288b027)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cccf)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828994fe)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff8289b442)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104df98)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050cbb)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828a1640)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063e49)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a6040)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7858)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff828a93b6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In mm/slub.c (ffffffff8129edc2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813b06b7)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814d06f5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828dea66)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828ea51b)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816ab93e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ae5ef)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7de6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81870de6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81a5fff6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81a61c3c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff82888fc3)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828917bf)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff828937d5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d468)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81040f1d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81042d0f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82899819)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105414c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289e17d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289f937)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff828a1462)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In mm/slub.c (ffffffff81290902)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813a1147)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814c1115)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828d7182)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828e19a8)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff8168929e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168bf4f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695a26)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183be2d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81a1d0c6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1ecac)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff8289e027)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cb2f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4de)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae422)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dde8)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050b6b)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8105306f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b4603)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff810642f9)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8f50)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba757)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff828bc2b5)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In mm/slub.c (ffffffff8129cbd2)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813adf17)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814cc785)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828f17da)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff828fe057)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816d9b1e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dc7cf)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e62b6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c2696)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81acc3e6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81ace02c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In init/main.c (ffffffff8289e02e)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d92f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4fc)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae440)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:tsc_read_refs
  - arch/x86/kernel/tsc.c:native_sched_clock
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f228)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051fab)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810544ef)
Location: arch/x86/include/asm/msr.h:201
Inline: True
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b4624)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/kernel/smpboot.c (ffffffff810658c0)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b9051)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_cal_handler
  - arch/x86/kernel/apic/apic.c:lapic_next_deadline
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba86d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
```
In arch/x86/kernel/hpet.c (ffffffff828bf40d)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098fc3)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In mm/slub.c (ffffffff812acc36)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/ext4/mballoc.c (ffffffff813c3263)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814e5255)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In lib/random32.c (ffffffff828f6c06)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (ffffffff82903d96)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/dmar.c (ffffffff816f40ce)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
  - drivers/iommu/dmar.c:dmar_disable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f6e0f)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_disable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:iommu_enable_translation
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_flush_write_buffer
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff817009b6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818de9a6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
```
```
In arch/x86/lib/delay.c (ffffffff81ad88f6)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:read_current_timer
```
```
In arch/x86/lib/kaslr.c (ffffffff81ada53c)
Location: arch/x86/include/asm/msr.h:201
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
</ul>

## Differences
