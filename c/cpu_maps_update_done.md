# Function: <code>cpu_maps_update_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081100)
Location: kernel/cpu.c:46
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_disable
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:register_cpu_notifier
  - kernel/cpu.c:unregister_cpu_notifier
  - kernel/cpu.c:cpu_down
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/profile.c:create_proc_profile
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/events/core.c:perf_event_init
  - mm/vmstat.c:setup_vmstat
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - drivers/idle/intel_idle.c:intel_idle_exit
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff81081100-ffffffff81081117: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084ec0)
Location: kernel/cpu.c:123
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:unregister_cpu_notifier
  - kernel/cpu.c:register_cpu_notifier
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/vmstat.c:setup_vmstat
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_init
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff81083610-ffffffff81083627: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089e6d)
Location: kernel/cpu.c:192
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff810895e0-ffffffff810895f7: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086d2d)
Location: kernel/cpu.c:201
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810868f0-ffffffff81086907: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108dacd)
Location: kernel/cpu.c:276
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8108d6a0-ffffffff8108d6b7: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810910a3)
Location: kernel/cpu.c:273
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81091230-ffffffff81091247: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109942c)
Location: kernel/cpu.c:271
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81098ed0-ffffffff81098ee7: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109de48)
Location: kernel/cpu.c:272
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8109d450-ffffffff8109d467: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4398)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810a39a0-ffffffff810a39b7: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aae1f)
Location: kernel/cpu.c:276
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810aaa70-ffffffff810aaa87: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a66af)
Location: kernel/cpu.c:276
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810a6300-ffffffff810a6317: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a771f)
Location: kernel/cpu.c:281
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810a7260-ffffffff810a7277: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b9162)
Location: kernel/cpu.c:292
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810b8c50-ffffffff810b8c67: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cfae8)
Location: kernel/cpu.c:293
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810cf590-ffffffff810cf5ad: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810edefc)
Location: kernel/cpu.c:293
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810ed940-ffffffff810ed95d: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f9fce)
Location: kernel/cpu.c:472
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810f99f0-ffffffff810f9a0d: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff811033ee)
Location: kernel/cpu.c:472
Inline: True
Inline callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_device_down
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81102e00-ffffffff81102e1d: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9dfc)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffff8000100f9290-ffff8000100f92b4: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0358050)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_up
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
```
**Symbols:**

```
c03575ac-c03575d0: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140eb0)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
**Symbols:**

```
c00000000013fff0-c00000000014002c: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3f0a)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffe0000c3dc8-ffffffe0000c3df2: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dcb8)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8109d2c0-ffffffff8109d2d7: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c6d8)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8108bce0-ffffffff8108bcf7: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dc68)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8109d270-ffffffff8109d287: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5b58)
Location: kernel/cpu.c:275
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:do_cpu_down
  - kernel/cpu.c:cpu_hotplug_enable
  - kernel/cpu.c:cpu_hotplug_disable
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810a50f0-ffffffff810a5107: cpu_maps_update_done (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
