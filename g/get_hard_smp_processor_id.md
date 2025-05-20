# Function: <code>get_hard_smp_processor_id</code>

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
In arch/powerpc/kernel/irq.c (c00000000001c2ac)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
```
```
In arch/powerpc/kernel/sysfs.c (c0000000000297ac)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kernel/sysfs.c:show_physical_id
```
```
In arch/powerpc/kernel/prom.c (c00000000002c500)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom.c:arch_match_cpu_phys_id
```
```
In arch/powerpc/kernel/rtas.c (c00000000003d9a4)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
```
```
In arch/powerpc/kernel/dbell.c (c000000000050170)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kernel/dbell.c:doorbell_global_ipi
```
```
In arch/powerpc/kernel/smp.c (c000000001350ab0)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
```
```
In arch/powerpc/mm/numa.c (c0000000000a3108)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
```
```
In arch/powerpc/lib/locks.c (c0000000000b40c4)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/lib/locks.c:splpar_rw_yield
  - arch/powerpc/lib/locks.c:splpar_spin_yield
```
```
In arch/powerpc/sysdev/mpic.c (c0000000000b6c54)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
```
```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba850)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server
  - arch/powerpc/sysdev/xics/xics-common.c:xics_update_irq_servers
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c0000000013596d8)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
```
```
In arch/powerpc/sysdev/xics/icp-hv.c (c0000000000bafcc)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_ipi_action
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_cause_ipi
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_teardown_cpu
```
```
In arch/powerpc/sysdev/xics/icp-opal.c (c0000000000bc7e4)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_flush_interrupt
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_ipi_action
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_cause_ipi
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bd84c)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_setup_cpu_ipi
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_vcpu_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_irq_mask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_unmask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_shutdown
  - arch/powerpc/sysdev/xive/common.c:xive_irq_startup
```
```
In arch/powerpc/sysdev/xive/native.c (c0000000000c0758)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_cleanup_queue
  - arch/powerpc/sysdev/xive/native.c:xive_native_setup_queue
```
```
In arch/powerpc/sysdev/xive/spapr.c (c0000000000c0f5c)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_cleanup_queue
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_setup_queue
```
```
In arch/powerpc/platforms/powernv/setup.c (c0000000000c1bd8)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
```
```
In arch/powerpc/platforms/powernv/idle.c (c00000000135c05c)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:pnv_program_cpu_hotplug_lpcr
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000ce344)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_kick_cpu
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfef0)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_core_pmu_counters
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eb144)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vpa_init
  - arch/powerpc/platforms/pseries/lpar.c:dtl_worker_offline
  - arch/powerpc/platforms/pseries/lpar.c:register_dtl_buffer
```
```
In arch/powerpc/platforms/pseries/smp.c (c0000000000f8880)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f8ef0)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_die
```
```
In arch/powerpc/platforms/pseries/dtl.c (c0000000000fccf0)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_release
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
```
```
In arch/powerpc/xmon/xmon.c (c00000000010af10)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:dump_one_xive
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000001216f0)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123d4c)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_eoi
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012aaa0)
Location: arch/powerpc/include/asm/smp.h:194
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:trace_imc_event_del
  - arch/powerpc/perf/imc-pmu.c:trace_imc_event_add
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_event_del
  - arch/powerpc/perf/imc-pmu.c:thread_imc_event_add
  - arch/powerpc/perf/imc-pmu.c:core_imc_event_init
  - arch/powerpc/perf/imc-pmu.c:core_imc_counters_release
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:nest_imc_event_init
  - arch/powerpc/perf/imc-pmu.c:nest_imc_counters_release
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
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
