# Function: <code>cpu_has_feature</code>

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
In arch/powerpc/kernel/ptrace.c (c000000000015ef4)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_get
  - arch/powerpc/kernel/ptrace.c:pmu_active
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_get
  - arch/powerpc/kernel/ptrace.c:ebb_active
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_get
  - arch/powerpc/kernel/ptrace.c:tm_dscr_active
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_get
  - arch/powerpc/kernel/ptrace.c:tm_ppr_active
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_get
  - arch/powerpc/kernel/ptrace.c:tm_tar_active
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_active
  - arch/powerpc/kernel/ptrace.c:tm_cvsx_set
  - arch/powerpc/kernel/ptrace.c:tm_cvsx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_active
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_active
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_active
```
```
In arch/powerpc/kernel/syscalls.c (c0000000000198a0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/syscalls.c:__se_sys_mmap
  - arch/powerpc/kernel/syscalls.c:__se_sys_mmap2
```
```
In arch/powerpc/kernel/irq.c (c00000000001bbcc)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
  - arch/powerpc/kernel/irq.c:arch_show_interrupts
```
```
In arch/powerpc/kernel/align.c (c00000000001c4d0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/align.c:fix_alignment
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001f120)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
```
```
In arch/powerpc/kernel/process.c (c000000000022e28)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:__ppc64_runlatch_off
  - arch/powerpc/kernel/process.c:__ppc64_runlatch_on
  - arch/powerpc/kernel/process.c:get_endian
  - arch/powerpc/kernel/process.c:get_endian
  - arch/powerpc/kernel/process.c:get_endian
  - arch/powerpc/kernel/process.c:set_endian
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:arch_dup_task_struct
  - arch/powerpc/kernel/process.c:arch_dup_task_struct
  - arch/powerpc/kernel/process.c:set_thread_tidr
  - arch/powerpc/kernel/process.c:set_thread_uses_vas
  - arch/powerpc/kernel/process.c:show_regs
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:__switch_to
  - arch/powerpc/kernel/process.c:restore_tm_state
  - arch/powerpc/kernel/process.c:restore_math
  - arch/powerpc/kernel/process.c:restore_math
  - arch/powerpc/kernel/process.c:init_msr_all_available
  - arch/powerpc/kernel/process.c:init_msr_all_available
  - arch/powerpc/kernel/process.c:__giveup_altivec
  - arch/powerpc/kernel/process.c:__giveup_fpu
  - arch/powerpc/kernel/process.c:__msr_check_and_clear
  - arch/powerpc/kernel/process.c:msr_check_and_set
```
```
In arch/powerpc/kernel/idle.c (c00000000002349c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/idle.c:arch_cpu_idle
  - arch/powerpc/kernel/idle.c:arch_cpu_idle
```
```
In arch/powerpc/kernel/sysfs.c (c0000000013489ac)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:unregister_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:register_cpu_online
  - arch/powerpc/kernel/sysfs.c:setup_smt_snooze_delay
```
```
In arch/powerpc/kernel/time.c (c00000000002be48)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:running_clock
  - arch/powerpc/kernel/time.c:running_clock
  - arch/powerpc/kernel/time.c:time_init
```
```
In arch/powerpc/kernel/traps.c (c00000000002ec98)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:emulate_instruction
  - arch/powerpc/kernel/traps.c:emulate_instruction
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a440)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:show_cpuinfo
```
```
In arch/powerpc/kernel/setup_64.c (c000000000031028)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:cpu_ready_for_interrupts
  - arch/powerpc/kernel/setup_64.c:cpu_ready_for_interrupts
  - arch/powerpc/kernel/setup_64.c:cpu_ready_for_interrupts
  - arch/powerpc/kernel/setup_64.c:cpu_ready_for_interrupts
```
```
In arch/powerpc/kernel/signal_64.c (c000000000034188)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
```
```
In arch/powerpc/kernel/dawr.c (c00000000134ccc0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/dawr.c:dawr_force_setup
```
```
In arch/powerpc/kernel/security.c (c00000000003b880)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/security.c:setup_stf_barrier
  - arch/powerpc/kernel/security.c:setup_stf_barrier
  - arch/powerpc/kernel/security.c:setup_stf_barrier
```
```
In arch/powerpc/kernel/smp.c (c000000000054498)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:powerpc_smt_flags
  - arch/powerpc/kernel/smp.c:smp_generic_cpu_bootable
```
```
In arch/powerpc/mm/fault.c (0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
```
```
In arch/powerpc/mm/mem.c (c000000000087574)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:copy_user_page
  - arch/powerpc/mm/mem.c:clear_user_page
  - arch/powerpc/mm/mem.c:__flush_dcache_icache
```
```
In arch/powerpc/mm/pgtable.c (0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
```
```
In arch/powerpc/mm/mmu_context.c (c00000000008a14c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/mmu_context.c:switch_mm_irqs_off
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008e378)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:flush_hash_hugepage
  - arch/powerpc/mm/book3s64/hash_utils.c:flush_hash_page
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_initialize
```
```
In arch/powerpc/mm/book3s64/slb.c (c00000000008ec60)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:slb_insert_entry
  - arch/powerpc/mm/book3s64/slb.c:switch_slb
  - arch/powerpc/mm/book3s64/slb.c:switch_slb
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c0000000000925d8)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_clear
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_find
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_updatepp
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_updatepp
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_insert
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c0000000013567e4)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_mmu
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000097d14)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid_guest
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_all_lpid
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_lpid_page
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm
```
```
In arch/powerpc/mm/book3s64/hash_64k.c (c00000000009df7c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_64K
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_64K
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e548)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:__hash_page_huge
```
```
In arch/powerpc/lib/feature-fixups.c (c0000000000a768c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
  - arch/powerpc/lib/feature-fixups.c:do_stf_barrier_fixups
```
```
In arch/powerpc/lib/sstep.c (c0000000000b1f70)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_step
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
  - arch/powerpc/lib/sstep.c:analyse_instr
```
```
In arch/powerpc/platforms/powernv/setup.c (c0000000000c1c44)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
```
```
In arch/powerpc/platforms/powernv/idle.c (c00000000135bbd0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt
  - arch/powerpc/platforms/powernv/idle.c:pnv_cpu_offline
  - arch/powerpc/platforms/powernv/idle.c:pnv_cpu_offline
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/platforms/powernv/rng.c (c00000000135cdbc)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/rng.c:__machine_initcall_powernv_rng_init
```
```
In arch/powerpc/platforms/powernv/smp.c (c00000000135ec9c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_probe
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_probe
  - arch/powerpc/platforms/powernv/smp.c:pnv_cpu_bootable
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_kill_self
  - arch/powerpc/platforms/powernv/smp.c:pnv_flush_interrupts
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d4de0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (c000000001361c0c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:hpte_init_pseries
  - arch/powerpc/platforms/pseries/lpar.c:vpa_init
  - arch/powerpc/platforms/pseries/lpar.c:vpa_init
```
```
In arch/powerpc/platforms/pseries/smp.c (c0000000013638e4)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
  - arch/powerpc/platforms/pseries/smp.c:pSeries_smp_probe
```
```
In arch/powerpc/xmon/xmon.c (c00000000010af2c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:dump_one_xive
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/xmon/ppc-dis.c (c000000000116034)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c000000000120400)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_hpte_hv_fault
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_hv_find_lock_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_hv_find_lock_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_clear_ref_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_invalidate_hpte
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_read
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_protect
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_bulk_remove
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_remove
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000120e20)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_check_need_tlb_flush
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_eoi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_ipoll
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_xirr_x
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_xirr
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_cma_reserve
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123ee4)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:kvmppc_deliver_irq_passthru
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
```
```
In arch/powerpc/perf/core-book3s.c (c0000000001283f0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
```
```
In arch/powerpc/perf/isa207-common.c (c00000000013560c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_compute_mmcr
  - arch/powerpc/perf/isa207-common.c:isa207_get_constraint
  - arch/powerpc/perf/isa207-common.c:isa207_get_constraint
  - arch/powerpc/perf/isa207-common.c:isa207_get_constraint
  - arch/powerpc/perf/isa207-common.c:isa207_get_constraint
```
```
In arch/powerpc/perf/power8-pmu.c (c000000000135db4)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - arch/powerpc/perf/power8-pmu.c:init_power8_pmu
```
```
In mm/mprotect.c (c0000000003d3050)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - mm/mprotect.c:__se_sys_mprotect
```
```
In drivers/misc/cxl/base.c (c0000000013abd6c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - drivers/misc/cxl/base.c:cxl_base_init
```
```
In drivers/cpuidle/cpuidle-pseries.c (c000000000c22624)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:shared_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:shared_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:dedicated_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:dedicated_cede_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
  - drivers/cpuidle/cpuidle-pseries.c:snooze_loop
```
```
In drivers/cpuidle/cpuidle-powernv.c (c000000000c22b2c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:23
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
  - drivers/cpuidle/cpuidle-powernv.c:snooze_loop
```
</details>
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
