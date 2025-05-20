# Function: <code>__sw_hweight32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int __sw_hweight32(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff81403410)
Location: lib/hweight.c:12
Inline: False
```
**Symbols:**

```
ffffffff81403410-ffffffff8140344a: __sw_hweight32 (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sw_hweight32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff81775ba0)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff81775ba0-ffffffff81775bdc: __sw_hweight32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sw_hweight32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff818a68b0)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff818a68b0-ffffffff818a68ec: __sw_hweight32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sw_hweight32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff818e9720)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff818e9720-ffffffff818e975c: __sw_hweight32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sw_hweight32();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff81930bc0)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff81930bc0-ffffffff81930bfc: __sw_hweight32 (STB_GLOBAL)
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
unsigned int __sw_hweight32(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffff80001063eec0)
Location: lib/hweight.c:13
Inline: False
Direct callers:
  - fs/fs-writeback.c:wbc_detach_inode
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/extcon/extcon.c:extcon_set_state
  - net/core/rtnetlink.c:do_setlink
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
**Symbols:**

```
ffff80001063eec0-ffff80001063eef4: __sw_hweight32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int __sw_hweight32(unsigned int w);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/hweight.c (c07e46a8)
Location: lib/hweight.c:13
Inline: True
Inline callers:
  - lib/hweight.c:__sw_hweight64
  - lib/hweight.c:__sw_hweight64
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/smp.c:smp_prepare_cpus
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
  - arch/arm/probes/kprobes/checkers-common.c:checker_stack_use_stmdx
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/sched/cpufreq_schedutil.c:sugov_start
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_init
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/mm_init.c:mm_compute_batch_init
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/irqchip/irq-gic.c:gic_get_cpumask
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/soc/tegra/flowctrl.c:flowctrl_cpu_suspend_enter
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/input/input.c:input_register_device
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - sound/soc/soc-pcm.c:soc_pcm_codec_params_fixup
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/rtnetlink.c:do_setlink
  - net/core/net-sysfs.c:store_rps_map
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
c07e45d8-c07e4628: __sw_hweight32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int __sw_hweight32(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (c0000000007e86c0)
Location: lib/hweight.c:13
Inline: False
```
**Symbols:**

```
c0000000007e86c0-c0000000007e8718: __sw_hweight32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int __sw_hweight32(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffe00046bd2a)
Location: lib/hweight.c:13
Inline: False
Direct callers:
  - fs/fs-writeback.c:wbc_detach_inode
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - net/core/rtnetlink.c:do_setlink
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
```
**Symbols:**

```
ffffffe00046bd2a-ffffffe00046bd78: __sw_hweight32 (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
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
</ul>
