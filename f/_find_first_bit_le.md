# Function: <code>_find_first_bit_le</code>

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
  - arch/arm/kernel/smp.c:cpufreq_callback
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_init
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_init
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/stats.c:schedstat_start
  - kernel/sched/debug.c:sched_debug_start
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/poweroff.c:handle_poweroff
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/resend.c:resend_irqs
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - mm/frontswap.c:frontswap_register_ops
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_set_bit
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-htc-egpio.c:egpio_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/msi.c:pci_irq_get_node
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/musb/musb_core.c:musb_interrupt
  - drivers/usb/musb/musb_core.c:musb_interrupt
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/opp/of.c:dev_pm_opp_of_register_em
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
  - drivers/clocksource/dw_apb_timer.c:apbt_resume
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_shutdown
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_irq
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - lib/idr.c:ida_free
  - lib/nodemask.c:__next_node_in
```
**Symbols:**

```
c0e7d5a0-c0e7d5cc: _find_first_bit_le (STB_GLOBAL)
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
