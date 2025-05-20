# Function: <code>__sw_hweight64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __sw_hweight64(__u64 w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff814034c0)
Location: lib/hweight.c:46
Inline: False
```
**Symbols:**

```
ffffffff814034c0-ffffffff81403523: __sw_hweight64 (STB_GLOBAL)
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
void __sw_hweight64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff81775be0)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff81775be0-ffffffff81775c42: __sw_hweight64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sw_hweight64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff818a6900)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff818a6900-ffffffff818a6962: __sw_hweight64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sw_hweight64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff818e9770)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff818e9770-ffffffff818e97d2: __sw_hweight64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sw_hweight64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/hweight.S (ffffffff81930c10)
Location: arch/x86/lib/hweight.S
Inline: False
```
**Symbols:**

```
ffffffff81930c10-ffffffff81930c72: __sw_hweight64 (STB_GLOBAL)
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
long unsigned int __sw_hweight64(__u64 w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffff80001063ef58)
Location: lib/hweight.c:47
Inline: False
Direct callers:
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
  - arch/arm64/mm/numa.c:node_set_online
  - kernel/workqueue.c:wq_numa_init
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/smp.c:smp_init
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/mempolicy.c:mpol_relative_nodemask
  - security/apparmor/lsm.c:alloc_buffers
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/input/input.c:input_register_device
  - drivers/md/dm.c:dm_get_numa_node
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
  - net/core/ethtool.c:ethtool_get_sset_info
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffff80001063ef58-ffff80001063ef8c: __sw_hweight64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __sw_hweight64(__u64 w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (c07e469c)
Location: lib/hweight.c:47
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - net/core/ethtool.c:ethtool_get_sset_info
```
**Symbols:**

```
c07e469c-c07e4714: __sw_hweight64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __sw_hweight64(__u64 w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (c0000000007e8790)
Location: lib/hweight.c:47
Inline: False
```
**Symbols:**

```
c0000000007e8790-c0000000007e8814: __sw_hweight64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __sw_hweight64(__u64 w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffe00046bde6)
Location: lib/hweight.c:47
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:rcu_cpu_starting
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
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/mm_init.c:mm_compute_batch_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
  - drivers/irqchip/irq-sifive-plic.c:plic_init
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/input/input.c:input_register_device
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/net-sysfs.c:store_rps_map
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffe00046bde6-ffffffe00046be3a: __sw_hweight64 (STB_GLOBAL)
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
