# Function: <code>__raw_readl</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 __raw_readl(volatile const void *addr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a96c0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100df364)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_put
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_put
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (ffff800010dad1a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access
```
```
In kernel/irq/generic-chip.c (ffff800010180d04)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_init_mask_cache
  - kernel/irq/generic-chip.c:irq_readl_be
```
```
In fs/debugfs/file.c (ffff80001051845c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_print_regs32
```
```
In lib/iomap_copy.c (ffff80001063d7f0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In lib/logic_pio.c (ffff80001063e708)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In lib/stmp_device.c (ffff800010667a1c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_clear_poll_bit
```
```
In drivers/irqchip/irq-al-fic.c (ffff80001066a8c0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-bcm2835.c (ffff80001066ab18)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
```
```
In drivers/irqchip/irq-bcm2836.c (ffff8000100816d0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_per_cpu_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_per_cpu_irq
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff80001066b188)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
Direct callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-sun4i.c (ffff80001066b340)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_unmask
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_mask
  - drivers/irqchip/irq-sun4i.c:sun4i_handle_irq
  - drivers/irqchip/irq-sun4i.c:sun4i_handle_irq
  - drivers/irqchip/irq-sun4i.c:sun4i_handle_irq
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001066b694)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c444)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_cpu_if_down
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic.c:gic_peek_irq
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
```
```
In drivers/irqchip/irq-gic-common.c (ffff80001066cf58)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d788)
Location: arch/arm64/include/asm/io.h:72
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e460)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_dist_supports_lpis
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists
  - drivers/irqchip/irq-gic-v3.c:gic_peek_irq
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_gicc
  - drivers/irqchip/irq-gic-v3.c:gic_validate_dist_version
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674ad0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
```
```
In drivers/irqchip/irq-mbigen.c (ffff800010676378)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_write_msg
  - drivers/irqchip/irq-mbigen.c:mbigen_set_type
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676a94)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067700c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff800010677a78)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677d64)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff800010678448)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff80001067898c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
  - drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_save
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff8000106796fc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff800010679f50)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_unmask_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_mask_irq
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a95c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b08c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067ba48)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c4a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_enable
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_unmask
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_mask
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067c994)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067d2b4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067da28)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f1d8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:wait_lpc_idle
```
```
In drivers/bus/brcmstb_gisb.c (ffff80001067ffb8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:gisb_read
  - drivers/bus/brcmstb_gisb.c:gisb_read
```
```
In drivers/bus/imx-weim.c (ffff800010685010)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
```
```
In drivers/bus/qcom-ebi2.c (ffff8000106856f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/phy/phy-xgene.c (ffff8000106881ec)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/phy/broadcom/phy-brcm-sata.c (ffff80001068a9c4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_wr
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692e08)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff8000106949fc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_set
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_get
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinmux_set_mux
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b1c0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b650)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readl
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a0ac8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3a9c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2711_pull_config_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_set_direction
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_disable_free
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_free
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_get_direction
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_get
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a615c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_direction
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a742c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a824c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_dbg_show
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aaa04)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_get
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac4b4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_suspend
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106adb3c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get_direction
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afc40)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b349c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get_config
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get_config
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pmx_set_mux
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b581c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_get
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_get
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7c14)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bb020)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_rmw
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc320)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/gpio/gpio-mmio.c:bgpio_read32
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce3a0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
  - drivers/gpio/gpio-davinci.c:davinci_gpio_get
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106cedf4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d0c9c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2450)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d6684)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_suspend
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_get_direction
  - drivers/gpio/gpio-xgene.c:__xgene_gpio_set
  - drivers/gpio/gpio-xgene.c:xgene_gpio_get
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d6bb0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_get
```
```
In drivers/pci/access.c (ffff8000106da534)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_read32
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffff8000106ef87c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffff8000106ff0cc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff80001071075c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_query_power_fault
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_status
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_latch_status
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_power_status
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_attention_status
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/msi.c (ffff8000107155bc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d784)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e99c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f640)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pci-aardvark.c (ffff8000107203c4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_unmask
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_mask
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wait_pio
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wait_pio
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_check_pio_status
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_link_up
Direct callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_check_pio_status
```
```
In drivers/pci/controller/pcie-rcar.c (ffff8000107226fc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_wait_for_dl
  - drivers/pci/controller/pcie-rcar.c:phy_wait_for_ack
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_rmw32
Direct callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723710)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus
Direct callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff80001072508c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_misc_handler
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_map_bus
Direct callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107259e8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107266f0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107279f0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:altera_pcie_link_up
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010728278)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
```
```
In drivers/pci/controller/pcie-rockchip.c (ffff800010728330)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff800010729c00)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_get_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b8f0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072caf0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072cdec)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072ff98)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732b28)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_err_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_start_link
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_stop_link
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_clear_dbi_mode
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_clear_dbi_mode
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_set_dbi_mode
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_set_dbi_mode
Direct callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff800010733594)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_link_up
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010735278)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_3_2_ltssm_enable
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_1_0_ltssm_enable
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff800010736664)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_link_up
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_sideband_dbi_r_mode
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736f84)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_r_mode
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_w_mode
```
```
In drivers/pci/controller/dwc/pcie-al.c (ffff800010737980)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_host_init
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_host_init
```
```
In drivers/pci/controller/pci-thunder-ecam.c (ffff8000107386c0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
```
```
In drivers/pci/controller/pci-xgene.c (ffff800010739db0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_map_bus
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffff800010759050)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075a95c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
Direct callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075b5c0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_setcolreg
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760a00)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/acpi/osl.c (ffff800010763b64)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a9ad0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/amba/bus.c (ffff8000107b978c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/clk-divider.c (ffff8000107c47b4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffff8000107c5684)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffff8000107c5b18)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffff8000107c6390)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c7148)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/clk/clk-fixed-mmio.c (ffff8000107c7e84)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
```
```
In drivers/clk/clk-hsdk-pll.c (ffff8000107c84f8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate
```
```
In drivers/clk/clk-qoriq.c (ffff8000107c85a0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Direct callers:
  - drivers/clk/clk-qoriq.c:p5040_init_periph
  - drivers/clk/clk-qoriq.c:p5020_init_periph
  - drivers/clk/clk-qoriq.c:p4080_init_periph
  - drivers/clk/clk-qoriq.c:p2041_init_periph
```
```
In drivers/clk/clk-xgene.c (ffff8000107c9544)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/clk-xgene.c:xgene_clk_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_recalc_rate
  - drivers/clk/clk-xgene.c:xgene_clk_is_enabled
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pll_recalc_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pll_is_enabled
```
```
In drivers/clk/bcm/clk-iproc-armpll.c (ffff8000107cb240)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/clk/bcm/clk-iproc-pll.c (ffff8000107cc998)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_recalc_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_recalc_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:__pll_enable
  - drivers/clk/bcm/clk-iproc-pll.c:__pll_enable
  - drivers/clk/bcm/clk-iproc-pll.c:__pll_enable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_write
```
```
In drivers/clk/bcm/clk-iproc-asiu.c (ffff8000107ccc90)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_set_rate
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_set_rate
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_recalc_rate
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_disable
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_enable
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107ce9f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_clock
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_get_parent
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_get_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_is_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_is_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_get_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_get_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_get_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_is_on
```
```
In drivers/clk/berlin/berlin2-avpll.c (ffff8000107cf140)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_enable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_enable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_is_enabled
```
```
In drivers/clk/berlin/berlin2-pll.c (ffff8000107cf300)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate
  - drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate
```
```
In drivers/clk/berlin/berlin2-div.c (ffff8000107cf614)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled
```
```
In drivers/clk/hisilicon/clkgate-separated.c (ffff8000107d02b8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_is_enabled
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d061c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_recalc_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (ffff8000107d0a70)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_get_phase
```
```
In drivers/clk/hisilicon/reset.c (ffff8000107d1424)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/hisilicon/clk-hi3660-stub.c (ffff8000107d1a68)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_recalc_rate
```
```
In drivers/clk/imx/clk.c (ffff800011485944)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_mmdc_mask_handshake
```
```
In drivers/clk/imx/clk-busy.c (ffff8000107d1f28)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-busy.c:clk_busy_wait
```
```
In drivers/clk/imx/clk-composite-8m.c (ffff8000107d24b4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (ffff8000107d31c0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:imx_clk_divider_gate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_is_enabled
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate_ro
```
```
In drivers/clk/imx/clk-fixup-div.c (ffff8000107d33e0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (ffff8000107d368c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-frac-pll.c (ffff8000107d3a9c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_is_prepared
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_unprepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-gate-exclusive.c (ffff8000107d3c58)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate-exclusive.c:clk_gate_exclusive_enable
```
```
In drivers/clk/imx/clk-gate2.c (ffff8000107d3fb4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_is_enabled
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfd.c (ffff8000107d4448)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfd.c:clk_pfd_is_enabled
  - drivers/clk/imx/clk-pfd.c:clk_pfd_recalc_rate
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d4984)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_is_enabled
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv1.c (ffff8000107d4b84)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv1.c:clk_pllv1_recalc_rate
```
```
In drivers/clk/imx/clk-pllv2.c (ffff8000107d4f64)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_unprepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
```
```
In drivers/clk/imx/clk-pllv3.c (ffff8000107d5888)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_is_prepared
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_unprepare
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare
```
```
In drivers/clk/imx/clk-pllv4.c (ffff8000107d5d2c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_disable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_is_enabled
```
```
In drivers/clk/imx/clk-sccg-pll.c (ffff8000107d6688)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_get_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_unprepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_is_prepared
```
```
In drivers/clk/imx/clk-pll14xx.c (ffff8000107d6f44)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_unprepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_is_prepared
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_recalc_rate
```
```
In drivers/clk/imx/clk-lpcg-scu.c (ffff8000107d76f8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable
```
```
In drivers/clk/mediatek/clk-pll.c (ffff8000107e2674)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_is_prepared
```
```
In drivers/clk/mediatek/clk-apmixed.c (ffff8000107e2df8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_unprepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_is_prepared
```
```
In drivers/clk/mvebu/armada-37xx-tbg.c (ffff8000107e8ab4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e96d4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_suspend
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_recalc_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_get_parent
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_double_div_recalc_rate
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_double_div_recalc_rate
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107ea48c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_div_recalc_rate
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eaf58)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_sd_clock_is_enabled
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_z_clk_recalc_rate
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify
Direct callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec04c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_status
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
```
```
In drivers/clk/renesas/clk-div6.c (ffff8000107ec7e8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_parent
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_rate
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_is_enabled
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_disable
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_enable
Direct callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
```
```
In drivers/clk/rockchip/clk-pll.c (ffff8000107ecf78)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_is_enabled
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_is_enabled
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_is_enabled
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee510)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_recalc_rate
```
```
In drivers/clk/rockchip/clk-half-divider.c (ffff8000107eefc0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_recalc_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (ffff8000107ef37c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_get_phase
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (ffff8000107ef5f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_mmc_get_phase
```
```
In drivers/clk/rockchip/clk-ddr.c (ffff8000107efc30)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_get_parent
```
```
In drivers/clk/rockchip/softrst.c (ffff8000107f00a4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/rockchip/clk-rk3288.c (ffff8000107f02c8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend
```
```
In drivers/clk/socfpga/clk-pll-s10.c (ffff8000107f0808)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/socfpga/clk-pll-s10.c:clk_pll_prepare
  - drivers/clk/socfpga/clk-pll-s10.c:clk_boot_get_parent
  - drivers/clk/socfpga/clk-pll-s10.c:clk_pll_get_parent
  - drivers/clk/socfpga/clk-pll-s10.c:clk_boot_clk_recalc_rate
  - drivers/clk/socfpga/clk-pll-s10.c:clk_pll_recalc_rate
  - drivers/clk/socfpga/clk-pll-s10.c:clk_pll_recalc_rate
```
```
In drivers/clk/socfpga/clk-periph-s10.c (ffff8000107f0a74)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/socfpga/clk-periph-s10.c:clk_peri_cnt_clk_recalc_rate
  - drivers/clk/socfpga/clk-periph-s10.c:clk_peri_c_clk_recalc_rate
```
```
In drivers/clk/socfpga/clk-gate-s10.c (ffff8000107f0ecc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/socfpga/clk-gate-s10.c:socfpga_gate_get_parent
  - drivers/clk/socfpga/clk-gate-s10.c:socfpga_dbg_clk_recalc_rate
  - drivers/clk/socfpga/clk-gate-s10.c:socfpga_gate_clk_recalc_rate
```
```
In drivers/clk/sunxi/clk-factors.c (ffff8000107f1490)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
  - drivers/clk/sunxi/clk-factors.c:clk_factors_recalc_rate
```
```
In drivers/clk/sunxi/clk-a10-pll2.c (ffff80001148c398)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
```
```
In drivers/clk/sunxi/clk-a10-ve.c (ffff8000107f2354)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff8000107f26bc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
  - drivers/clk/sunxi/clk-mod0.c:mmc_get_phase
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (ffff8000107f28f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_status
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (ffff8000107f2c80)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_recalc_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_get_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_is_enabled
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3778)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3b34)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (ffff8000107f4230)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_common.c (ffff8000107f4868)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (ffff8000107f4cb0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_get_mmc_timing_mode
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
```
```
In drivers/clk/sunxi-ng/ccu_reset.c (ffff8000107f4e34)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_status
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu_div.c (ffff8000107f5244)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_frac.c (ffff8000107f583c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_read_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_is_enabled
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f5a70)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_gate.c:ccu_gate_is_enabled
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f6480)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_get_parent
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (ffff8000107f6940)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (ffff8000107f6bfc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_get_phase
```
```
In drivers/clk/sunxi-ng/ccu_sdm.c (ffff8000107f72c4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_read_rate
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_is_enabled
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_is_enabled
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (ffff8000107f77f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (ffff8000107f7ec8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (ffff8000107f86b0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (ffff8000107f9030)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f978c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_mmc_set_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_mmc_recalc_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_recalc_rate
```
```
In drivers/clk/sunxi-ng/ccu-sun50i-a64.c (ffff8000107f9a14)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu-sun50i-h6.c (ffff8000107f9b0c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-a83t.c (ffff8000107f9ccc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_cpu_pll_fixup
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-h3.c (ffff80001148e784)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-h3.c:sunxi_h3_h5_ccu_init
```
```
In drivers/clk/versatile/clk-sp810.c (ffff8000107fa06c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_get_parent
```
```
In drivers/dma/amba-pl08x.c (ffff800010802978)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff80001080498c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/mv_xor.c (ffff8000108060ec)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_suspend
  - drivers/dma/mv_xor.c:mv_xor_suspend
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
```
```
In drivers/dma/mv_xor_v2.c (ffff8000108092b0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_resume
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_resume
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler
```
```
In drivers/dma/mxs-dma.c (ffff80001080979c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_tx_status
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080a378)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d16c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_ic_disable_task
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
  - drivers/dma/ipu/ipu_idmac.c:dump_idmac_reg
```
```
In drivers/soc/actions/owl-sps-helper.c (ffff80001080d940)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e0f8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
Direct callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
```
```
In drivers/soc/bcm/brcmstb/common.c (ffff80001080f494)
Location: arch/arm64/include/asm/io.h:72
Inline: False
Direct callers:
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init
  - drivers/soc/bcm/brcmstb/common.c:brcmstb_soc_device_early_init
```
```
In drivers/soc/bcm/brcmstb/biuctrl.c (ffff80001080f4a0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Direct callers:
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f7f0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff8000108102a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_set_sdest
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_set_sdest
  - drivers/soc/fsl/qbman/qman_ccsr.c:__qman_liodn_fixup
  - drivers/soc/fsl/qbman/qman_ccsr.c:__qman_liodn_fixup
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr
  - drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010811f0c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:portal_isr
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010813624)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_remove
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:portal_isr
```
```
In drivers/soc/fsl/guts.c (ffff800010817d1c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/imx/soc-imx8.c (ffff800010818768)
Location: arch/arm64/include/asm/io.h:72
Inline: False
Direct callers:
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff800010819448)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b354)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_is_free
```
```
In drivers/soc/renesas/renesas-soc.c (ffff80001081e174)
Location: arch/arm64/include/asm/io.h:72
Inline: False
Direct callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/soc/renesas/rcar-rst.c (ffff800011491090)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff8000114913c4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/soc/sunxi/sunxi_sram.c (ffff80001081f9b8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_claim
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826958)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_get_status
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffff800010827570)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff8000108293a0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
```
In drivers/reset/reset-meson.c (ffff80001084da04)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_level
```
```
In drivers/reset/reset-simple.c (ffff80001084df94)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_status
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088798c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_in
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffff80001088c3f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff8000108900ec)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffff8000108906f4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890b2c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_in32be
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_in32
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108959e4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_putc
  - drivers/tty/serial/amba-pl011.c:pl011_putc
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc
  - drivers/tty/serial/amba-pl011.c:pl011_read
```
```
In drivers/tty/serial/imx.c (ffff80001089b580)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_early_putchar
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_tx_empty
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_get_hwmctrl
  - drivers/tty/serial/imx.c:imx_uart_get_hwmctrl
  - drivers/tty/serial/imx.c:imx_uart_get_hwmctrl
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_setup
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e720)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/meson_uart.c:meson_uart_stop_rx
  - drivers/tty/serial/meson_uart.c:meson_uart_stop_tx
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a327c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_tx_empty
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5aa8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6f0c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/arm64/include/asm/io.h:72
Inline: False
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c27dc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3708)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1db4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync
```
```
In drivers/iommu/arm-smmu-impl.c (ffff8000108d3168)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_smmu_read_ns
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d49c4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_priq_thread
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_evtq_thread
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d8b84)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
Direct callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108db37c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c4e4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092bdfc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/mfd/vexpress-sysreg.c (ffff80001094edc0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
```
In drivers/ata/libata-core.c (ffff800010998528)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
```
```
In drivers/ata/libata-sff.c (ffff8000109b069c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
```
```
In drivers/ata/ahci_imx.c (ffff8000109b82a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
Direct callers:
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
```
```
In drivers/ata/libahci.c (ffff8000109b98b8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_set_em_messages
  - drivers/ata/libahci.c:ahci_set_em_messages
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_handle_port_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_bad_pmp_check_ready
  - drivers/ata/libahci.c:ahci_bad_pmp_check_ready
  - drivers/ata/libahci.c:ahci_check_ready
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_dev_classify
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_reset_em
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_stop_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_scr_read
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
```
In drivers/ata/libahci_platform.c (ffff8000109bdb08)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_suspend_host
  - drivers/ata/libahci_platform.c:ahci_platform_suspend_host
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbe3c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd9cc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
Direct callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d9034)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops
  - drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops
  - drivers/net/phy/mdio-mux-bcm-iproc.c:iproc_mdio_wait_for_idle
```
```
In drivers/net/ethernet/broadcom/bgmac-platform.c (ffff8000109e4d7c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_idm_read
  - drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea6a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_update_ethtool_stats
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ec7d4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109ed780)
Location: arch/arm64/include/asm/io.h:72
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109f03f0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_get_revision
  - drivers/net/ethernet/freescale/fman/fman.c:fman_reset_mac
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:disable_rams_ecc
  - drivers/net/ethernet/freescale/fman/fman.c:enable_rams_ecc
```
```
In drivers/net/ethernet/freescale/fman/fman_keygen.c (ffff8000109f130c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_write_sp
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_write_ar_wait
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (ffff8000109f2b20)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f5f0c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_get_version
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_disable
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_enable
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_1588_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_1588_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:set_bucket
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:set_bucket
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f769c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_disable
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_enable
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_err_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_err_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:set_exception
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f88d4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_get_version
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_disable
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_enable
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_err_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_err_exception
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb9fc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a39978)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/phy/phy-ulpi-viewport.c (ffff800010a3a128)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_wait
```
```
In drivers/usb/dwc2/core.c (ffff800010a3c064)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3d580)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e3c4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/params.c (ffff800010a3f858)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a481a0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b14c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4caa4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e0b0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50f74)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
Direct callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5d498)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_clear_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_set_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_handshake
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffff800010a5e2b8)
Location: arch/arm64/include/asm/io.h:72
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-orion.c (ffff800010a5ed64)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a65bd4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_usb_reset
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/xhci.c (ffff800010a71f08)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_quiesce
  - drivers/usb/host/xhci.c:xhci_quiesce
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
Direct callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7acdc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
```
```
In drivers/usb/host/xhci-ext-caps.c (ffff800010a7ba18)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a80478)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a86d58)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_test_and_clear_bit
  - drivers/usb/host/xhci-hub.c:xhci_set_link_state
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8bd94)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a902a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a911d4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/rtc/rtc-mv.c (ffff800010aaca90)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_interrupt
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
Direct callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aaccf4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aadbd8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_gettime
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_get_parent
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_recalc_rate
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_recalc_rate
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aae32c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_suspend
  - drivers/rtc/rtc-xgene.c:xgene_rtc_alarm_irq_enable
  - drivers/rtc/rtc-xgene.c:xgene_rtc_read_alarm
  - drivers/rtc/rtc-xgene.c:xgene_rtc_set_time
  - drivers/rtc/rtc-xgene.c:xgene_rtc_read_time
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8b20)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abd1e0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr_thread
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr_thread
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae18bc)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_ping
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_stop
```
```
In drivers/edac/altera_edac.c (ffff800010b17cb0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:s10_edac_dberr_handler
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_check_ocram_deps_init
Direct callers:
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_memory_port
  - drivers/edac/altera_edac.c:altr_init_memory_port
```
```
In drivers/mmc/host/mmci.c (ffff800010b478a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_get_rx_fifocnt
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
  - drivers/mmc/host/mmci.c:mmci_set_mask1
  - drivers/mmc/host/mmci.c:mmci_dma_start
  - drivers/mmc/host/mmci.c:mmci_card_busy
```
```
In drivers/mmc/host/mmci_qcom_dml.c (ffff800010b47d30)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56864)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58b7c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63cd4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read32
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65b14)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/clocksource/mmio.c (ffff800010b66348)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/mmio.c:clocksource_mmio_readl_down
  - drivers/clocksource/mmio.c:clocksource_mmio_readl_up
```
```
In drivers/clocksource/timer-rockchip.c (ffff800010b664e0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_sched_read
```
```
In drivers/clocksource/timer-mediatek.c (ffff8000114a88ec)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_read_sched_clock
```
```
In drivers/clocksource/timer-owl.c (ffff800010b669d8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_shutdown
  - drivers/clocksource/timer-owl.c:owl_timer_sched_read
Direct callers:
  - drivers/clocksource/timer-owl.c:owl_timer_init
```
```
In drivers/clocksource/timer-sprd.c (ffff800010b66a74)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_disable
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_enable
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_read
  - drivers/clocksource/timer-sprd.c:sprd_timer_interrupt
  - drivers/clocksource/timer-sprd.c:sprd_timer_interrupt
  - drivers/clocksource/timer-sprd.c:sprd_timer_shutdown
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b673a0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_phys_mem
Direct callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq
```
```
In drivers/clocksource/timer-sp804.c (ffff800010b67fb0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-sp804.c:sp804_read
```
```
In drivers/clocksource/timer-versatile.c (ffff800010b68180)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-versatile.c:versatile_sys_24mhz_read
```
```
In drivers/clocksource/timer-imx-sysctr.c (ffff8000114aa24c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_timer_init
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7ae38)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:__ipc_rcv
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b0a4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_irq
```
```
In drivers/mailbox/pcc.c (ffff800010b7b6e4)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:read_register
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7c32c)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_last_tx_done
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_irq
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_irq
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7d050)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_send_data
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_last_tx_done
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_last_tx_done
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_peek_data
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_peek_data
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8ab54)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:show_vendor
  - drivers/memory/brcmstb_dpfe.c:show_vendor
  - drivers/memory/brcmstb_dpfe.c:show_vendor
  - drivers/memory/brcmstb_dpfe.c:show_vendor
  - drivers/memory/brcmstb_dpfe.c:show_vendor
  - drivers/memory/brcmstb_dpfe.c:show_refresh
  - drivers/memory/brcmstb_dpfe.c:show_refresh
  - drivers/memory/brcmstb_dpfe.c:show_refresh
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:__send_command
  - drivers/memory/brcmstb_dpfe.c:__send_command
  - drivers/memory/brcmstb_dpfe.c:__send_command
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b3e0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:check_nand_stat
  - drivers/memory/fsl_ifc.c:check_nand_stat
```
```
In drivers/memory/mtk-smi.c (ffff800010b8b9ac)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen1
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
```
```
In drivers/perf/arm-cci.c (ffff800010b90a00)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_event_update
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In drivers/perf/arm-ccn.c (ffff800010b937a8)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_irq_handler
  - drivers/perf/arm-ccn.c:arm_ccn_irq_handler
  - drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region
  - drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_overflow_handler
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_disable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_enable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96e30)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_disable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_enable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_disable_counter
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_enable_counter
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_stop_counters
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_start_counters
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_write_evtype
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b97688)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_disable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_enable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_disable_counter
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_enable_counter
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_stop_counters
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_start_counters
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_write_evtype
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97ed0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_disable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_enable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_disable_counter
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_enable_counter
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_stop_counters
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_start_counters
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_read_counter
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9ab04)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__handle_irq
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c8e0)
Location: arch/arm64/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_isr
  - drivers/perf/xgene_pmu.c:xgene_pmu_stop_counters
  - drivers/perf/xgene_pmu.c:xgene_pmu_start_counters
  - drivers/perf/xgene_pmu.c:xgene_pmu_reset_counters
  - drivers/perf/xgene_pmu.c:xgene_pmu_disable_counter_int
  - drivers/perf/xgene_pmu.c:xgene_pmu_enable_counter_int
  - drivers/perf/xgene_pmu.c:xgene_pmu_disable_counter
  - drivers/perf/xgene_pmu.c:xgene_pmu_enable_counter
  - drivers/perf/xgene_pmu.c:xgene_pmu_read_counter64
  - drivers/perf/xgene_pmu.c:xgene_pmu_read_counter64
  - drivers/perf/xgene_pmu.c:xgene_pmu_read_counter64
```
**Symbols:**

```
ffff80001066b6c8-ffff80001066b6d0: __raw_readl (STB_LOCAL)
ffff80001066d998-ffff80001066d9a0: __raw_readl (STB_LOCAL)
ffff80001066b088-ffff80001066b090: __raw_readl (STB_LOCAL)
ffff80001066d788-ffff80001066d790: __raw_readl (STB_LOCAL)
ffff80001066fdd0-ffff80001066fdd8: __raw_readl (STB_LOCAL)
ffff8000106f9fb8-ffff8000106f9fc0: __raw_readl (STB_LOCAL)
ffff80001070f898-ffff80001070f8a0: __raw_readl (STB_LOCAL)
ffff80001071f998-ffff80001071f9a0: __raw_readl (STB_LOCAL)
ffff8000107211d0-ffff8000107211d8: __raw_readl (STB_LOCAL)
ffff8000107232a0-ffff8000107232a8: __raw_readl (STB_LOCAL)
ffff800010723e90-ffff800010723e98: __raw_readl (STB_LOCAL)
ffff800010732380-ffff800010732388: __raw_readl (STB_LOCAL)
ffff800010759200-ffff800010759208: __raw_readl (STB_LOCAL)
ffff8000107c85a0-ffff8000107c85a8: __raw_readl (STB_LOCAL)
ffff8000107eadc8-ffff8000107eadd0: __raw_readl (STB_LOCAL)
ffff8000107eb808-ffff8000107eb810: __raw_readl (STB_LOCAL)
ffff8000107ec4e8-ffff8000107ec4f0: __raw_readl (STB_LOCAL)
ffff8000107ffa60-ffff8000107ffa68: __raw_readl (STB_LOCAL)
ffff800010805c28-ffff800010805c30: __raw_readl (STB_LOCAL)
ffff80001080dce0-ffff80001080dce8: __raw_readl (STB_LOCAL)
ffff80001080f494-ffff80001080f49c: __raw_readl (STB_LOCAL)
ffff80001080f4a0-ffff80001080f4a8: __raw_readl (STB_LOCAL)
ffff800010818768-ffff800010818770: __raw_readl (STB_LOCAL)
ffff80001081e174-ffff80001081e17c: __raw_readl (STB_LOCAL)
ffff800010899e48-ffff800010899e50: __raw_readl (STB_LOCAL)
ffff8000108d33a8-ffff8000108d33b0: __raw_readl (STB_LOCAL)
ffff8000108d7b60-ffff8000108d7b68: __raw_readl (STB_LOCAL)
ffff8000109b6cd0-ffff8000109b6cd8: __raw_readl (STB_LOCAL)
ffff8000109cc8d0-ffff8000109cc8d8: __raw_readl (STB_LOCAL)
ffff800010a4fa68-ffff800010a4fa70: __raw_readl (STB_LOCAL)
ffff800010a51760-ffff800010a51768: __raw_readl (STB_LOCAL)
ffff800010a5e2b8-ffff800010a5e2c0: __raw_readl (STB_LOCAL)
ffff800010a5eec8-ffff800010a5eed0: __raw_readl (STB_LOCAL)
ffff800010a6d448-ffff800010a6d450: __raw_readl (STB_LOCAL)
ffff800010a835f8-ffff800010a83600: __raw_readl (STB_LOCAL)
ffff800010aac820-ffff800010aac828: __raw_readl (STB_LOCAL)
ffff800010b15668-ffff800010b15670: __raw_readl (STB_LOCAL)
ffff800010b66890-ffff800010b66898: __raw_readl (STB_LOCAL)
ffff800010b66ca8-ffff800010b66cb0: __raw_readl (STB_LOCAL)
ffff800010b9ac80-ffff800010b9ac88: __raw_readl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_scu.c (c0314548)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/smp_scu.c:scu_enable
  - arch/arm/kernel/smp_scu.c:scu_enable
  - arch/arm/kernel/smp_scu.c:scu_get_core_count
```
```
In arch/arm/kernel/smp_twd.c (c0314a28)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_handler
  - arch/arm/kernel/smp_twd.c:twd_set_next_event
```
```
In arch/arm/kernel/io.c (c0319e30)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/io.c:atomic_io_modify
  - arch/arm/kernel/io.c:atomic_io_modify_relaxed
```
```
In arch/arm/mm/cache-feroceon-l2.c (c1509bd8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_of_init
```
```
In arch/arm/mm/cache-l2x0.c (c150afac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
  - arch/arm/mm/cache-l2x0.c:tauros3_configure
  - arch/arm/mm/cache-l2x0.c:tauros3_save
  - arch/arm/mm/cache-l2x0.c:tauros3_save
  - arch/arm/mm/cache-l2x0.c:tauros3_save
  - arch/arm/mm/cache-l2x0.c:aurora_save
  - arch/arm/mm/cache-l2x0.c:aurora_save
  - arch/arm/mm/cache-l2x0.c:aurora_disable
  - arch/arm/mm/cache-l2x0.c:__l2c_init
  - arch/arm/mm/cache-l2x0.c:__l2c_init
  - arch/arm/mm/cache-l2x0.c:__l2c_init
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_save
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c220_sync
  - arch/arm/mm/cache-l2x0.c:l2c220_flush_range
  - arch/arm/mm/cache-l2x0.c:l2c220_flush_range
  - arch/arm/mm/cache-l2x0.c:l2c220_clean_range
  - arch/arm/mm/cache-l2x0.c:l2c220_clean_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_op_pa_range
  - arch/arm/mm/cache-l2x0.c:l2c220_op_way
  - arch/arm/mm/cache-l2x0.c:l2c_resume
  - arch/arm/mm/cache-l2x0.c:l2c_disable
  - arch/arm/mm/cache-l2x0.c:l2c_enable
  - arch/arm/mm/cache-l2x0.c:l2c_enable
  - arch/arm/mm/cache-l2x0.c:__l2c_op_way
  - arch/arm/mm/cache-l2x0.c:l2x0_init
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c150b214)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_resume
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
```
```
In arch/arm/mm/cache-uniphier.c (c150b7b8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_sync
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_maint_all
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_range
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_range
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common
```
```
In arch/arm/mach-alpine/alpine_cpu_pm.c (c150c180)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-alpine/alpine_cpu_pm.c:alpine_cpu_pm_init
```
```
In arch/arm/mach-berlin/platsmp.c (c032cafc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-berlin/platsmp.c:berlin_cpu_kill
  - arch/arm/mach-berlin/platsmp.c:berlin_boot_secondary
```
```
In arch/arm/mach-exynos/exynos.c (c032cc14)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-exynos/firmware.c (c032d098)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-exynos/firmware.c:exynos_clear_boot_flag
  - arch/arm/mach-exynos/firmware.c:exynos_set_boot_flag
  - arch/arm/mach-exynos/firmware.c:exynos_get_cpu_boot_addr
```
```
In arch/arm/mach-exynos/pm.c (c032d3fc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
```
```
In arch/arm/mach-exynos/suspend.c (c032da8c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos_suspend_enter
  - arch/arm/mach-exynos/suspend.c:exynos_suspend_enter
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_init
```
```
In arch/arm/mach-exynos/platsmp.c (c032e700)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_get_boot_addr
  - arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_state
  - arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down
  - arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c150cb50)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_cpu_powerup
```
```
In arch/arm/mach-highbank/highbank.c (c032efcc)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In arch/arm/mach-hisi/platmcpm.c (c032f514)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
```
```
In arch/arm/mach-hisi/platsmp.c (c032f934)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hi3xxx_get_cpu_jump
```
```
In arch/arm/mach-hisi/hotplug.c (c032fd40)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-hisi/hotplug.c:hip01_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hip01_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
```
```
In arch/arm/mach-meson/platsmp.c (c0330768)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_die
  - arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot
  - arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot
```
```
In arch/arm/mach-mvebu/system-controller.c (c03308b8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_get_soc_id
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_get_soc_id
```
```
In arch/arm/mach-mvebu/mvebu-soc-id.c (c150d47c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
```
```
In arch/arm/mach-mvebu/cpu-reset.c (c0330a68)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_deassert
```
```
In arch/arm/mach-mvebu/coherency.c (c0330b1c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:armada_xp_clear_shared_l2
```
```
In arch/arm/mach-mvebu/pmsu.c (c0331328)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_exit
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_exit
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare
```
```
In arch/arm/mach-mvebu/pm.c (c03314c8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown
```
```
In arch/arm/mach-mvebu/pm-board.c (c0331788)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_enter
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_enter
```
```
In arch/arm/mach-imx/cpu.c (c150e630)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpu.c:imx_set_aips
```
```
In arch/arm/mach-imx/system.c (c150ea3c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/system.c:imx_init_l2cache
  - arch/arm/mach-imx/system.c:imx_init_l2cache
```
```
In arch/arm/mach-imx/cpu-imx5.c (c150eb34)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init
  - arch/arm/mach-imx/cpu-imx5.c:imx5_read_srev_reg
```
```
In arch/arm/mach-imx/pm-imx5.c (c0331fa8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
```
```
In arch/arm/mach-imx/tzic.c (c033225c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/tzic.c:tzic_enable_wake
  - arch/arm/mach-imx/tzic.c:tzic_enable_wake
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-imx/tzic.c:tzic_handle_irq
  - arch/arm/mach-imx/tzic.c:tzic_handle_irq
  - arch/arm/mach-imx/tzic.c:tzic_irq_resume
  - arch/arm/mach-imx/tzic.c:tzic_set_irq_fiq
```
```
In arch/arm/mach-imx/anatop.c (c150f054)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop
  - arch/arm/mach-imx/anatop.c:imx_init_revision_from_anatop
```
```
In arch/arm/mach-imx/gpc.c (c0332a68)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:imx_gpc_irq_mask
  - arch/arm/mach-imx/gpc.c:imx_gpc_irq_unmask
  - arch/arm/mach-imx/gpc.c:imx_gpc_mask_all
  - arch/arm/mach-imx/gpc.c:imx_gpc_pre_suspend
  - arch/arm/mach-imx/gpc.c:imx_gpc_set_l2_mem_power_in_lpm
```
```
In arch/arm/mach-imx/mmdc.c (c033320c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In arch/arm/mach-imx/src.c (c150f3d8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/src.c:imx_src_init
  - arch/arm/mach-imx/src.c:imx_get_cpu_arg
  - arch/arm/mach-imx/src.c:imx_enable_cpu
  - arch/arm/mach-imx/src.c:imx_src_reset_module
  - arch/arm/mach-imx/src.c:imx_src_reset_module
```
```
In arch/arm/mach-imx/pm-imx7ulp.c (c1510104)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx7ulp.c:imx7ulp_pm_init
```
```
In arch/arm/mach-imx/pm-imx6.c (c15105bc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_ccm_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-imx/pm-imx6.c:imx6_set_lpm
  - arch/arm/mach-imx/pm-imx6.c:imx6_enable_rbc
  - arch/arm/mach-imx/pm-imx6.c:imx6_enable_rbc
```
```
In arch/arm/mach-imx/mach-imx51.c (c15107a0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
```
```
In arch/arm/mach-omap2/id.c (c1511b2c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/id.c:dra7xxx_check_revision
  - arch/arm/mach-omap2/id.c:omap5xxx_check_revision
  - arch/arm/mach-omap2/id.c:omap4xxx_check_revision
  - arch/arm/mach-omap2/id.c:omap3xxx_check_revision
  - arch/arm/mach-omap2/id.c:omap4xxx_check_features
  - arch/arm/mach-omap2/id.c:omap2xxx_check_revision
  - arch/arm/mach-omap2/id.c:omap2xxx_check_revision
```
```
In arch/arm/mach-omap2/control.c (c0335994)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:am43xx_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf
  - arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_control_save_context
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap_ctrl_writeb
  - arch/arm/mach-omap2/control.c:omap_ctrl_readb
```
```
In arch/arm/mach-omap2/timer.c (c1512da0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:clocksource_read_cycles
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_next_event
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_next_event
```
```
In arch/arm/mach-omap2/dma.c (c15135e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/dma.c:omap2_show_dma_caps
```
```
In arch/arm/mach-omap2/wd_timer.c (c0336374)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/wd_timer.c:omap2_wd_timer_disable
  - arch/arm/mach-omap2/wd_timer.c:omap2_wd_timer_disable
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c0336b9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete
  - arch/arm/mach-omap2/omap_hwmod.c:_wait_softreset_complete
```
```
In arch/arm/mach-omap2/sdrc.c (c1514bb0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init
  - arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init
  - arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init
```
```
In arch/arm/mach-omap2/omap4-common.c (c033be74)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger
  - arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger
  - arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger
  - arch/arm/mach-omap2/omap4-common.c:gic_dist_disabled
  - arch/arm/mach-omap2/omap4-common.c:omap_interconnect_sync
  - arch/arm/mach-omap2/omap4-common.c:omap_interconnect_sync
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c151513c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:omap_wakeupgen_cpu_dead
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_sar_clear
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_unmask
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_mask
```
```
In arch/arm/mach-omap2/omap-smp.c (c1515414)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
```
```
In arch/arm/mach-omap2/omap-hotplug.c (c033cad8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-hotplug.c:omap4_cpu_die
```
```
In arch/arm/mach-omap2/ti81xx-restart.c (c033ceb8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/ti81xx-restart.c:ti81xx_restart
```
```
In arch/arm/mach-omap2/omap-mpuss-lowpower.c (c1515820)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d5ec)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
```
```
In arch/arm/mach-omap2/prm2xxx_3xxx.c (c0340780)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_clear_all_wkdeps
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_read_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_del_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_add_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_wait_transition
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_logic_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_read_mem_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_read_mem_pwrst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_assert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_is_hardreset_asserted
```
```
In arch/arm/mach-omap2/prm3xxx.c (c0340cb0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_disable_hdwr_sar
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_enable_hdwr_sar
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_mem_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_logic_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_logic_retst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_logic_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_next_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_save_scratchpad_contents
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_save_scratchpad_contents
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_read_reset_sources
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_save_and_clear_irqen
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_save_and_clear_irqen
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_ocp_barrier
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_read_pending_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_read_pending_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_rmw
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_read
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vp_check_txdone
```
```
In arch/arm/mach-omap2/cm3xxx.c (c0341a18)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_scratchpad_contents
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_save_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_deny_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_allow_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clear_all_sleepdeps
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_read_sleepdep
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_del_sleepdep
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_add_sleepdep
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_cm_wait_module_ready
```
```
In arch/arm/mach-omap2/cminst44xx.c (c0341b20)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_save_context
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_clk_disable
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_read_wkup_sleep_dep
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_del_wkup_sleep_dep
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_add_wkup_sleep_dep
  - arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_module_disable
  - arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_wait_module_idle
  - arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_wait_module_ready
  - arch/arm/mach-omap2/cminst44xx.c:_clktrctrl_write
```
```
In arch/arm/mach-omap2/prm44xx.c (c0342cdc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm44xx.c:prm_save_context
  - arch/arm/mach-omap2/prm44xx.c:prm_save_context
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_reset_sources
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_save_and_clear_irqen
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_save_and_clear_irqen
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_ocp_barrier
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_pending_irqs
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_read_pending_irqs
```
```
In arch/arm/mach-omap2/prcm_mpu44xx.c (c0342dcc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prcm_mpu44xx.c:omap4_prcm_mpu_rmw_inst_reg_bits
```
```
In arch/arm/mach-omap2/prminst44xx.c (c0343174)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset
```
```
In arch/arm/mach-omap2/prm33xx.c (c0343848)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_restore_context
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_save_context
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_global_warm_sw_reset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_global_warm_sw_reset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_mem_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_mem_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_logic_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_logic_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_logic_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_clear_all_prev_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_lowpwrstchange
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_next_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_assert_hardreset
```
```
In arch/arm/mach-omap2/cm33xx.c (c0343c08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_save_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm33xx.c:am33xx_cm_module_disable
  - arch/arm/mach-omap2/cm33xx.c:am33xx_cm_module_enable
  - arch/arm/mach-omap2/cm33xx.c:am33xx_cm_wait_module_idle
  - arch/arm/mach-omap2/cm33xx.c:am33xx_cm_wait_module_ready
```
```
In arch/arm/mach-omap2/powerdomains3xxx_data.c (c03467b4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_read_logic_pwrst
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_read_pwrst
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_read_next_pwrst
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_set_next_pwrst
```
```
In arch/arm/mach-shmobile/setup-rcar-gen2.c (c1519bcc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
```
```
In arch/arm/mach-shmobile/platsmp-apmu.c (c03497a8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_boot_secondary
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_cpu_kill
```
```
In arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c (c151a154)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
```
```
In arch/arm/mach-shmobile/pm-rcar-gen2.c (c151a474)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
```
```
In arch/arm/mach-shmobile/smp-sh73a0.c (c034a374)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_boot_secondary
```
```
In arch/arm/mach-shmobile/platsmp-scu.c (c034a48c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_cpu_kill
```
```
In arch/arm/mach-tegra/irq.c (c034a5d4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-tegra/irq.c:tegra_pending_sgi
```
```
In arch/arm/mach-tegra/reset.c (c151a998)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init
  - arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init
```
```
In arch/arm/mach-vexpress/dcscb.c (c151ae20)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/dcscb.c:dcscb_init
  - arch/arm/mach-vexpress/dcscb.c:dcscb_cluster_powerup
  - arch/arm/mach-vexpress/dcscb.c:dcscb_cpu_powerup
```
```
In arch/arm/mach-vexpress/spc.c (c034cfd0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:spc_recalc_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
  - arch/arm/mach-vexpress/spc.c:ve_spc_irq_handler
  - arch/arm/mach-vexpress/spc.c:ve_spc_cpu_in_wfi
  - arch/arm/mach-vexpress/spc.c:ve_spc_cpu_wakeup_irq
  - arch/arm/mach-vexpress/spc.c:ve_spc_global_wakeup_irq
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
```
```
In arch/arm/mach-vexpress/tc2_pm.c (c151b32c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_init
```
```
In arch/arm/plat-omap/counter_32k.c (c151b6b0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/plat-omap/counter_32k.c:omap_init_clocksource_32k
  - arch/arm/plat-omap/counter_32k.c:omap_read_persistent_clock64
  - arch/arm/plat-omap/counter_32k.c:omap_32k_read_sched_clock
```
```
In arch/arm/plat-samsung/cpu.c (c151b924)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/plat-samsung/cpu.c:s5p_init_cpu
  - arch/arm/plat-samsung/cpu.c:s3c64xx_init_cpu
  - arch/arm/plat-samsung/cpu.c:s3c64xx_init_cpu
```
```
In arch/arm/plat-samsung/pm-common.c (c034f988)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - arch/arm/plat-samsung/pm-common.c:s3c_pm_do_restore
  - arch/arm/plat-samsung/pm-common.c:s3c_pm_do_save
```
```
In kernel/irq/generic-chip.c (c03d0970)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_init_mask_cache
  - kernel/irq/generic-chip.c:irq_readl_be
```
```
In fs/debugfs/file.c (c06d29cc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_print_regs32
```
```
In lib/iomap_copy.c (c07e3ad0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In lib/stmp_device.c (c0810194)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_clear_poll_bit
```
```
In drivers/irqchip/irq-al-fic.c (c0812fa0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/exynos-combiner.c (c081377c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_suspend
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
```
```
In drivers/irqchip/irq-hip04.c (c1549c08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-hip04.c:hip04_handle_irq
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
```
```
In drivers/irqchip/irq-tegra.c (c0814098)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c154a05c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-orion.c (c0814638)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_handler
  - drivers/irqchip/irq-orion.c:orion_handle_irq
```
```
In drivers/irqchip/irq-omap-intc.c (c154a9d0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq
  - drivers/irqchip/irq-omap-intc.c:omap_irq_pending
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_intc_save_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_save_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_save_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_save_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_save_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_save_context
```
```
In drivers/irqchip/irq-gic.c (c154aeb8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_dist_save
  - drivers/irqchip/irq-gic.c:gic_cpu_if_down
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_get_cpumask
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-common.c (c081616c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b288)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (c154c054)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:__gic_update_rdist_properties
  - drivers/irqchip/irq-gic-v3.c:__gic_update_rdist_properties
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists
  - drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists
  - drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists
  - drivers/irqchip/irq-gic-v3.c:gic_peek_irq
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cc38)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_inv
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
  - drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_entry
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d460)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_suspend
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_smp_cpu_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
```
```
In drivers/irqchip/irq-rda-intc.c (c03027e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda_handle_irq
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ed08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read32
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fe7c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c0820e44)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-mtk-cirq.c (c0821220)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c08219a4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
  - drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_save
```
```
In drivers/irqchip/irq-aspeed-vic.c (c154e5c0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq
  - drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (c0821cb8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0821df0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_suspend
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_irq_set_type
```
```
In drivers/irqchip/irq-meson-gpio.c (c0822440)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (c082279c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:pdc_enable_intr
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c0822edc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/arm-cci.c (c0823654)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/bus/brcmstb_gisb.c (c0823ef0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_suspend
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_suspend
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:gisb_arb_get_timeout
  - drivers/bus/brcmstb_gisb.c:gisb_arb_get_timeout
```
```
In drivers/bus/imx-weim.c (c0824418)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
```
```
In drivers/bus/mvebu-mbus.c (c0824c80)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dove_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dove_setup_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_setup_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_setup_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_show_dove
  - drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_show_orion
  - drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_show_orion
```
```
In drivers/bus/omap_l3_noc.c (c0825e9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:l3_resume_noirq
  - drivers/bus/omap_l3_noc.c:l3_resume_noirq
  - drivers/bus/omap_l3_noc.c:l3_resume_noirq
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
```
```
In drivers/bus/qcom-ebi2.c (c0826658)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/bus/ti-sysc.c (c08289e0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_clk_quirk_i2c
  - drivers/bus/ti-sysc.c:sysc_pre_reset_quirk_hdq1w
  - drivers/bus/ti-sysc.c:sysc_disable_module
  - drivers/bus/ti-sysc.c:sysc_enable_module
  - drivers/bus/ti-sysc.c:sysc_read_sysstatus
  - drivers/bus/ti-sysc.c:sysc_read_sysconfig
```
```
In drivers/bus/uniphier-system-bus.c (c08299e8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
```
```
In drivers/phy/marvell/phy-armada375-usb2.c (c082bbac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_init
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082be5c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c78c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cc90)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init
```
```
In drivers/pinctrl/pinctrl-amd.c (c08343a8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083a288)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083d288)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_get
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_get
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
```
```
In drivers/pinctrl/pinctrl-single.c (c083e3e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readl
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c0843148)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_resume
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_suspend
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_dbg_show
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_set
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_set
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_get
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_set_mux
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_set_mux
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c08434b0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_off
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_off
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinconf_group_set
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinconf_group_get
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinmux_set
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0845c24)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c084894c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_dbg_show
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
```
```
In drivers/pinctrl/freescale/pinctrl-imx7ulp.c (c0849b9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx7ulp.c:imx7ulp_pmx_gpio_set_direction
```
```
In drivers/pinctrl/freescale/pinctrl-vf610.c (c0849c40)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-vf610.c:vf610_pmx_gpio_set_direction
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a848)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_get
```
```
In drivers/pinctrl/mvebu/pinctrl-dove.c (c084b964)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio0_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio0_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_mpp4_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_mpp4_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_get
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_get
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-xp.c (c084c144)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-xp.c:armada_xp_pinctrl_suspend
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084ce98)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084ee3c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_get_direction
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c08502b8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_suspend
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_suspend
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_direction
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_get
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_value
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinconf_rw
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinmux_set_mux
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852b70)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_suspend
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_irq
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_release_resources
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_request_resources
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_unmask
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_mask
```
```
In drivers/pinctrl/samsung/pinctrl-exynos-arm.c (c0852d70)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos-arm.c:s5pv210_retention_disable
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853530)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7778.c (c08559d8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_get_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855adc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_is_enabled
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858b8c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085bc70)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_get_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
```
In drivers/gpio/gpio-mmio.c (c0867f9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/gpio/gpio-mmio.c:bgpio_read32
```
```
In drivers/gpio/gpio-ftgpio010.c (c08687c4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
```
```
In drivers/gpio/gpio-mvebu.c (c0869df8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_suspend
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
```
```
In drivers/gpio/gpio-mxc.c (c086bd54)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
```
```
In drivers/gpio/gpio-omap.c (c086d6ac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_unidle
  - drivers/gpio/gpio-omap.c:omap_gpio_set_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_set_config
  - drivers/gpio/gpio-omap.c:omap_gpio_get_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_get_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_get_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_output
  - drivers/gpio/gpio-omap.c:omap_gpio_get
  - drivers/gpio/gpio-omap.c:omap_gpio_get
  - drivers/gpio/gpio-omap.c:omap_gpio_input
  - drivers/gpio/gpio-omap.c:omap_gpio_get_direction
  - drivers/gpio/gpio-omap.c:omap_gpio_free
  - drivers/gpio/gpio-omap.c:omap_gpio_free
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_mask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_mask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_startup
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
  - drivers/gpio/gpio-omap.c:omap_enable_gpio_module
  - drivers/gpio/gpio-omap.c:omap_enable_gpio_module
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_dataout_mask
```
```
In drivers/gpio/gpio-tegra.c (c0871b94)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_show
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_get_direction
  - drivers/gpio/gpio-tegra.c:tegra_gpio_get_direction
  - drivers/gpio/gpio-tegra.c:tegra_gpio_get
  - drivers/gpio/gpio-tegra.c:tegra_gpio_get
```
```
In drivers/gpio/gpio-vf610.c (c08735c0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_input
  - drivers/gpio/gpio-vf610.c:vf610_gpio_get
  - drivers/gpio/gpio-vf610.c:vf610_gpio_get
```
```
In drivers/gpio/gpio-xilinx.c (c0873cfc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_get
```
```
In drivers/gpio/gpio-zevio.c (c08743e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_input
  - drivers/gpio/gpio-zevio.c:zevio_gpio_set
  - drivers/gpio/gpio-zevio.c:zevio_gpio_get
  - drivers/gpio/gpio-zevio.c:zevio_gpio_get
```
```
In drivers/pci/access.c (c0877478)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_read32
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c0889e94)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c088a460)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c08951c0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/msi.c (c089ff9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6798)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7898)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a8260)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9cdc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_suspend
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_wr_conf
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_base_conf_write
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_read
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
```
```
In drivers/pci/controller/pci-tegra.c (c08aca78)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_show
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_show
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_isr
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_isr
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_isr
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_disable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_disable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_disable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_enable
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08ada74)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
```
```
In drivers/pci/controller/pcie-rcar.c (c08ae0f4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_wait_for_dl
  - drivers/pci/controller/pcie-rcar.c:phy_wait_for_ack
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b02b8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b0ed4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b2170)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:s10_rp_read_cfg
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:altera_pcie_link_up
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2e18)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
```
```
In drivers/pci/controller/pcie-rockchip.c (c08b3648)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b47ac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_get_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5520)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
```
```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6610)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9214)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c1552390)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_irq_handler
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_stop_link
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_link_up
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bdd5c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_3_2_ltssm_enable
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_1_0_ltssm_enable
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08be5f8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_link_up
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_r_mode
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf2b0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_unmask
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_mask
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_ack
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_stop_link
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_establish_link
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_link_up
```
```
In drivers/video/fbdev/core/cfbfillrect.c (c08da510)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (c08dabc8)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/video/fbdev/core/cfbimgblt.c (c08dbf58)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/video/fbdev/imsttfb.c (c08dda1c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
```
```
In drivers/video/fbdev/amba-clcd.c (c08de490)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_setcolreg
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/video/fbdev/mx3fb.c (c08e3378)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/amba/bus.c (c08e58f4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/amba/tegra-ahb.c (c08e60fc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_suspend
  - drivers/amba/tegra-ahb.c:tegra_ahb_enable_smmu
```
```
In drivers/clk/clk-divider.c (c08ef99c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (c08f0e48)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (c08f1070)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (c08f1618)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (c08f2164)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/clk/clk-fixed-mmio.c (c08f2e08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
```
```
In drivers/clk/clk-highbank.c (c08f455c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-highbank.c:clk_periclk_recalc_rate
  - drivers/clk/clk-highbank.c:clk_cpu_a9bclk_recalc_rate
  - drivers/clk/clk-highbank.c:clk_cpu_periphclk_recalc_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_recalc_rate
  - drivers/clk/clk-highbank.c:clk_pll_disable
  - drivers/clk/clk-highbank.c:clk_pll_enable
  - drivers/clk/clk-highbank.c:clk_pll_unprepare
  - drivers/clk/clk-highbank.c:clk_pll_prepare
  - drivers/clk/clk-highbank.c:clk_pll_prepare
  - drivers/clk/clk-highbank.c:clk_pll_prepare
```
```
In drivers/clk/clk-hsdk-pll.c (c08f4dcc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate
```
```
In drivers/clk/clk-milbeaut.c (c08f4e7c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_recalc_rate
  - drivers/clk/clk-milbeaut.c:m10v_mux_set_parent
  - drivers/clk/clk-milbeaut.c:m10v_mux_get_parent
```
```
In drivers/clk/clk-npcm7xx.c (c08f55bc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_pll_recalc_rate
```
```
In drivers/clk/clk-qoriq.c (c155601c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:p5040_init_periph
  - drivers/clk/clk-qoriq.c:p5020_init_periph
  - drivers/clk/clk-qoriq.c:p4080_init_periph
  - drivers/clk/clk-qoriq.c:p2041_init_periph
```
```
In drivers/clk/berlin/berlin2-avpll.c (c08f6df0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_enable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_is_enabled
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_recalc_rate
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_enable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_is_enabled
```
```
In drivers/clk/berlin/berlin2-pll.c (c08f7018)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate
  - drivers/clk/berlin/berlin2-pll.c:berlin2_pll_recalc_rate
```
```
In drivers/clk/berlin/berlin2-div.c (c08f73dc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled
```
```
In drivers/clk/hisilicon/clkgate-separated.c (c08f7cf0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_is_enabled
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (c08f7e80)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_recalc_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (c08f8204)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_get_phase
```
```
In drivers/clk/hisilicon/clk-hi3620.c (c08f8550)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
```
```
In drivers/clk/hisilicon/clk-hix5hd2.c (c08f889c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_disable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_disable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_enable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_enable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_unprepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
```
```
In drivers/clk/hisilicon/reset.c (c08f8ec8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/hisilicon/clk-hi3660-stub.c (c08f94e8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_recalc_rate
```
```
In drivers/clk/imx/clk.c (c1557ec4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_mmdc_mask_handshake
```
```
In drivers/clk/imx/clk-busy.c (c08f9954)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/clk/imx/clk-composite-8m.c (c08f9db0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_recalc_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (c08fa784)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:imx_clk_divider_gate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_is_enabled
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate_ro
```
```
In drivers/clk/imx/clk-fixup-div.c (c08fa8a0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (c08faab0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-frac-pll.c (c08fae08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_recalc_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_is_prepared
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_unprepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-gate-exclusive.c (c08fb058)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate-exclusive.c:clk_gate_exclusive_enable
```
```
In drivers/clk/imx/clk-gate2.c (c08fb264)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_is_enabled
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfd.c (c08fb560)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfd.c:clk_pfd_is_enabled
  - drivers/clk/imx/clk-pfd.c:clk_pfd_recalc_rate
```
```
In drivers/clk/imx/clk-pfdv2.c (c08fba64)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_is_enabled
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_recalc_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv1.c (c08fbc94)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv1.c:clk_pllv1_recalc_rate
```
```
In drivers/clk/imx/clk-pllv2.c (c08fbe5c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_unprepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
```
```
In drivers/clk/imx/clk-pllv3.c (c08fc6e0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_recalc_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_is_prepared
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_unprepare
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock
```
```
In drivers/clk/imx/clk-pllv4.c (c08fcd28)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_disable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_recalc_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_is_enabled
```
```
In drivers/clk/imx/clk-sccg-pll.c (c08fd360)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_get_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_recalc_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_unprepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_is_prepared
```
```
In drivers/clk/imx/clk-pll14xx.c (c08fe36c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_unprepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_is_prepared
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_recalc_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_recalc_rate
```
```
In drivers/clk/imx/clk-imx5.c (c155bac4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
```
```
In drivers/clk/imx/clk-imx6q.c (c155dd4c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
```
```
In drivers/clk/imx/clk-imx6sl.c (c08fe708)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
```
```
In drivers/clk/imx/clk-vf610.c (c08fe840)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/imx/clk-vf610.c:vf610_clk_suspend
  - drivers/clk/imx/clk-vf610.c:vf610_clk_suspend
  - drivers/clk/imx/clk-vf610.c:vf610_clk_suspend
  - drivers/clk/imx/clk-vf610.c:vf610_clk_suspend
  - drivers/clk/imx/clk-vf610.c:vf610_clk_suspend
  - drivers/clk/imx/clk-vf610.c:vf610_clk_suspend
```
```
In drivers/clk/mediatek/clk-pll.c (c08ff3ac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_unprepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_recalc_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_is_prepared
```
```
In drivers/clk/mediatek/clk-apmixed.c (c08fff28)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_unprepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_is_prepared
```
```
In drivers/clk/mvebu/common.c (c0903398)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_suspend
  - drivers/clk/mvebu/common.c:kirkwood_fix_sscg_deviation
```
```
In drivers/clk/mvebu/clk-cpu.c (c0903680)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_recalc_rate
```
```
In drivers/clk/mvebu/clk-corediv.c (c0903910)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_recalc_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_disable
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_enable
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_is_enabled
```
```
In drivers/clk/mvebu/armada-370.c (c0903b00)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-370.c:a370_is_sscg_enabled
  - drivers/clk/mvebu/armada-370.c:a370_get_clk_ratio
  - drivers/clk/mvebu/armada-370.c:a370_get_cpu_freq
  - drivers/clk/mvebu/armada-370.c:a370_get_tclk_freq
```
```
In drivers/clk/mvebu/armada-375.c (c157d8f4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-375.c:armada_375_get_clk_ratio
  - drivers/clk/mvebu/armada-375.c:armada_375_get_cpu_freq
  - drivers/clk/mvebu/armada-375.c:armada_375_get_tclk_freq
```
```
In drivers/clk/mvebu/armada-38x.c (c157da2c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-38x.c:armada_38x_get_clk_ratio
  - drivers/clk/mvebu/armada-38x.c:armada_38x_get_cpu_freq
  - drivers/clk/mvebu/armada-38x.c:armada_38x_get_tclk_freq
```
```
In drivers/clk/mvebu/armada-39x.c (c157dba8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-39x.c:armada_39x_refclk_ratio
  - drivers/clk/mvebu/armada-39x.c:armada_39x_get_cpu_freq
  - drivers/clk/mvebu/armada-39x.c:armada_39x_get_tclk_freq
```
```
In drivers/clk/mvebu/armada-xp.c (c157dc98)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-xp.c:axp_get_clk_ratio
  - drivers/clk/mvebu/armada-xp.c:axp_get_clk_ratio
  - drivers/clk/mvebu/armada-xp.c:axp_get_cpu_freq
  - drivers/clk/mvebu/armada-xp.c:axp_get_cpu_freq
```
```
In drivers/clk/mvebu/mv98dx3236.c (c157de90)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_cpu_freq
```
```
In drivers/clk/mvebu/dove.c (c157e0bc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/dove.c:dove_get_clk_ratio
  - drivers/clk/mvebu/dove.c:dove_get_clk_ratio
  - drivers/clk/mvebu/dove.c:dove_get_cpu_freq
  - drivers/clk/mvebu/dove.c:dove_get_tclk_freq
```
```
In drivers/clk/mvebu/dove-divider.c (c0903d9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
  - drivers/clk/mvebu/dove-divider.c:dove_recalc_rate
```
```
In drivers/clk/renesas/clk-rz.c (c157e90c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
```
```
In drivers/clk/renesas/r7s9210-cpg-mssr.c (c157ead0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/r7s9210-cpg-mssr.c:rza2_cpg_clk_register
```
```
In drivers/clk/renesas/clk-r8a7740.c (c157eecc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (c0903f84)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_dualgate_setenable
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_mux_get_parent
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_div_recalc_rate
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_is_enabled
  - drivers/clk/renesas/r9a06g032-clocks.c:clk_rdesc_set
```
```
In drivers/clk/renesas/clk-sh73a0.c (c1580374)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (c1580be8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_register_clock
  - drivers/clk/renesas/clk-rcar-gen2.c:cpg_z_clk_recalc_rate
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (c1580e60)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen2-cpg.c:rcar_gen2_cpg_clk_register
  - drivers/clk/renesas/rcar-gen2-cpg.c:cpg_z_clk_recalc_rate
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c09058b0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_status
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-mstp.c (c09059a8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_is_enabled
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-div6.c (c1582090)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_parent
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_rate
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_is_enabled
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_disable
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_enable
```
```
In drivers/clk/rockchip/clk-pll.c (c09064f8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_is_enabled
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_is_enabled
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_recalc_rate
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_is_enabled
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_get_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_get_params
```
```
In drivers/clk/rockchip/clk-cpu.c (c0907dd8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_recalc_rate
```
```
In drivers/clk/rockchip/clk-half-divider.c (c0908770)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_recalc_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (c0908b6c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_get_phase
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (c0908d44)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_mmc_get_phase
```
```
In drivers/clk/rockchip/clk-ddr.c (c09092f8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_get_parent
```
```
In drivers/clk/rockchip/softrst.c (c0909694)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/rockchip/clk-rk3288.c (c09097a8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend
```
```
In drivers/clk/samsung/clk.c (c0909924)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/samsung/clk.c:samsung_clk_suspend
```
```
In drivers/clk/samsung/clk-pll.c (c0909d88)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550x_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_upll_disable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_upll_enable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_mpll_disable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_mpll_enable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2440_mpll_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_pll_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll6553_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll6553_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll6552_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll35xx_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll3000_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2126_recalc_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_disable
  - drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_enable
  - drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_enable
```
```
In drivers/clk/samsung/clk-cpu.c (c090b55c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_set_safe_div
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c090b788)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_resume
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_clk_save
```
```
In drivers/clk/samsung/clk-exynos-clkout.c (c090b890)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_suspend
```
```
In drivers/clk/tegra/clk-dfll.c (c090c264)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:attr_registers_show
  - drivers/clk/tegra/clk-dfll.c:attr_registers_show
  - drivers/clk/tegra/clk-dfll.c:attr_registers_show
  - drivers/clk/tegra/clk-dfll.c:attr_registers_show
  - drivers/clk/tegra/clk-dfll.c:attr_registers_show
  - drivers/clk/tegra/clk-dfll.c:attr_registers_show
  - drivers/clk/tegra/clk-dfll.c:attr_rate_get
  - drivers/clk/tegra/clk-dfll.c:attr_rate_get
  - drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config
  - drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config
  - drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config
  - drivers/clk/tegra/clk-dfll.c:dfll_enable
  - drivers/clk/tegra/clk-dfll.c:dfll_disable
```
```
In drivers/clk/tegra/clk-divider.c (c090dac8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-divider.c:clk_frac_div_set_rate
  - drivers/clk/tegra/clk-divider.c:clk_frac_div_recalc_rate
```
```
In drivers/clk/tegra/clk-periph-fixed.c (c090e1c4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_periph_fixed_is_enabled
  - drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_periph_fixed_is_enabled
```
```
In drivers/clk/tegra/clk-periph-gate.c (c090e774)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-periph-gate.c:tegra_clk_register_periph_gate
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_is_enabled
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_is_enabled
```
```
In drivers/clk/tegra/clk-pll.c (c0911db8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle_tegra114
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle_tegra114
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_tegra114_enable
  - drivers/clk/tegra/clk-pll.c:clk_plle_tegra114_disable
  - drivers/clk/tegra/clk-pll.c:_clk_pllc_disable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_enable
  - drivers/clk/tegra/clk-pll.c:clk_pllu_enable
  - drivers/clk/tegra/clk-pll.c:clk_plle_recalc_rate
  - drivers/clk/tegra/clk-pll.c:clk_pll_recalc_rate
  - drivers/clk/tegra/clk-pll.c:_program_pll
  - drivers/clk/tegra/clk-pll.c:_program_pll
  - drivers/clk/tegra/clk-pll.c:_program_pll
  - drivers/clk/tegra/clk-pll.c:_get_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_get_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_get_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_get_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_get_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_get_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_update_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_update_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_update_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_update_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_update_pll_mnp
  - drivers/clk/tegra/clk-pll.c:_update_pll_mnp
  - drivers/clk/tegra/clk-pll.c:clk_pll_disable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_disable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_disable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_disable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_disable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_enable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_enable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_enable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_enable
  - drivers/clk/tegra/clk-pll.c:_clk_pll_enable
  - drivers/clk/tegra/clk-pll.c:clk_pll_is_enabled
  - drivers/clk/tegra/clk-pll.c:clk_pll_is_enabled
  - drivers/clk/tegra/clk-pll.c:clk_pll_wait_for_lock
```
```
In drivers/clk/tegra/clk-pll-out.c (c09120a8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-pll-out.c:clk_pll_out_disable
  - drivers/clk/tegra/clk-pll-out.c:clk_pll_out_enable
  - drivers/clk/tegra/clk-pll-out.c:clk_pll_out_is_enabled
```
```
In drivers/clk/tegra/clk-sdmmc-mux.c (c09124f4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_set_rate
  - drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_recalc_rate
  - drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_set_parent
  - drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_get_parent
```
```
In drivers/clk/tegra/clk-super.c (c091283c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-super.c:clk_super_set_parent
```
```
In drivers/clk/tegra/clk-tegra-fixed.c (c1586c74)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra-fixed.c:tegra_osc_clk_init
```
```
In drivers/clk/tegra/clk-emc.c (c0913584)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
  - drivers/clk/tegra/clk-emc.c:emc_set_rate
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/clk/tegra/clk-emc.c:emc_recalc_rate
```
```
In drivers/clk/tegra/clk-tegra20.c (c15876c0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init
  - drivers/clk/tegra/clk-tegra20.c:tegra20_clock_init
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_rail_off_ready
  - drivers/clk/tegra/clk-tegra20.c:tegra20_disable_cpu_clock
  - drivers/clk/tegra/clk-tegra20.c:tegra20_enable_cpu_clock
  - drivers/clk/tegra/clk-tegra20.c:tegra20_enable_cpu_clock
  - drivers/clk/tegra/clk-tegra20.c:tegra20_wait_cpu_in_reset
  - drivers/clk/tegra/clk-tegra20.c:tegra20_periph_clk_init
```
```
In drivers/clk/tegra/clk-tegra30.c (c0913dc8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_rail_off_ready
  - drivers/clk/tegra/clk-tegra30.c:tegra30_disable_cpu_clock
  - drivers/clk/tegra/clk-tegra30.c:tegra30_enable_cpu_clock
  - drivers/clk/tegra/clk-tegra30.c:tegra30_wait_cpu_in_reset
```
```
In drivers/clk/tegra/clk-tegra114.c (c0914230)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_deassert_dfll_dvco_reset
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_deassert_dfll_dvco_reset
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_assert_dfll_dvco_reset
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_assert_dfll_dvco_reset
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_init
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_high
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra114.c:tegra114_wait_cpu_in_reset
```
```
In drivers/clk/tegra/clk-tegra124.c (c1589830)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre
  - drivers/clk/tegra/clk-tegra124.c:tegra124_reset_deassert
  - drivers/clk/tegra/clk-tegra124.c:tegra124_reset_deassert
  - drivers/clk/tegra/clk-tegra124.c:tegra124_reset_assert
  - drivers/clk/tegra/clk-tegra124.c:tegra124_reset_assert
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra124.c:tegra124_wait_cpu_in_reset
```
```
In drivers/clk/ti/clk.c (c0915960)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/ti/clk.c:clk_memmap_readl
  - drivers/clk/ti/clk.c:clk_memmap_readl
  - drivers/clk/ti/clk.c:clk_memmap_rmw
  - drivers/clk/ti/clk.c:clk_memmap_rmw
```
```
In drivers/clk/ti/fapll.c (c158d438)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_round_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_round_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_set_frac_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_is_enabled
  - drivers/clk/ti/fapll.c:ti_fapll_synth_disable
  - drivers/clk/ti/fapll.c:ti_fapll_synth_enable
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_get_parent
  - drivers/clk/ti/fapll.c:ti_fapll_recalc_rate
  - drivers/clk/ti/fapll.c:ti_fapll_recalc_rate
  - drivers/clk/ti/fapll.c:ti_fapll_disable
  - drivers/clk/ti/fapll.c:ti_fapll_enable
```
```
In drivers/clk/ti/adpll.c (c091b9d0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_clkout_get_parent
  - drivers/clk/ti/adpll.c:ti_adpll_is_prepared
  - drivers/clk/ti/adpll.c:ti_adpll_unprepare
  - drivers/clk/ti/adpll.c:ti_adpll_prepare
  - drivers/clk/ti/adpll.c:ti_adpll_prepare
```
```
In drivers/clk/versatile/clk-sp810.c (c091d434)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_get_parent
```
```
In drivers/dma/amba-pl08x.c (c0921dac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
```
```
In drivers/dma/mv_xor.c (c0923b84)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_suspend
  - drivers/dma/mv_xor.c:mv_xor_suspend
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_add_io_win
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mxs-dma.c (c0926230)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_tx_status
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
```
```
In drivers/dma/ipu/ipu_irq.c (c0927008)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (c0927f50)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
```
```
In drivers/dma/tegra20-apb-dma.c (c0929db4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_stop
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_stop
```
```
In drivers/dma/ti/edma.c (c092caa8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_xbar_event_map
  - drivers/dma/ti/edma.c:edma_alloc_chan_resources
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:edma_assign_channel_eventq
  - drivers/dma/ti/edma.c:edma_clean_channel
  - drivers/dma/ti/edma.c:edma_trigger_channel
  - drivers/dma/ti/edma.c:edma_stop
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_link
```
```
In drivers/dma/ti/omap-dma.c (c093111c)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/soc/actions/owl-sps-helper.c (c09338d4)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/soc/dove/pmu.c (c158f824)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:dove_init_pmu
  - drivers/soc/dove/pmu.c:dove_init_pmu_legacy
  - drivers/soc/dove/pmu.c:pmu_irq_handler
  - drivers/soc/dove/pmu.c:pmu_irq_handler
  - drivers/soc/dove/pmu.c:pmu_domain_power_on
  - drivers/soc/dove/pmu.c:pmu_domain_power_on
  - drivers/soc/dove/pmu.c:pmu_domain_power_on
  - drivers/soc/dove/pmu.c:pmu_domain_power_off
  - drivers/soc/dove/pmu.c:pmu_domain_power_off
  - drivers/soc/dove/pmu.c:pmu_domain_power_off
  - drivers/soc/dove/pmu.c:pmu_reset_deassert
  - drivers/soc/dove/pmu.c:pmu_reset_assert
  - drivers/soc/dove/pmu.c:pmu_reset_reset
```
```
In drivers/soc/fsl/guts.c (c0934030)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/imx/soc-imx8.c (c158fa18)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mm_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
  - drivers/soc/imx/soc-imx8.c:imx8mq_soc_revision
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935cf0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_domain_is_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_domain_is_on
```
```
In drivers/soc/qcom/spm.c (c0937f00)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:spm_set_low_power_mode
  - drivers/soc/qcom/spm.c:spm_set_low_power_mode
```
```
In drivers/soc/renesas/renesas-soc.c (c15906c8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/soc/renesas/rcar-rst.c (c1590ac4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins
```
```
In drivers/soc/renesas/rcar-sysc.c (c1590e58)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/soc/renesas/rmobile-sysc.c (c0938b98)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up
  - drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up
  - drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939e30)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-pmu.c:pmu_raw_readl
```
```
In drivers/soc/samsung/pm_domains.c (c1591a40)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c1591d08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
```
```
In drivers/soc/tegra/fuse/fuse-tegra30.c (c093a530)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read_early
```
```
In drivers/soc/tegra/fuse/tegra-apbmisc.c (c15920dc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_revision
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_read_ram_code
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_get_chip_id
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a718)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read_early
```
```
In drivers/soc/tegra/flowctrl.c (c093ac20)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_read_cpu_csr
  - drivers/soc/tegra/flowctrl.c:flowctrl_update
```
```
In drivers/soc/tegra/pmc.c (c1593060)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity
  - drivers/soc/tegra/pmc.c:tegra20_pmc_setup_irq_polarity
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_type
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_wake
  - drivers/soc/tegra/pmc.c:reset_level_show
  - drivers/soc/tegra/pmc.c:reset_reason_show
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_powergate_is_powered
  - drivers/soc/tegra/pmc.c:tegra_powergate_is_powered
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
```
```
In drivers/virtio/virtio_mmio.c (c0944b64)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_get_status
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
```
```
In drivers/virtio/virtio_pci_modern.c (c09451a8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946de4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
```
In drivers/regulator/ti-abb-regulator.c (c0956204)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_clear_all_txdone
  - drivers/regulator/ti-abb-regulator.c:ti_abb_clear_all_txdone
```
```
In drivers/reset/reset-meson.c (c0959d6c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_deassert
  - drivers/reset/reset-meson.c:meson_reset_assert
```
```
In drivers/reset/reset-simple.c (c0959fbc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_status
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/serial/8250/8250_port.c (c0984f28)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_in
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c0989d0c)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (c098aedc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (c098cdd4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/amba-pl011.c (c098f464)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_putc
  - drivers/tty/serial/amba-pl011.c:pl011_putc
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_get_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_tx_empty
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
```
```
In drivers/tty/serial/imx.c (c09951e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_early_putchar
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_poll_get_char
  - drivers/tty/serial/imx.c:imx_uart_poll_get_char
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_tx_empty
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_get_hwmctrl
  - drivers/tty/serial/imx.c:imx_uart_get_hwmctrl
  - drivers/tty/serial/imx.c:imx_uart_get_hwmctrl
```
```
In drivers/tty/serial/meson_uart.c (c0999394)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_serial_early_console_setup
  - drivers/tty/serial/meson_uart.c:meson_serial_console_setup
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/meson_uart.c:meson_uart_stop_rx
```
```
In drivers/tty/serial/msm_serial.c (c099bf48)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_poll_get_char
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_tx_empty
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/tty/serial/omap-serial.c (c09a01bc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1860)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_get_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_isr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty
```
```
In drivers/tty/serial/owl-uart.c (c09a280c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_get_mctrl
  - drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl
```
```
In drivers/tty/serial/rda-uart.c (c09a36c8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
  - drivers/tty/serial/rda-uart.c:rda_uart_shutdown
  - drivers/tty/serial/rda-uart.c:rda_uart_startup
  - drivers/tty/serial/rda-uart.c:rda_uart_startup
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_rx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_rx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_rx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_tx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_tx
  - drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_get_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_get_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_tx_empty
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (c09baf20)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c1c84)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_tlb_invalidate
```
```
In drivers/iommu/omap-iommu.c (c09c31ec)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:iommu_fault_handler
  - drivers/iommu/omap-iommu.c:iommu_fault_handler
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:omap_iommu_save_ctx
```
```
In drivers/iommu/rockchip-iommu.c (c09c5e9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
```
In drivers/iommu/tegra-gart.c (c09c7670)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
  - drivers/iommu/tegra-gart.c:tegra_gart_resume
  - drivers/iommu/tegra-gart.c:tegra_gart_suspend
  - drivers/iommu/tegra-gart.c:tegra_gart_suspend
  - drivers/iommu/tegra-gart.c:gart_iommu_sync
  - drivers/iommu/tegra-gart.c:gart_iommu_iova_to_phys
  - drivers/iommu/tegra-gart.c:gart_iommu_unmap
  - drivers/iommu/tegra-gart.c:gart_iommu_map
```
```
In drivers/iommu/tegra-smmu.c (c09c8c68)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_clients_show
  - drivers/iommu/tegra-smmu.c:tegra_smmu_swgroups_show
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09ca430)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/iommu/qcom_iommu.c (c09cc478)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/base/regmap/regmap-mmio.c (c0a01c8c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a470)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/mfd/sm501.c (c0a0d444)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_plat_resume
  - drivers/mfd/sm501.c:sm501_plat_suspend
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/sm501.c:sm501_init_regs
  - drivers/mfd/sm501.c:sm501_init_regs
  - drivers/mfd/sm501.c:sm501_init_regs
  - drivers/mfd/sm501.c:sm501_dbg_regs
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_input
  - drivers/mfd/sm501.c:sm501_gpio_input
  - drivers/mfd/sm501.c:sm501_gpio_input
  - drivers/mfd/sm501.c:sm501_gpio_set
  - drivers/mfd/sm501.c:sm501_gpio_set
  - drivers/mfd/sm501.c:sm501_gpio_set
  - drivers/mfd/sm501.c:sm501_gpio_get
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_unit_power
  - drivers/mfd/sm501.c:sm501_unit_power
  - drivers/mfd/sm501.c:sm501_unit_power
  - drivers/mfd/sm501.c:sm501_unit_power
  - drivers/mfd/sm501.c:sm501_modify_reg
  - drivers/mfd/sm501.c:sm501_modify_reg
  - drivers/mfd/sm501.c:sm501_misc_control
  - drivers/mfd/sm501.c:sm501_misc_control
```
```
In drivers/mfd/omap-usb-host.c (c0a34cc0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a358e8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/mfd/vexpress-sysreg.c (c0a38c68)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
```
In drivers/ata/libata-core.c (c0a68088)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
```
```
In drivers/ata/libahci.c (c0a83f38)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_set_em_messages
  - drivers/ata/libahci.c:ahci_set_em_messages
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_handle_port_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_bad_pmp_check_ready
  - drivers/ata/libahci.c:ahci_bad_pmp_check_ready
  - drivers/ata/libahci.c:ahci_check_ready
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_dev_classify
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_reset_em
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_stop_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_save_initial_config
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
```
In drivers/ata/libahci_platform.c (c0a87e98)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_suspend_host
  - drivers/ata/libahci_platform.c:ahci_platform_suspend_host
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
```
```
In drivers/ata/sata_highbank.c (c0a88b7c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_suspend
  - drivers/ata/sata_highbank.c:ahci_highbank_suspend
  - drivers/ata/sata_highbank.c:__combo_phy_reg_read
```
```
In drivers/ata/ahci_imx.c (c0a8ab54)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
```
```
In drivers/mtd/maps/map_funcs.c (c0a995d0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_read
```
```
In drivers/mtd/nand/raw/omap2.c (c0aab7b8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc_bch_multi
  - drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc
  - drivers/mtd/nand/raw/omap2.c:omap_calculate_ecc
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_nand_irq
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_pref
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_reset
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_enable
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aacec0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_isr
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
```
```
In drivers/spi/spi-fsl-spi.c (c0ab5544)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7ed4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accb30)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_ethtool_stats
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0ace5fc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf438)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_done
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_done
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_free
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_free
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfabc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0754)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4198)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit
  - drivers/net/ethernet/ti/cpsw.c:_cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fifo_shp_on
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad8a28)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_control_get
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_process
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_process
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctrl_txchs_state
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctrl_rxchs_state
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_set_chan_shaper
  - drivers/net/ethernet/ti/davinci_cpdma.c:_cpdma_control_set
```
```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad9c4c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_control_get
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_control_set
```
```
In drivers/net/ethernet/ti/cpsw_priv.c (c0ad9df0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_priv.c:cpsw_init_common
```
```
In drivers/net/ethernet/ti/cpsw_sl.c (c0ada128)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adac54)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_get_ethtool_stats
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce
```
```
In drivers/auxdisplay/arm-charlcd.c (c0ae85ec)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c960)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/phy/phy-ulpi-viewport.c (c0b0d29c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
```
```
In drivers/usb/dwc2/core.c (c0b0efa0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c0b10334)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (c0b10f0c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/params.c (c0b12454)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (c0b1a8e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1d418)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1ec6c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b2019c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (c0b2238c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (c0b29e30)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_port_handed_over
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_disable_PSE
  - drivers/usb/host/ehci-hcd.c:ehci_disable_ASE
  - drivers/usb/host/ehci-hcd.c:ehci_set_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (c0b2fbe4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-orion.c (c0b3013c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/usb/host/ohci-hcd.c (c0b36aec)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (c0b3b2b4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/usb/host/xhci.c (c0b45c4c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_quiesce
  - drivers/usb/host/xhci.c:xhci_quiesce
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/host/xhci-mem.c (c0b4e600)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (c0b4ef70)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-ring.c (c0b538a0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (c0b59d0c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_link_state
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5eb84)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/usb/host/xhci-debugfs.c (c0b62504)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/host/xhci-pci.c (c0b62930)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/usb/musb/musb_core.c (c0b63ed4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_readl
```
```
In drivers/rtc/rtc-mv.c (c15a04f4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_interrupt
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
  - drivers/rtc/rtc-mv.c:mv_rtc_read_time
```
```
In drivers/rtc/rtc-omap.c (c0b8b7ac)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_scratch_read
  - drivers/rtc/rtc-omap.c:rtc_pinconf_set
  - drivers/rtc/rtc-omap.c:rtc_pinconf_get
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
```
```
In drivers/rtc/rtc-pl031.c (c0b8db54)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_read_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_read_alarm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_read_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_read_time
  - drivers/rtc/rtc-pl031.c:pl031_alarm_irq_enable
```
```
In drivers/rtc/rtc-s3c.c (c0b8de08)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_save_tick_cnt
```
```
In drivers/i2c/busses/i2c-designware-common.c (c0b980e8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9dfd4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:i2c_s3c_irq_nextbyte
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
```
```
In drivers/power/avs/smartreflex.c (c0ba9b5c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/power/avs/smartreflex.c:sr_enable
  - drivers/power/avs/smartreflex.c:sr_enable
  - drivers/power/avs/smartreflex.c:sr_configure_minmax
  - drivers/power/avs/smartreflex.c:sr_disable_errgen
  - drivers/power/avs/smartreflex.c:sr_disable_errgen
  - drivers/power/avs/smartreflex.c:sr_configure_errgen
  - drivers/power/avs/smartreflex.c:sr_configure_errgen
  - drivers/power/avs/smartreflex.c:sr_interrupt
  - drivers/power/avs/smartreflex.c:sr_interrupt
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe238)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_clear_irqs
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_initialize
```
```
In drivers/watchdog/npcm_wdt.c (c0bc2780)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_probe
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_ping
```
```
In drivers/watchdog/aspeed_wdt.c (c0bc2c2c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:access_cs0_show
```
```
In drivers/edac/armada_xp_edac.c (c0bf257c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/edac/armada_xp_edac.c:aurora_l2_probe
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
```
```
In drivers/opp/ti-opp-supply.c (c0bf7a34)
Location: arch/arm/include/asm/io.h:110
Inline: True
```
```
In drivers/mmc/host/mmci.c (c0c21070)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_get_rx_fifocnt
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
  - drivers/mmc/host/mmci.c:mmci_set_mask1
  - drivers/mmc/host/mmci.c:mmci_dma_start
  - drivers/mmc/host/mmci.c:mmci_card_busy
```
```
In drivers/mmc/host/mmci_qcom_dml.c (c0c21224)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
```
```
In drivers/mmc/host/sdhci.c (c0c24e44)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:__sdhci_read_caps
  - drivers/mmc/host/sdhci.c:__sdhci_read_caps
  - drivers/mmc/host/sdhci.c:sdhci_cqe_disable
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_card_busy
  - drivers/mmc/host/sdhci.c:sdhci_check_ro
  - drivers/mmc/host/sdhci.c:sdhci_get_cd
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
  - drivers/mmc/host/sdhci.c:sdhci_dumpregs
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a558)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_conf_bus_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_conf_bus_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_enable_sdio_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_enable_sdio_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_enable_sdio_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:set_data_timeout
  - drivers/mmc/host/omap_hsmmc.c:set_sd_bus_power
  - drivers/mmc/host/omap_hsmmc.c:set_sd_bus_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2cfe8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_unregister
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f2f8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_timeout
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_hs400_enhanced_strobe
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_executing_tuning
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_prepare_tuning
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_prepare_tuning
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_pltfm_set_bus_width
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
```
```
In drivers/mmc/host/cqhci.c (c0c2f968)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_off
  - drivers/mmc/host/cqhci.c:cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_disable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
  - drivers/mmc/host/cqhci.c:cqhci_dumpregs
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37524)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
```
```
In drivers/firmware/arm_scmi/perf.c (c0c393d0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c440b8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read32
```
```
In drivers/clocksource/renesas-ostm.c (c0c45b74)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_read_sched_clock
```
```
In drivers/clocksource/sh_tmu.c (c0c45dbc)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/clocksource/em_sti.c (c0c46a9c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_count
  - drivers/clocksource/em_sti.c:em_sti_count
```
```
In drivers/clocksource/mmio.c (c0c47134)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/mmio.c:clocksource_mmio_readl_down
  - drivers/clocksource/mmio.c:clocksource_mmio_readl_up
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47668)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timers_active
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timers_active
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_start
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_start
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_write_reg
```
```
In drivers/clocksource/dw_apb_timer.c (c0c48944)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer.c:__apbt_read_clocksource
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start
  - drivers/clocksource/dw_apb_timer.c:apbt_next_event
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_shutdown
  - drivers/clocksource/dw_apb_timer.c:apbt_enable_int
  - drivers/clocksource/dw_apb_timer.c:apbt_enable_int
  - drivers/clocksource/dw_apb_timer.c:apbt_eoi
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_pause
```
```
In drivers/clocksource/dw_apb_timer_of.c (c0c490c0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_delay_timer_read
  - drivers/clocksource/dw_apb_timer_of.c:read_sched_clock
```
```
In drivers/clocksource/timer-rockchip.c (c0c49220)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_sched_read
```
```
In drivers/clocksource/timer-armada-370-xp.c (c15ab410)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_delay_timer_read
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_suspend
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_suspend
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_starting_cpu
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_set_periodic
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_shutdown
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_next_event
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_read_sched_clock
```
```
In drivers/clocksource/timer-orion.c (c0c496e4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-orion.c:orion_read_sched_clock
  - drivers/clocksource/timer-orion.c:orion_read_timer
```
```
In drivers/clocksource/timer-meson6.c (c15ab9e0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event
  - drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event
  - drivers/clocksource/timer-meson6.c:meson6_set_periodic
  - drivers/clocksource/timer-meson6.c:meson6_set_periodic
  - drivers/clocksource/timer-meson6.c:meson6_set_oneshot
  - drivers/clocksource/timer-meson6.c:meson6_set_oneshot
  - drivers/clocksource/timer-meson6.c:meson6_shutdown
  - drivers/clocksource/timer-meson6.c:meson6_timer_sched_read
  - drivers/clocksource/timer-meson6.c:meson6_read_current_timer
```
```
In drivers/clocksource/timer-tegra.c (c0c49b70)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_rtc_read_ms
  - drivers/clocksource/timer-tegra.c:tegra_rtc_read_ms
  - drivers/clocksource/timer-tegra.c:tegra_delay_timer_read_counter_long
  - drivers/clocksource/timer-tegra.c:tegra_read_sched_clock
```
```
In drivers/clocksource/exynos_mct.c (c15ac264)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/exynos_mct.c:exynos4_mct_tick_clear
  - drivers/clocksource/exynos_mct.c:exynos4_mct_tick_start
  - drivers/clocksource/exynos_mct.c:exynos4_mct_tick_stop
  - drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start
  - drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start
  - drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start
  - drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_start
  - drivers/clocksource/exynos_mct.c:exynos4_mct_comp0_stop
  - drivers/clocksource/exynos_mct.c:exynos4_read_current_timer
  - drivers/clocksource/exynos_mct.c:exynos4_read_sched_clock
  - drivers/clocksource/exynos_mct.c:exynos4_frc_resume
  - drivers/clocksource/exynos_mct.c:exynos4_frc_read
  - drivers/clocksource/exynos_mct.c:exynos4_mct_write
```
```
In drivers/clocksource/timer-qcom.c (c0c4a4d8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_read_timer_count
  - drivers/clocksource/timer-qcom.c:msm_timer_shutdown
  - drivers/clocksource/timer-qcom.c:msm_timer_set_next_event
  - drivers/clocksource/timer-qcom.c:msm_timer_set_next_event
  - drivers/clocksource/timer-qcom.c:msm_timer_interrupt
```
```
In drivers/clocksource/timer-mediatek.c (c15ac89c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_read_sched_clock
```
```
In drivers/clocksource/timer-ti-32k.c (c15ac92c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init
  - drivers/clocksource/timer-ti-32k.c:omap_32k_read_sched_clock
```
```
In drivers/clocksource/timer-owl.c (c15aca54)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_shutdown
  - drivers/clocksource/timer-owl.c:owl_timer_sched_read
```
```
In drivers/clocksource/timer-milbeaut.c (c0c4ac84)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_sched_read
  - drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_shutdown
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_oneshot
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_interrupt
```
```
In drivers/clocksource/timer-npcm7xx.c (c15acc50)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_oneshot
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_shutdown
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_resume
```
```
In drivers/clocksource/timer-rda.c (c0c4afa4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-rda.c:rda_hwtimer_read
  - drivers/clocksource/timer-rda.c:rda_hwtimer_read
  - drivers/clocksource/timer-rda.c:rda_hwtimer_read
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad520)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_phys_mem
```
```
In drivers/clocksource/arm_global_timer.c (c0c4b960)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:gt_read_long
  - drivers/clocksource/arm_global_timer.c:gt_sched_clock_read
  - drivers/clocksource/arm_global_timer.c:gt_sched_clock_read
  - drivers/clocksource/arm_global_timer.c:gt_sched_clock_read
  - drivers/clocksource/arm_global_timer.c:gt_clocksource_read
  - drivers/clocksource/arm_global_timer.c:gt_clocksource_read
  - drivers/clocksource/arm_global_timer.c:gt_clocksource_read
  - drivers/clocksource/arm_global_timer.c:gt_clockevent_shutdown
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
```
```
In drivers/clocksource/timer-sp804.c (c0c4bb70)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-sp804.c:sp804_read
```
```
In drivers/clocksource/timer-versatile.c (c0c4bd34)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-versatile.c:versatile_sys_24mhz_read
```
```
In drivers/clocksource/timer-imx-gpt.c (c0c4c030)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-gpt.c:mxc_timer_interrupt
  - drivers/clocksource/timer-imx-gpt.c:mxc_set_oneshot
  - drivers/clocksource/timer-imx-gpt.c:mxc_shutdown
  - drivers/clocksource/timer-imx-gpt.c:v2_set_next_event
  - drivers/clocksource/timer-imx-gpt.c:v2_set_next_event
  - drivers/clocksource/timer-imx-gpt.c:mx1_2_set_next_event
  - drivers/clocksource/timer-imx-gpt.c:mx1_2_set_next_event
  - drivers/clocksource/timer-imx-gpt.c:imx_read_current_timer
  - drivers/clocksource/timer-imx-gpt.c:mxc_read_sched_clock
  - drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_enable
  - drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_disable
```
```
In drivers/clocksource/timer-imx-tpm.c (c15ae678)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_state_shutdown
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_state_oneshot
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_next_event
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_next_event
  - drivers/clocksource/timer-imx-tpm.c:tpm_read_sched_clock
  - drivers/clocksource/timer-imx-tpm.c:tpm_read_current_timer
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5cd84)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_suspend
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_suspend
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_enable
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_fifo_flush
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_fifo_flush
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_set_stall
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_restert_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_dma_abort
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_dma_abort
```
```
In drivers/mailbox/pl320-ipc.c (c0c602d4)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c60594)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_irq
```
```
In drivers/mailbox/tegra-hsp.c (c0c61488)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_flush
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_shutdown
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_startup
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_startup
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_irq
```
```
In drivers/memory/omap-gpmc.c (c0c71738)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_save_context
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_gpio_get
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_mem_exit
  - drivers/memory/omap-gpmc.c:gpmc_handle_irq
  - drivers/memory/omap-gpmc.c:gpmc_irq_set_type
  - drivers/memory/omap-gpmc.c:gpmc_irq_set_type
  - drivers/memory/omap-gpmc.c:gpmc_irq_enable
  - drivers/memory/omap-gpmc.c:gpmc_irq_disable
  - drivers/memory/omap-gpmc.c:gpmc_nand_writebuffer_empty
  - drivers/memory/omap-gpmc.c:gpmc_cs_free
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_memconf
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:set_gpmc_timing_reg
  - drivers/memory/omap-gpmc.c:set_gpmc_timing_reg
```
```
In drivers/memory/mtk-smi.c (c0c72b7c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen1
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
```
```
In drivers/memory/samsung/exynos-srom.c (c0c732a0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_suspend
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
```
In drivers/memory/tegra/mc.c (c0c7401c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_get_emem_device_count
  - drivers/memory/tegra/mc.c:tegra_mc_reset_status_common
  - drivers/memory/tegra/mc.c:tegra_mc_unblock_dma_common
  - drivers/memory/tegra/mc.c:tegra_mc_dma_idling_common
  - drivers/memory/tegra/mc.c:tegra_mc_block_dma_common
```
```
In drivers/memory/tegra/tegra20.c (c0c747ec)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20.c:tegra20_mc_unblock_dma
  - drivers/memory/tegra/tegra20.c:tegra20_mc_reset_status
  - drivers/memory/tegra/tegra20.c:tegra20_mc_dma_idling
  - drivers/memory/tegra/tegra20.c:tegra20_mc_block_dma
  - drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_deassert
  - drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_assert
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74d1c)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:emc_prepare_timing_change
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_isr
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c75b14)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
```
```
In drivers/perf/arm-cci.c (c0c7ae18)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_event_update
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In drivers/perf/arm-ccn.c (c0c7c8f8)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region
  - drivers/perf/arm-ccn.c:arm_ccn_for_each_valid_region
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_overflow_handler
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_disable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_enable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In sound/soc/fsl/imx-audmux.c (c0cc1ae0)
Location: arch/arm/include/asm/io.h:110
Inline: True
Inline callers:
  - sound/soc/fsl/imx-audmux.c:imx_audmux_suspend
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap_copy.c (c0000000007e7478)
Location: arch/powerpc/include/asm/io.h:310
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/gpio/gpio-xilinx.c (c00000000084dc9c)
Location: arch/powerpc/include/asm/io.h:310
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_get
```
```
In drivers/video/fbdev/core/cfbimgblt.c (c0000000008be740)
Location: arch/powerpc/include/asm/io.h:310
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092c60c)
Location: arch/powerpc/include/asm/io.h:310
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/sifive_l2_cache.c (ffffffe000003f34)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
  - arch/riscv/mm/sifive_l2_cache.c:l2_int_handler
```
```
In kernel/irq/generic-chip.c (ffffffe000118b6a)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_init_mask_cache
  - kernel/irq/generic-chip.c:irq_readl_be
```
```
In fs/debugfs/file.c (ffffffe000381924)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_print_regs32
```
```
In lib/iomap_copy.c (ffffffe00046b384)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/irqchip/irq-al-fic.c (ffffffe00049546a)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe000495696)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_handle_irq
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_mask
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e9ac)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fd24)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readl
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad3e0)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/gpio/gpio-mmio.c:bgpio_read32
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae826)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b2b66)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_get_state
  - drivers/pwm/pwm-sifive.c:pwm_sifive_get_state
```
```
In drivers/pci/access.c (ffffffe0004b3d5c)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_read32
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffe0004c36c8)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffe0004cc7b0)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dce82)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_query_power_fault
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_status
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_latch_status
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_power_status
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_attention_status
```
```
In drivers/pci/msi.c (ffffffe0004ded84)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:__pci_read_msi_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e4472)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e5880)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e649c)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6e26)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_map_bus
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e760e)
Location: arch/riscv/include/asm/io.h:77
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e9fb4)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/video/fbdev/imsttfb.c (ffffffe000506726)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
```
```
In drivers/clk/clk-divider.c (ffffffe0005117d2)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffe000512c36)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffe000512e20)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffe000513250)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe000513f46)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/clk/clk-fixed-mmio.c (ffffffe000514b6a)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
```
```
In drivers/clk/clk-hsdk-pll.c (ffffffe0005151f0)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate
```
```
In drivers/clk/sifive/fu540-prci.c (ffffffe00051573e)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_tlclksel_recalc_rate
  - drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_corepll
  - drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_corepll
  - drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_hfclk
  - drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_hfclk
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d164)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_get_status
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d9a6)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f5b0)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000550fa4)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_in
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555b3e)
Location: arch/riscv/include/asm/io.h:77
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557174)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe0005597ae)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sifive.c (ffffffe00055e02a)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_console_write
  - drivers/tty/serial/sifive.c:sifive_serial_console_putchar
  - drivers/tty/serial/sifive.c:early_sifive_serial_putc
  - drivers/tty/serial/sifive.c:sifive_serial_set_termios
  - drivers/tty/serial/sifive.c:sifive_serial_set_termios
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/tty/serial/sifive.c:sifive_serial_irq
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/riscv/include/asm/io.h:77
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe000573990)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059bfa8)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le
```
```
In drivers/ata/libata-core.c (ffffffe0005f8e44)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
```
```
In drivers/ata/libata-sff.c (ffffffe00060ca9e)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061c008)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c392)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
```
```
In drivers/usb/dwc2/core.c (ffffffe000657840)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe000659384)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a564)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/params.c (ffffffe00065b50a)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000665028)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000667e4a)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe0006695a8)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066aaa6)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066cba2)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe0006773b2)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_get_frame
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_disable_PSE
  - drivers/usb/host/ehci-hcd.c:ehci_disable_ASE
  - drivers/usb/host/ehci-hcd.c:ehci_set_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
```
```
In drivers/usb/host/ehci-pci.c (ffffffe000679716)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067ff02)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_dump_status
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000683252)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci.c (ffffffe00068a62c)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_get_frame
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:compliance_mode_recovery
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_quiesce
  - drivers/usb/host/xhci.c:xhci_quiesce
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692318)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffe000692c30)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000696d8c)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069c5ee)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_link_state
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0a2e)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a34f2)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_portsc_show
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a38fc)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bda62)
Location: arch/riscv/include/asm/io.h:77
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
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
<b>Arch</b>
<ul>
</ul>
