# Function: <code>__virt_to_phys_nodebug</code>

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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/reboot.c (c030d228)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/reboot.c:__soft_restart
```
```
In arch/arm/kernel/setup.c (c1504a48)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:hyp_mode_check
  - arch/arm/kernel/setup.c:hyp_mode_check
```
```
In arch/arm/kernel/suspend.c (c0311adc)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:cpu_suspend
```
```
In arch/arm/kernel/hibernate.c (c0311cf8)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/hibernate.c:arch_restore_image
  - arch/arm/kernel/hibernate.c:arch_restore_image
```
```
In arch/arm/kernel/smp.c (c0312a30)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:__cpu_up
  - arch/arm/kernel/smp.c:__cpu_up
  - arch/arm/kernel/smp.c:__cpu_up
  - arch/arm/kernel/smp.c:__cpu_up
```
```
In arch/arm/kernel/machine_kexec.c (c031555c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm/kernel/psci_smp.c (c031a0c8)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/kernel/psci_smp.c:psci_boot_secondary
```
```
In arch/arm/mm/init.c (c1507808)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:arm_memblock_init
  - arch/arm/mm/init.c:parse_tag_initrd
```
```
In arch/arm/mm/dma-mapping.c (c031b2dc)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:__dma_clear_buffer
  - arch/arm/mm/dma-mapping.c:__dma_clear_buffer
```
```
In arch/arm/mm/idmap.c (c031ee64)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:setup_mm_for_reboot
  - arch/arm/mm/idmap.c:init_static_idmap
  - arch/arm/mm/idmap.c:init_static_idmap
```
```
In arch/arm/mm/mmap.c (c031f730)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mm/mmap.c:valid_phys_addr_range
```
```
In arch/arm/mm/mmu.c (c1509368)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:arm_mm_memblock_reserve
  - arch/arm/mm/mmu.c:arm_pte_alloc
  - arch/arm/mm/mmu.c:early_fixmap_init
```
```
In arch/arm/mm/context.c (c03223b0)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/common/mcpm_entry.c (c150bac0)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_set_early_poke
  - arch/arm/common/mcpm_entry.c:mcpm_set_early_poke
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical
  - arch/arm/common/mcpm_entry.c:mcpm_sync_init
```
```
In arch/arm/mach-actions/platsmp.c (c032c874)
Location: arch/arm/include/asm/memory.h:215
Inline: True
```
```
In arch/arm/mach-alpine/platsmp.c (c032c964)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-alpine/platsmp.c:alpine_boot_secondary
```
```
In arch/arm/mach-aspeed/platsmp.c (c032ca28)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary
```
```
In arch/arm/mach-berlin/platsmp.c (c150c304)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
```
```
In arch/arm/mach-exynos/firmware.c (c032cde4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-exynos/firmware.c:exynos_suspend
```
```
In arch/arm/mach-exynos/pm.c (c032d130)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_pre_enter_aftr
  - arch/arm/mach-exynos/pm.c:exynos_cpu0_enter_aftr
```
```
In arch/arm/mach-exynos/suspend.c (c032dc94)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_prepare
```
```
In arch/arm/mach-exynos/platsmp.c (c032e874)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_secondary_init
  - arch/arm/mach-exynos/platsmp.c:exynos_secondary_init
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c150cb9c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
```
```
In arch/arm/mach-highbank/pm.c (c032f214)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-highbank/pm.c:highbank_suspend_finish
```
```
In arch/arm/mach-hisi/platmcpm.c (c150ce90)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
```
```
In arch/arm/mach-hisi/platsmp.c (c032f8f8)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hi3xxx_boot_secondary
```
```
In arch/arm/mach-meson/platsmp.c (c032ff48)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot
  - arch/arm/mach-meson/platsmp.c:meson_smp_begin_secondary_boot
```
```
In arch/arm/mach-mvebu/system-controller.c (c0330974)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_set_cpu_boot_addr
```
```
In arch/arm/mach-mvebu/coherency.c (c150db70)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
```
```
In arch/arm/mach-mvebu/pmsu.c (c0331098)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_set_cpu_boot_addr
```
```
In arch/arm/mach-mvebu/pm.c (c0331650)
Location: arch/arm/include/asm/memory.h:215
Inline: True
```
```
In arch/arm/mach-mvebu/platsmp.c (c03319e4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
```
```
In arch/arm/mach-imx/src.c (c033395c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-imx/src.c:imx_set_cpu_jump
```
```
In arch/arm/mach-imx/platsmp.c (c150f494)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:ls1021a_smp_prepare_cpus
  - arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus
  - arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus
```
```
In arch/arm/mach-imx/pm-imx6.c (c1510304)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
```
```
In arch/arm/mach-mediatek/platsmp.c (c1510bb4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
```
```
In arch/arm/mach-milbeaut/platsmp.c (c0334cbc)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-milbeaut/platsmp.c:m10v_die
  - arch/arm/mach-milbeaut/platsmp.c:m10v_die
  - arch/arm/mach-milbeaut/platsmp.c:m10v_boot_secondary
```
```
In arch/arm/mach-npcm/platsmp.c (c0334e24)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary
```
```
In arch/arm/mach-omap2/control.c (c03353ac)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
```
```
In arch/arm/mach-omap2/omap-secure.c (c033b924)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-secure.c:rx51_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:rx51_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:rx51_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:omap3_save_secure_ram
  - arch/arm/mach-omap2/omap-secure.c:omap3_save_secure_ram
  - arch/arm/mach-omap2/omap-secure.c:omap_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:omap_secure_dispatcher
  - arch/arm/mach-omap2/omap-secure.c:omap_secure_dispatcher
```
```
In arch/arm/mach-omap2/omap-smp.c (c15154bc)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_cpu1_startup_valid
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_cpu1_startup_valid
```
```
In arch/arm/mach-omap2/omap-mpuss-lowpower.c (c151585c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_hotplug_cpu
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower
```
```
In arch/arm/mach-rockchip/pm.c (c151917c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_init
```
```
In arch/arm/mach-rockchip/platsmp.c (c1519504)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
```
```
In arch/arm/mach-shmobile/platsmp-apmu.c (c1519ef8)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_prepare_cpus_dt
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_boot_secondary
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_do_suspend
```
```
In arch/arm/mach-shmobile/smp-sh73a0.c (c151a514)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_smp_prepare_cpus
```
```
In arch/arm/mach-shmobile/platsmp-scu.c (c151a56c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_scu_cpu_prepare
```
```
In arch/arm/mach-shmobile/smp-r8a7779.c (c151a5cc)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-r8a7779.c:r8a7779_smp_prepare_cpus
```
```
In arch/arm/mach-shmobile/smp-emev2.c (c151a624)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus
```
```
In arch/arm/mach-tegra/reset.c (c151a914)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init
  - arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init
```
```
In arch/arm/mach-vexpress/dcscb.c (c151ae8c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/dcscb.c:dcscb_init
```
```
In arch/arm/mach-vexpress/spc.c (c034d434)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:__sync_cache_range_w
  - arch/arm/mach-vexpress/spc.c:__sync_cache_range_w
```
```
In arch/arm/mach-vexpress/tc2_pm.c (c034d740)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_cpu_suspend_prepare
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_cpu_powerup
```
```
In arch/arm/mach-vexpress/platsmp.c (c151b4a0)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/platsmp.c:vexpress_smp_dt_prepare_cpus
```
```
In arch/arm/plat-versatile/platsmp.c (c034fae0)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_secondary_init
  - arch/arm/plat-versatile/platsmp.c:versatile_secondary_init
```
```
In kernel/crash_core.c (c040f384)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (c040fb34)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/events/core.c (c04cf614)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/percpu.c (c152e59c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dfl_fc_free
  - mm/percpu.c:pcpu_dfl_fc_alloc
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/memory.c (c051813c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/page_alloc.c (c1531f00)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
```
```
In mm/memblock.c (c0536050)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_find_in_range_node
```
```
In mm/cma.c (c1535138)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/page_ext.c (c15354a4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - mm/page_ext.c:page_ext_init_flatmem
```
```
In mm/usercopy.c (c0565240)
Location: arch/arm/include/asm/memory.h:215
Inline: True
```
```
In fs/io_uring.c (c05d2730)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/vmcore.c (c06125f0)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In drivers/irqchip/irq-gic-v3-its.c (c0819b48)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/bus/arm-cci.c (c08235a4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/bus/arm-cci.c:__sync_cache_range_w
  - drivers/bus/arm-cci.c:__sync_cache_range_w
```
```
In drivers/pci/controller/pcie-rcar.c (c08af5f4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b0458)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5830)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_compose_msi_msg
```
```
In drivers/soc/renesas/r9a06g032-smp.c (c0938528)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_boot_secondary
```
```
In drivers/soc/tegra/pmc.c (c093bd2c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_pmc_suspend
```
```
In drivers/virtio/virtio_ring.c (c093f6a4)
Location: arch/arm/include/asm/memory.h:215
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (c09c0458)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s2
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s1
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_install_table
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_sync_pte
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c31c8)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:iopte_alloc
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/exynos-iommu.c (c09c8e78)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_iova_to_phys
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/dax/super.c (0)
Location: arch/arm/include/asm/memory.h:215
Inline: True
```
```
In drivers/usb/core/devio.c (c0b01ff8)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/qcom_scm-32.c (c0c3670c)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_warm_boot_addr
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
```
```
In drivers/firmware/psci/psci.c (c0c3b050)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/firmware/psci/psci.c:psci_system_suspend
  - drivers/firmware/psci/psci.c:psci_suspend_finisher
```
```
In drivers/firmware/efi/efi.c (c0e99384)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/of/fdt.c (c15af5dc)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_add_memory_arch
  - drivers/of/fdt.c:early_init_fdt_reserve_self
```
```
In drivers/remoteproc/remoteproc_core.c (c0c62b80)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/xdp/xsk.c (c0e78b50)
Location: arch/arm/include/asm/memory.h:215
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
