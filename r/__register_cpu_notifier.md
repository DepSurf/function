# Function: <code>__register_cpu_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __register_cpu_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081270)
Location: kernel/cpu.c:205
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/profile.c:create_proc_profile
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/events/core.c:perf_event_init
  - mm/vmstat.c:setup_vmstat
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:init_zswap
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff81081270-ffffffff8108128a: __register_cpu_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __register_cpu_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810837f0)
Location: kernel/cpu.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/vmstat.c:setup_vmstat
  - mm/zswap.c:init_zswap
  - mm/zswap.c:zswap_pool_create
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff810837f0-ffffffff8108380a: __register_cpu_notifier (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
