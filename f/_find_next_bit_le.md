# Function: <code>_find_next_bit_le</code>

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
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
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
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_next
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/events/core.c:perf_output_sample_regs
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_next_unpop
  - mm/frontswap.c:frontswap_register_ops
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/genalloc.c:gen_pool_best_fit
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-htc-egpio.c:egpio_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
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
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
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
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-netlink.c:ncsi_write_package_info
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c0e7d5cc-c0e7d5f4: _find_next_bit_le (STB_GLOBAL)
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
