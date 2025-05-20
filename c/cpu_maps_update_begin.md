# Function: <code>cpu_maps_update_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810810e0)
Location: kernel/cpu.c:40
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
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - kernel/profile.c:create_proc_profile
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/events/core.c:perf_event_init
  - mm/vmstat.c:setup_vmstat
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
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
```
**Symbols:**

```
ffffffff810810e0-ffffffff810810f7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084e86)
Location: kernel/cpu.c:117
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
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - mm/vmstat.c:setup_vmstat
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zsmalloc.c:zs_unregister_cpu_notifier
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_init
```
**Symbols:**

```
ffffffff810835f0-ffffffff81083607: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089e36)
Location: kernel/cpu.c:187
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
ffffffff810895c0-ffffffff810895d7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086cf6)
Location: kernel/cpu.c:196
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
```
**Symbols:**

```
ffffffff810868d0-ffffffff810868e7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108da96)
Location: kernel/cpu.c:271
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
```
**Symbols:**

```
ffffffff8108d680-ffffffff8108d697: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109101f)
Location: kernel/cpu.c:268
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
```
**Symbols:**

```
ffffffff81091210-ffffffff81091227: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810993af)
Location: kernel/cpu.c:266
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
```
**Symbols:**

```
ffffffff81098eb0-ffffffff81098ec7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dda5)
Location: kernel/cpu.c:267
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
```
**Symbols:**

```
ffffffff8109d430-ffffffff8109d447: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a42f5)
Location: kernel/cpu.c:270
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
```
**Symbols:**

```
ffffffff810a3980-ffffffff810a3997: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aadfa)
Location: kernel/cpu.c:271
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
```
**Symbols:**

```
ffffffff810aaa50-ffffffff810aaa67: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a668a)
Location: kernel/cpu.c:271
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
```
**Symbols:**

```
ffffffff810a62e0-ffffffff810a62f7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a76fa)
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
```
**Symbols:**

```
ffffffff810a7240-ffffffff810a7257: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b913d)
Location: kernel/cpu.c:287
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
```
**Symbols:**

```
ffffffff810b8c30-ffffffff810b8c47: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cfab6)
Location: kernel/cpu.c:288
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
```
**Symbols:**

```
ffffffff810cf570-ffffffff810cf58d: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810edec8)
Location: kernel/cpu.c:288
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
```
**Symbols:**

```
ffffffff810ed910-ffffffff810ed92d: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f9fad)
Location: kernel/cpu.c:467
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
```
**Symbols:**

```
ffffffff810f99c0-ffffffff810f99dd: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff811033cd)
Location: kernel/cpu.c:467
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
```
**Symbols:**

```
ffffffff81102dd0-ffffffff81102ded: cpu_maps_update_begin (STB_GLOBAL)
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
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9dcc)
Location: kernel/cpu.c:270
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
```
**Symbols:**

```
ffff8000100f9268-ffff8000100f928c: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c035802c)
Location: kernel/cpu.c:270
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
c0357588-c03575ac: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140e74)
Location: kernel/cpu.c:270
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
c00000000013ffb0-c00000000013ffec: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3e56)
Location: kernel/cpu.c:270
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffe0000c3d9e-ffffffe0000c3dc8: cpu_maps_update_begin (STB_GLOBAL)
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
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dc15)
Location: kernel/cpu.c:270
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
```
**Symbols:**

```
ffffffff8109d2a0-ffffffff8109d2b7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c635)
Location: kernel/cpu.c:270
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
```
**Symbols:**

```
ffffffff8108bcc0-ffffffff8108bcd7: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109dbc5)
Location: kernel/cpu.c:270
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
```
**Symbols:**

```
ffffffff8109d250-ffffffff8109d267: cpu_maps_update_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpu_maps_update_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5ab5)
Location: kernel/cpu.c:270
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
```
**Symbols:**

```
ffffffff810a50d0-ffffffff810a50e7: cpu_maps_update_begin (STB_GLOBAL)
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
