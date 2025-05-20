# Function: <code>v7_flush_kern_cache_all</code>

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
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/reboot.c:__soft_restart
  - arch/arm/kernel/reboot.c:__soft_restart
  - arch/arm/kernel/smp_scu.c:scu_enable
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
  - arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:early_cachepolicy
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_init
  - arch/arm/mach-exynos/firmware.c:exynos_cpu_suspend
  - arch/arm/mach-exynos/suspend.c:exynos_suspend_enter
  - arch/arm/mach-exynos/suspend.c:exynos3250_cpu_suspend
  - arch/arm/mach-exynos/suspend.c:exynos_cpu_suspend
  - arch/arm/mach-hisi/hotplug.c:hix5hd2_cpu_die
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_cpu_die
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_idle_finish
  - arch/arm/mach-omap2/omap-secure.c:rx51_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:rx51_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:omap_secure_dispatcher
  - arch/arm/mach-rockchip/pm.c:rockchip_lpmode_enter
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-shmobile/platsmp.c:shmobile_smp_hook
  - arch/arm/mach-shmobile/platsmp.c:shmobile_smp_hook
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_cpu_die
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_unmap_vmap_area
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
c0321f44-c0321f5c: v7_flush_kern_cache_all (STB_GLOBAL)
```
</details>
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
