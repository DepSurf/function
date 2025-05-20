# Function: <code>__raw_writel</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a96f4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100df2d8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_load
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_load
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_restore_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_restore_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_save_state
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_init_lrs
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (ffff800010dad100)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c:__vgic_v2_perform_cpuif_access
```
```
In kernel/irq/generic-chip.c (ffff800010180c1c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In lib/iomap_copy.c (ffff80001063d7c0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In lib/logic_pio.c (ffff80001063e788)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In lib/stmp_device.c (ffff8000106679e8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_clear_poll_bit
```
```
In drivers/irqchip/irq-al-fic.c (ffff800011470674)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_retrigger
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-bcm2835.c (ffff80001066aa1c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2835.c:armctrl_unmask_irq
  - drivers/irqchip/irq-bcm2835.c:armctrl_mask_irq
```
```
In drivers/irqchip/irq-bcm2836.c (ffff800011470a9c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_send_ipi
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_pmu_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_pmu_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_per_cpu_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_per_cpu_irq
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470d00)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
```
```
In drivers/irqchip/irq-sun4i.c (ffff80001066b368)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_unmask
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_mask
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001147132c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c494)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_if_down
  - drivers/irqchip/irq-gic.c:gic_cpu_init
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic.c:gic_eoi_irq
  - drivers/irqchip/irq-gic.c:gic_unmask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-common.c (ffff80001066d144)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472eec)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_poke_irq
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674ba4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
```
```
In drivers/irqchip/irq-mbigen.c (ffff800010676384)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_write_msg
  - drivers/irqchip/irq-mbigen.c:mbigen_set_type
  - drivers/irqchip/irq-mbigen.c:mbigen_eoi_irq
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676adc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000114753bc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_mask
  - drivers/irqchip/irq-bcm7038-l1.c:__bcm7038_l1_unmask
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff80001067760c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677d90)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff80001067844c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_unmask
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_mask
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800011475df4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
  - drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_restore
  - drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_save
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff80001067970c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff800010679ee4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_enable_percpu_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_enable_percpu_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_unmask_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_mask_irq
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_eoi_irq
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a808)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_set_irqchip_state
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c1a0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_set_type
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_enable
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_enable
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_unmask
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_mask
  - drivers/irqchip/irq-sni-exiu.c:exiu_irq_eoi
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067c9ac)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067cf84)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d998)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f8b4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
```
```
In drivers/bus/brcmstb_gisb.c (ffff8000106801bc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/bus/imx-weim.c (ffff800010685034)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/imx-weim.c:weim_parse_dt
```
```
In drivers/bus/qcom-ebi2.c (ffff8000106857ac)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/phy/phy-xgene.c (ffff8000106881e4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/phy/broadcom/phy-brcm-sata.c (ffff80001068a9c0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_wr
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_wr
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692934)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694ad8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_set
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinmux_set_mux
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699b98)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b6f0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writel
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a0b14)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3a28)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2711_pinconf_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2711_pull_config_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinconf_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pull_config_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pull_config_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pull_config_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_set_direction
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_set_direction
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_disable_free
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_free
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_ack
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_set
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a6178)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_ack
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a6a18)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a8dc0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aaa28)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_set
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106abffc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106acf80)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_ps_hold_poweroff
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106b013c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b31d4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pmx_set_mux
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b69e0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_ack
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7e7c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_resume
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_resume
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_suspend
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_suspend
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_type
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_type
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_ack
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_unmask
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_mask
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_flip_edge
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bad6c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_rmw
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106ccdb4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/gpio/gpio-mmio.c:bgpio_write32
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cddfc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:gpio_irq_type_unbanked
  - drivers/gpio/gpio-davinci.c:gpio_irq_type_unbanked
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
  - drivers/gpio/gpio-davinci.c:gpio_irq_enable
  - drivers/gpio/gpio-davinci.c:gpio_irq_enable
  - drivers/gpio/gpio-davinci.c:gpio_irq_disable
  - drivers/gpio/gpio-davinci.c:gpio_irq_disable
  - drivers/gpio/gpio-davinci.c:davinci_gpio_set
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce890)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106cfd88)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2354)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d64e4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_resume
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:__xgene_gpio_set
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d6da4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
```
```
In drivers/pci/access.c (ffff8000106da564)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffff8000106ff118)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010711060)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
```
In drivers/pci/msi.c (ffff800010715724)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
```
```
In drivers/pci/controller/pcie-cadence.c (ffff80001071d230)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071da6c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e30c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f6c0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_parse_map_dma_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pci-aardvark.c (ffff800010720594)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_unmask
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_mask
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_wr_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_rd_conf
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write
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
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722744)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_rmw32
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723740)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff8000107250d8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
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
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
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
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_misc_handler
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107266fc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727540)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:s10_rp_write_cfg
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727c8c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
```
```
In drivers/pci/controller/pcie-rockchip.c (ffff8000107282f8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff80001072967c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_start
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b928)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_map_bus
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_msi_ack_irq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c514)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072ce88)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff800010730044)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731f40)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800011479fb4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_err_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_start_link
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_stop_link
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_clear_dbi_mode
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_set_dbi_mode
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_unmask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_mask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_ack
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_ack
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff800010733524)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff80001073526c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_3_2_ltssm_enable
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_1_0_ltssm_enable
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff800010736684)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_host_init
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_sideband_dbi_r_mode
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736fa4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_r_mode
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_w_mode
```
```
In drivers/pci/controller/dwc/pcie-al.c (ffff800010737a04)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_host_init
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_host_init
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_conf_addr_map
```
```
In drivers/pci/controller/pci-thunder-ecam.c (ffff800010738588)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
```
```
In drivers/pci/controller/pci-xgene.c (ffff800010739a0c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_map_bus
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffff800010759054)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075ab28)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_pan_display
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c9c4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/amba-clcd.c:clcdfb_setcolreg
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107609ac)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:sdc_set_brightness
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/acpi/osl.c (ffff800010763d78)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107aaa60)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/clk/clk-divider.c (ffff8000107c4774)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffff8000107c5780)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffff8000107c5b6c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffff8000107c6334)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c7198)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
```
```
In drivers/clk/clk-hsdk-pll.c (ffff8000107c84b4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/clk/clk-qoriq.c (ffff8000107c8718)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:mux_set_parent
  - drivers/clk/clk-qoriq.c:mux_set_parent
```
```
In drivers/clk/clk-xgene.c (ffff8000107c9550)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/clk-xgene.c:xgene_clk_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate
```
```
In drivers/clk/bcm/clk-iproc-pll.c (ffff8000107cb96c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_write
```
```
In drivers/clk/bcm/clk-iproc-asiu.c (ffff8000107ccc30)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_set_rate
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_set_rate
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_disable
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_clk_enable
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cd028)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_parent
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off
```
```
In drivers/clk/berlin/berlin2-avpll.c (ffff8000107cf0ac)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_enable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_enable
```
```
In drivers/clk/berlin/berlin2-div.c (ffff8000107cf81c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
```
```
In drivers/clk/hisilicon/clkgate-separated.c (ffff8000107d0234)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d0648)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (ffff8000107d0aa0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
```
```
In drivers/clk/hisilicon/reset.c (ffff8000107d1440)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/imx/clk.c (ffff800011485958)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_mmdc_mask_handshake
```
```
In drivers/clk/imx/clk-composite-8m.c (ffff8000107d24f0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (ffff8000107d2e80)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
```
```
In drivers/clk/imx/clk-fixup-div.c (ffff8000107d3430)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (ffff8000107d36d0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-frac-pll.c (ffff8000107d3aac)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_unprepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-gate2.c (ffff8000107d3fe0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfd.c (ffff8000107d43fc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfd.c:clk_pfd_set_rate
  - drivers/clk/imx/clk-pfd.c:clk_pfd_set_rate
  - drivers/clk/imx/clk-pfd.c:clk_pfd_disable
  - drivers/clk/imx/clk-pfd.c:clk_pfd_enable
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d4998)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv2.c (ffff8000107d4f68)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_unprepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
```
```
In drivers/clk/imx/clk-pllv3.c (ffff8000107d58a0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_unprepare
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare
```
```
In drivers/clk/imx/clk-pllv4.c (ffff8000107d5d30)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_disable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
```
```
In drivers/clk/imx/clk-sccg-pll.c (ffff8000107d66b0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_unprepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare
```
```
In drivers/clk/imx/clk-pll14xx.c (ffff8000107d6f48)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_unprepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
```
```
In drivers/clk/imx/clk-lpcg-scu.c (ffff8000107d7714)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable
```
```
In drivers/clk/mediatek/clk-pll.c (ffff8000107e2610)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
```
```
In drivers/clk/mediatek/clk-apmixed.c (ffff8000107e2e14)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_unprepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e8be8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_resume
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_resume
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_resume
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_resume
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_resume
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_resume
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107ea520)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_div_set_rate
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff800011487fd0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec008)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_deassert
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_assert
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_reset
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_reset
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-div6.c (ffff8000107ec800)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_parent
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_rate
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_disable
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_enable
```
```
In drivers/clk/rockchip/clk.c (ffff8000107ec950)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_restart_notify
```
```
In drivers/clk/rockchip/clk-pll.c (ffff8000107eccd4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_disable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_disable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_disable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee734)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
```
In drivers/clk/rockchip/clk-half-divider.c (ffff8000107eef70)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (ffff8000107ef3a8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (ffff8000107ef780)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_mmc_set_phase
```
```
In drivers/clk/rockchip/softrst.c (ffff8000107f00c4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/rockchip/clk-rk3036.c (ffff80001148a298)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init
```
```
In drivers/clk/rockchip/clk-rk3288.c (ffff8000107f0380)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_shutdown
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_resume
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend
```
```
In drivers/clk/socfpga/clk-pll-s10.c (ffff8000107f0824)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/socfpga/clk-pll-s10.c:clk_pll_prepare
```
```
In drivers/clk/sunxi/clk-factors.c (ffff8000107f1540)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
```
```
In drivers/clk/sunxi/clk-a10-pll2.c (ffff80001148c3b4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
```
```
In drivers/clk/sunxi/clk-a10-ve.c (ffff8000107f2370)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff8000107f2700)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (ffff8000107f29a4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (ffff8000107f2cb0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3790)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3b50)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (ffff8000107f427c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (ffff8000107f4c14)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
```
```
In drivers/clk/sunxi-ng/ccu_reset.c (ffff8000107f4ee4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu_div.c (ffff8000107f5298)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_frac.c (ffff8000107f5868)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f5b18)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f64d4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (ffff8000107f69a4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (ffff8000107f6c50)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
```
```
In drivers/clk/sunxi-ng/ccu_sdm.c (ffff8000107f70dc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (ffff8000107f7890)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (ffff8000107f7fa4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (ffff8000107f8758)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (ffff8000107f8ec4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f96e8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
```
```
In drivers/clk/sunxi-ng/ccu-sun50i-a64.c (ffff8000107f9a2c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu-sun50i-h6.c (ffff8000107f9b28)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-a83t.c (ffff8000107f9ce8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_cpu_pll_fixup
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-h3.c (ffff80001148e79c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-h3.c:sunxi_h3_h5_ccu_init
```
```
In drivers/clk/versatile/clk-sp810.c (ffff8000107fa094)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
```
```
In drivers/dma/amba-pl08x.c (ffff800010802834)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
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
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
```
```
In drivers/dma/bcm2835-dma.c (ffff800010805018)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_start_desc
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_start_desc
```
```
In drivers/dma/mv_xor.c (ffff800010805e6c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_resume
  - drivers/dma/mv_xor.c:mv_xor_resume
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_chan_start_new_chain
  - drivers/dma/mv_xor.c:mv_chan_activate
```
```
In drivers/dma/mv_xor_v2.c (ffff800010809138)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_resume
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_resume
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_resume
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_suspend
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_descq_init
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_set_msi_msg
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_set_msi_msg
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_set_msi_msg
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
```
```
In drivers/dma/mxs-dma.c (ffff80001148f040)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_resume_chan
  - drivers/dma/mxs-dma.c:mxs_dma_resume_chan
  - drivers/dma/mxs-dma.c:mxs_dma_pause_chan
  - drivers/dma/mxs-dma.c:mxs_dma_pause_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080a528)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_ack
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f4c0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_ic_disable_task
```
```
In drivers/soc/actions/owl-sps-helper.c (ffff80001080d97c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e8b4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
```
```
In drivers/soc/bcm/brcmstb/biuctrl.c (ffff80001148fb8c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
  - drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f96c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
  - drivers/soc/fsl/qbman/bman_ccsr.c:bman_isr
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff8000108103d4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
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
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010812488)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_p_irqsource_add
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/bman.c:portal_isr
  - drivers/soc/fsl/qbman/bman.c:portal_isr
  - drivers/soc/fsl/qbman/bman.c:portal_isr
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010817564)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:_qm_dqrr_consume_and_match
  - drivers/soc/fsl/qbman/qman.c:_qm_mr_consume_and_match_verb
  - drivers/soc/fsl/qbman/qman.c:set_vdqcr
  - drivers/soc/fsl/qbman/qman.c:qman_p_static_dequeue_add
  - drivers/soc/fsl/qbman/qman.c:qman_p_poll_dqrr
  - drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_remove
  - drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_remove
  - drivers/soc/fsl/qbman/qman.c:qman_p_irqsource_add
  - drivers/soc/fsl/qbman/qman.c:qm_mr_process_task
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
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/soc/fsl/qbman/qman.c:drain_mr_fqrni
  - drivers/soc/fsl/qbman/qman.c:portal_isr
  - drivers/soc/fsl/qbman/qman.c:portal_isr
  - drivers/soc/fsl/qbman/qman.c:portal_isr
  - drivers/soc/fsl/qbman/qman.c:qman_enable_irqs
  - drivers/soc/fsl/qbman/qman.c:qman_enable_irqs
  - drivers/soc/fsl/qbman/qman.c:qman_portal_set_iperiod
  - drivers/soc/fsl/qbman/qman.c:qman_dqrr_set_ithresh
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff800010819470)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b518)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
```
```
In drivers/soc/renesas/rcar-rst.c (ffff80001081e19c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_enable_wdt_reset
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff80001081e274)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/soc/sunxi/sunxi_sram.c (ffff80001081f9d0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_claim
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826a64)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_notify
  - drivers/virtio/virtio_mmio.c:vm_reset
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffff800010827778)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829050)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/reset/reset-meson.c (ffff80001084da28)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_level
  - drivers/reset/reset-meson.c:meson_reset_level
  - drivers/reset/reset-meson.c:meson_reset_reset
```
```
In drivers/reset/reset-qcom-aoss.c (ffff80001084dc14)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_reset
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_assert
```
```
In drivers/reset/reset-simple.c (ffff80001084de9c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886408)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_out
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffff80001088c380)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088ff80)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffff8000108905d8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890ecc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_out32be
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_out32
  - drivers/tty/serial/8250/8250_dw.c:dw8250_check_lcr
  - drivers/tty/serial/8250/8250_dw.c:dw8250_check_lcr
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892be4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894508)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_putc
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown_channel
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (ffff80001089a0a4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_early_putchar
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_putchar
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e740)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/meson_uart.c:meson_uart_stop_rx
  - drivers/tty/serial/meson_uart.c:meson_uart_stop_tx
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3284)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
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
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_shutdown
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_break_ctl
  - drivers/tty/serial/msm_serial.c:msm_break_ctl
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
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
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_enable_ms
  - drivers/tty/serial/msm_serial.c:msm_stop_rx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a4cbc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6f28)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2840)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c2e84)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/iommu/arm-smmu.c (ffff8000108cfee0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_write_sme
  - drivers/iommu/arm-smmu.c:arm_smmu_write_s2cr
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_global_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_vmid_nosync
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_range_s2
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_range_s1
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_context_s2
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_context_s1
  - drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync
```
```
In drivers/iommu/arm-smmu-impl.c (ffff8000108d31b0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_mmu500_reset
  - drivers/iommu/arm-smmu-impl.c:arm_smmu_write_ns
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6c5c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_write_msi_msg
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_write_msi_msg
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_gerror_handler
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_priq_thread
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:queue_remove_raw
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d8b80)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108daa20)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_inv_range_nosync
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_inv_context
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c5f8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092be34)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/mfd/vexpress-sysreg.c (ffff80001094ef78)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_flags_set
  - drivers/mfd/vexpress-sysreg.c:vexpress_flags_set
```
```
In drivers/ata/libata-sff.c (ffff8000109b12e4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
```
```
In drivers/ata/ahci_imx.c (ffff8000109b82e8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
```
```
In drivers/ata/libahci.c (ffff8000109b9d10)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_stop
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_freeze
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_handle_port_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_reset_em
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_stop_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_store_em_buffer
```
```
In drivers/ata/libahci_platform.c (ffff8000109bdb20)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_suspend_host
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbcd0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd9a8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_prepare_message
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
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_fifo
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d8ae4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_switch_fn
  - drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops
  - drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops
  - drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops
  - drivers/net/phy/mdio-mux-bcm-iproc.c:start_miim_ops
```
```
In drivers/net/ethernet/broadcom/bgmac-platform.c (ffff8000109e4f08)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_nicpm_speed_set
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_nicpm_speed_set
  - drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_idm_write
  - drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_write
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea6c8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ec704)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109eda8c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109f0478)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
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
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:dma_init
  - drivers/net/ethernet/freescale/fman/fman.c:disable_rams_ecc
  - drivers/net/ethernet/freescale/fman/fman.c:disable_rams_ecc
  - drivers/net/ethernet/freescale/fman/fman.c:enable_rams_ecc
  - drivers/net/ethernet/freescale/fman/fman.c:enable_rams_ecc
```
```
In drivers/net/ethernet/freescale/fman/fman_keygen.c (ffff8000109f1254)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_init
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_write_sp
  - drivers/net/ethernet/freescale/fman/fman_keygen.c:keygen_write_ar_wait
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (ffff8000109f228c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_config
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:set_ext_buffer_pools
  - drivers/net/ethernet/freescale/fman/fman_port.c:set_ext_buffer_pools
  - drivers/net/ethernet/freescale/fman/fman_port.c:set_ext_buffer_pools
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (ffff8000109f5d30)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_adjust_link
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_modify_mac_address
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_disable
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_enable
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_1588_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:set_bucket
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:set_bucket
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:init
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (ffff8000109f7404)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_add_hash_mac_address
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
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_err_exception
  - drivers/net/ethernet/freescale/fman/fman_memac.c:set_exception
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (ffff8000109f88f8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_del_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tstamp
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_allmulti
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_add_hash_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_accept_rx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_tx_pause_frames
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_set_promiscuous
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_disable
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_enable
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_err_exception
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:set_mac_address
  - drivers/net/ethernet/freescale/fman/fman_tgec.c:set_mac_address
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb54c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a393d4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/phy/phy-ulpi-viewport.c (ffff800010a3a074)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
```
```
In drivers/usb/dwc2/core.c (ffff800010a3c120)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3d6e8)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
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
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a48194)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
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
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b2e0)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4cf64)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e0e0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50ee4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5d5ec)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
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
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_clear_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_set_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
```
In drivers/usb/host/ehci-pci.c (ffff800010a5e3e0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/usb/host/ehci-orion.c (ffff800010a5ed50)
Location: arch/arm64/include/asm/io.h:37
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
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_reset
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a65c34)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
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
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_usb_reset
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/xhci.c (ffff800010a73a98)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
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
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
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
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_quiesce
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7ae0c)
Location: arch/arm64/include/asm/io.h:37
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
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7db88)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a86d74)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
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
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b138)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8feec)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a911ec)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/rtc/rtc-mv.c (ffff80001149df6c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_interrupt
  - drivers/rtc/rtc-mv.c:mv_rtc_alarm_irq_enable
  - drivers/rtc/rtc-mv.c:mv_rtc_alarm_irq_enable
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aaccf8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad328)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_settime
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_settime
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aadf78)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_set_alarm
  - drivers/rtc/rtc-xgene.c:xgene_rtc_alarm_irq_enable
  - drivers/rtc/rtc-xgene.c:xgene_rtc_set_time
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab9378)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba36c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:mscc_twi_set_sda_hold_time
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abd240)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr_thread
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_enable
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_data_transfer
```
```
In drivers/power/reset/hisi-reboot.c (ffff800010ac9a80)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/power/reset/hisi-reboot.c:hisi_restart_handler
```
```
In drivers/power/reset/msm-poweroff.c (ffff800010ac9bf8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/power/reset/msm-poweroff.c:do_msm_poweroff
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1b30)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_set_timeout
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_ping
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_ping
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_stop
```
```
In drivers/edac/altera_edac.c (ffff800010b17ca4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:s10_edac_dberr_handler
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_check_ocram_deps_init
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_init_memory_port
  - drivers/edac/altera_edac.c:altr_init_memory_port
  - drivers/edac/altera_edac.c:altr_edac_a10_ecc_irq
  - drivers/edac/altera_edac.c:altr_edac_a10_ecc_irq
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/mmc/host/mmci.c (ffff800010b462a4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_stop_data
  - drivers/mmc/host/mmci.c:mmci_set_mask1
  - drivers/mmc/host/mmci.c:mmci_set_mask1
  - drivers/mmc/host/mmci.c:mmci_dma_start
  - drivers/mmc/host/mmci.c:mmci_dma_start
```
```
In drivers/mmc/host/mmci_qcom_dml.c (ffff800010b47c8c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b480a0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_finalize
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56aa8)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58308)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63d60)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_write32
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b66104)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/clocksource/timer-rockchip.c (ffff8000114a8620)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_interrupt
  - drivers/clocksource/timer-rockchip.c:rk_timer_interrupt
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_shutdown
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
```
```
In drivers/clocksource/timer-mediatek.c (ffff8000114a87ec)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_interrupt
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_handler
```
```
In drivers/clocksource/timer-owl.c (ffff8000114a89f0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer1_interrupt
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_oneshot
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_oneshot
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_oneshot
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_shutdown
```
```
In drivers/clocksource/timer-sprd.c (ffff800010b66a78)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_disable
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_enable
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_enable
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_enable
  - drivers/clocksource/timer-sprd.c:sprd_timer_init
  - drivers/clocksource/timer-sprd.c:sprd_timer_interrupt
  - drivers/clocksource/timer-sprd.c:sprd_timer_interrupt
  - drivers/clocksource/timer-sprd.c:sprd_timer_shutdown
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a91d4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_phys_mem
```
```
In drivers/clocksource/timer-sp804.c (ffff8000114aa094)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/timer-sp804.c:integrator_cp_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/clocksource/timer-sp804.c:__sp804_clockevents_init
  - drivers/clocksource/timer-sp804.c:sp804_set_next_event
  - drivers/clocksource/timer-sp804.c:sp804_set_next_event
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_shutdown
  - drivers/clocksource/timer-sp804.c:sp804_timer_interrupt
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:sp804_timer_disable
```
```
In drivers/clocksource/timer-imx-sysctr.c (ffff800010b6821c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_timer_interrupt
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_state_shutdown
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_set_next_event
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7ad10)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b100)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_irq
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_shutdown
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_startup
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_send_data
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_send_data
```
```
In drivers/mailbox/pcc.c (ffff800010b7b804)
Location: arch/arm64/include/asm/io.h:37
Inline: True
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7bf60)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_shutdown
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_startup
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_send_data
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7cd70)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_send_data
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_send_data
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_send_data
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8a9bc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:store_refresh
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
  - drivers/memory/brcmstb_dpfe.c:__write_firmware
  - drivers/memory/brcmstb_dpfe.c:__write_firmware
  - drivers/memory/brcmstb_dpfe.c:__write_firmware
  - drivers/memory/brcmstb_dpfe.c:__send_command
  - drivers/memory/brcmstb_dpfe.c:__send_command
  - drivers/memory/brcmstb_dpfe.c:__send_command
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b6fc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:check_nand_stat
  - drivers/memory/fsl_ifc.c:check_nand_stat
```
```
In drivers/memory/mtk-smi.c (ffff800010b8c2a4)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen1
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_mt8173
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
```
```
In drivers/perf/arm-cci.c (ffff800010b913a0)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_stop
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In drivers/perf/arm-ccn.c (ffff800010b922cc)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_irq_handler
  - drivers/perf/arm-ccn.c:arm_ccn_irq_handler
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_overflow_handler
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_disable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_enable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96e9c)
Location: arch/arm64/include/asm/io.h:37
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
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b976f4)
Location: arch/arm64/include/asm/io.h:37
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
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97f3c)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_isr
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_disable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_enable_counter_int
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_disable_counter
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_enable_counter
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_stop_counters
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_start_counters
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_write_counter
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a474)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__pmu_disable
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__pmu_enable
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__handle_irq
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_stop
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c2ec)
Location: arch/arm64/include/asm/io.h:37
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_stop_counters
  - drivers/perf/xgene_pmu.c:xgene_pmu_start_counters
  - drivers/perf/xgene_pmu.c:xgene_pmu_reset_counters
  - drivers/perf/xgene_pmu.c:xgene_pmu_disable_counter_int
  - drivers/perf/xgene_pmu.c:xgene_pmu_enable_counter_int
  - drivers/perf/xgene_pmu.c:xgene_pmu_disable_counter
  - drivers/perf/xgene_pmu.c:xgene_pmu_enable_counter
  - drivers/perf/xgene_pmu.c:xgene_pmu_write_agent1msk
  - drivers/perf/xgene_pmu.c:xgene_pmu_write_agentmsk
  - drivers/perf/xgene_pmu.c:xgene_pmu_write_evttype
  - drivers/perf/xgene_pmu.c:xgene_pmu_write_counter64
  - drivers/perf/xgene_pmu.c:xgene_pmu_write_counter64
  - drivers/perf/xgene_pmu.c:xgene_pmu_v3_unmask_int
  - drivers/perf/xgene_pmu.c:xgene_pmu_unmask_int
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
In arch/arm/kernel/smp_scu.c (c0314524)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/kernel/smp_scu.c:scu_enable
  - arch/arm/kernel/smp_scu.c:scu_enable
```
```
In arch/arm/kernel/smp_twd.c (c0314800)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_timer_dying_cpu
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_handler
  - arch/arm/kernel/smp_twd.c:twd_set_next_event
  - arch/arm/kernel/smp_twd.c:twd_set_next_event
  - arch/arm/kernel/smp_twd.c:twd_set_periodic
  - arch/arm/kernel/smp_twd.c:twd_set_periodic
  - arch/arm/kernel/smp_twd.c:twd_set_oneshot
```
```
In arch/arm/kernel/io.c (c0319e48)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/kernel/io.c:atomic_io_modify
  - arch/arm/kernel/io.c:atomic_io_modify_relaxed
```
```
In arch/arm/mm/cache-feroceon-l2.c (c1509be4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_of_init
```
```
In arch/arm/mm/cache-l2x0.c (c0323ff4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:tauros3_configure
  - arch/arm/mm/cache-l2x0.c:tauros3_configure
  - arch/arm/mm/cache-l2x0.c:tauros3_configure
  - arch/arm/mm/cache-l2x0.c:bcm_clean_range
  - arch/arm/mm/cache-l2x0.c:bcm_clean_range
  - arch/arm/mm/cache-l2x0.c:bcm_clean_range
  - arch/arm/mm/cache-l2x0.c:aurora_disable
  - arch/arm/mm/cache-l2x0.c:aurora_disable
  - arch/arm/mm/cache-l2x0.c:aurora_cache_sync
  - arch/arm/mm/cache-l2x0.c:aurora_flush_all
  - arch/arm/mm/cache-l2x0.c:aurora_pa_range
  - arch/arm/mm/cache-l2x0.c:aurora_pa_range
  - arch/arm/mm/cache-l2x0.c:aurora_pa_range
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_configure
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_all_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_flush_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c310_inv_range_erratum
  - arch/arm/mm/cache-l2x0.c:l2c220_sync
  - arch/arm/mm/cache-l2x0.c:l2c220_flush_range
  - arch/arm/mm/cache-l2x0.c:l2c220_clean_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c220_op_pa_range
  - arch/arm/mm/cache-l2x0.c:l2c220_op_way
  - arch/arm/mm/cache-l2x0.c:l2c210_sync
  - arch/arm/mm/cache-l2x0.c:l2c210_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c210_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c210_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c210_inv_range
  - arch/arm/mm/cache-l2x0.c:l2c_disable
  - arch/arm/mm/cache-l2x0.c:l2c_enable
  - arch/arm/mm/cache-l2x0.c:l2c_enable
  - arch/arm/mm/cache-l2x0.c:__l2c_op_way
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c150b21c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_resume
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_resume
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_start
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_configure
```
```
In arch/arm/mm/cache-uniphier.c (c150ba1c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_init
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_init
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_sync
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_disable
  - arch/arm/mm/cache-uniphier.c:uniphier_cache_maint_all
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_range
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_range
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_maint_common
```
```
In arch/arm/mach-actions/platsmp.c (c032c878)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In arch/arm/mach-alpine/alpine_cpu_pm.c (c032c9b8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-alpine/alpine_cpu_pm.c:alpine_cpu_wakeup
```
```
In arch/arm/mach-aspeed/platsmp.c (c150c21c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_smp_prepare_cpus
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary
```
```
In arch/arm/mach-berlin/platsmp.c (c032cb24)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-berlin/platsmp.c:berlin_cpu_kill
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-berlin/platsmp.c:berlin_boot_secondary
  - arch/arm/mach-berlin/platsmp.c:berlin_boot_secondary
```
```
In arch/arm/mach-exynos/exynos.c (c032cc24)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-exynos/firmware.c (c032d0a0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-exynos/firmware.c:exynos_clear_boot_flag
  - arch/arm/mach-exynos/firmware.c:exynos_set_boot_flag
  - arch/arm/mach-exynos/firmware.c:exynos_resume
  - arch/arm/mach-exynos/firmware.c:exynos_suspend
  - arch/arm/mach-exynos/firmware.c:exynos_suspend
  - arch/arm/mach-exynos/firmware.c:exynos_cpu_suspend
  - arch/arm/mach-exynos/firmware.c:exynos_set_cpu_boot_addr
```
```
In arch/arm/mach-exynos/pm.c (c032d404)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
```
```
In arch/arm/mach-exynos/suspend.c (c032db58)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos_pm_suspend
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_init
```
```
In arch/arm/mach-exynos/platsmp.c (c032e710)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_up
  - arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_down
  - arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c150cadc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_cpu_powerup
```
```
In arch/arm/mach-highbank/highbank.c (c032eed8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-highbank/highbank.c:highbank_power_off
  - arch/arm/mach-highbank/highbank.c:highbank_power_off
```
```
In arch/arm/mach-highbank/system.c (c032f198)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-highbank/system.c:highbank_restart
  - arch/arm/mach-highbank/system.c:highbank_restart
  - arch/arm/mach-highbank/system.c:highbank_set_core_pwr
```
```
In arch/arm/mach-hisi/platmcpm.c (c150cf3c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
```
```
In arch/arm/mach-hisi/platsmp.c (c032f8fc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hi3xxx_boot_secondary
```
```
In arch/arm/mach-hisi/hotplug.c (c032fd48)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-hisi/hotplug.c:hip01_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hip01_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_set_cpu
```
```
In arch/arm/mach-meson/platsmp.c (c0330788)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_die
  - arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot
  - arch/arm/mach-meson/platsmp.c:meson_smp_finalize_secondary_boot
  - arch/arm/mach-meson/platsmp.c:meson_smp_begin_secondary_boot
```
```
In arch/arm/mach-mvebu/system-controller.c (c0330980)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_set_cpu_boot_addr
  - arch/arm/mach-mvebu/system-controller.c:mvebu_restart
  - arch/arm/mach-mvebu/system-controller.c:mvebu_restart
```
```
In arch/arm/mach-mvebu/cpu-reset.c (c0330a84)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_deassert
```
```
In arch/arm/mach-mvebu/coherency.c (c0330b34)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:armada_xp_clear_shared_l2
```
```
In arch/arm/mach-mvebu/pmsu.c (c0331344)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
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
  - arch/arm/mach-mvebu/pmsu.c:mvebu_setup_boot_addr_wa
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_set_cpu_boot_addr
```
```
In arch/arm/mach-mvebu/pm.c (c03314e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_powerdown
```
```
In arch/arm/mach-mvebu/pm-board.c (c03317c0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_enter
```
```
In arch/arm/mach-mvebu/platsmp.c (c03319cc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
  - arch/arm/mach-mvebu/platsmp.c:mv98dx3236_boot_secondary
```
```
In arch/arm/mach-imx/cpu.c (c150e60c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpu.c:imx_set_aips
  - arch/arm/mach-imx/cpu.c:imx_set_aips
  - arch/arm/mach-imx/cpu.c:imx_set_aips
  - arch/arm/mach-imx/cpu.c:imx_set_aips
  - arch/arm/mach-imx/cpu.c:imx_set_aips
  - arch/arm/mach-imx/cpu.c:imx_set_aips
  - arch/arm/mach-imx/cpu.c:imx_set_aips
```
```
In arch/arm/mach-imx/system.c (c150ea54)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/system.c:imx_init_l2cache
```
```
In arch/arm/mach-imx/cpu-imx5.c (c150eb3c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpu-imx5.c:imx5_pmu_init
```
```
In arch/arm/mach-imx/pm-imx5.c (c0331fe8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
  - arch/arm/mach-imx/pm-imx5.c:mx5_cpu_lp_set
```
```
In arch/arm/mach-imx/tzic.c (c0332258)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/tzic.c:tzic_enable_wake
  - arch/arm/mach-imx/tzic.c:tzic_enable_wake
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-imx/tzic.c:tzic_irq_resume
  - arch/arm/mach-imx/tzic.c:tzic_irq_suspend
  - arch/arm/mach-imx/tzic.c:tzic_set_irq_fiq
```
```
In arch/arm/mach-imx/gpc.c (c150f24c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
  - arch/arm/mach-imx/gpc.c:imx_gpc_irq_mask
  - arch/arm/mach-imx/gpc.c:imx_gpc_irq_unmask
  - arch/arm/mach-imx/gpc.c:imx_gpc_restore_all
  - arch/arm/mach-imx/gpc.c:imx_gpc_mask_all
  - arch/arm/mach-imx/gpc.c:imx_gpc_post_resume
  - arch/arm/mach-imx/gpc.c:imx_gpc_post_resume
  - arch/arm/mach-imx/gpc.c:imx_gpc_pre_suspend
  - arch/arm/mach-imx/gpc.c:imx_gpc_pre_suspend
  - arch/arm/mach-imx/gpc.c:imx_gpc_set_l2_mem_power_in_lpm
  - arch/arm/mach-imx/gpc.c:imx_gpc_set_arm_power_down_timing
  - arch/arm/mach-imx/gpc.c:imx_gpc_set_arm_power_up_timing
```
```
In arch/arm/mach-imx/mmdc.c (c0333230)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_stop
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_stop
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
```
```
In arch/arm/mach-imx/src.c (c150f3e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/src.c:imx_src_init
  - arch/arm/mach-imx/src.c:imx_set_cpu_arg
  - arch/arm/mach-imx/src.c:imx_set_cpu_jump
  - arch/arm/mach-imx/src.c:imx_enable_cpu
  - arch/arm/mach-imx/src.c:imx_src_reset_module
```
```
In arch/arm/mach-imx/platsmp.c (c150f49c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:ls1021a_smp_prepare_cpus
```
```
In arch/arm/mach-imx/pm-imx7ulp.c (c1510118)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx7ulp.c:imx7ulp_pm_init
```
```
In arch/arm/mach-imx/pm-imx6.c (c15105c4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_ccm_init
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
In arch/arm/mach-imx/mach-imx51.c (c1510798)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
```
```
In arch/arm/mach-mediatek/platsmp.c (c0334ae8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mediatek/platsmp.c:mtk_boot_secondary
```
```
In arch/arm/mach-mediatek/mediatek.c (c1510c4c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
```
```
In arch/arm/mach-milbeaut/platsmp.c (c0334bd4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-milbeaut/platsmp.c:m10v_cpu_kill
  - arch/arm/mach-milbeaut/platsmp.c:m10v_boot_secondary
```
```
In arch/arm/mach-npcm/platsmp.c (c0334e30)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary
```
```
In arch/arm/mach-omap2/control.c (c03359ec)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:am43xx_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_init
  - arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf
  - arch/arm/mach-omap2/control.c:omap3630_ctrl_disable_rta
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_control_restore_context
  - arch/arm/mach-omap2/control.c:omap3_clear_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_mode
  - arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_addr
  - arch/arm/mach-omap2/control.c:omap3_ctrl_write_boot_mode
  - arch/arm/mach-omap2/control.c:omap_ctrl_writeb
```
```
In arch/arm/mach-omap2/timer.c (c1512db4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/timer.c:omap_clkevt_unidle
  - arch/arm/mach-omap2/timer.c:omap_clkevt_unidle
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_periodic
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_shutdown
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_next_event
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_set_next_event
  - arch/arm/mach-omap2/timer.c:omap2_gp_timer_interrupt
```
```
In arch/arm/mach-omap2/dma.c (c03362e8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/dma.c:omap2_clear_dma
```
```
In arch/arm/mach-omap2/wd_timer.c (c0336368)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/wd_timer.c:omap2_wd_timer_disable
  - arch/arm/mach-omap2/wd_timer.c:omap2_wd_timer_disable
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c03380d0)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In arch/arm/mach-omap2/sram.c (c1514940)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
  - arch/arm/mach-omap2/sram.c:omap_sram_init
```
```
In arch/arm/mach-omap2/omap_hwmod_reset.c (c033b5f0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod_reset.c:omap_hwmod_aess_preprogram
```
```
In arch/arm/mach-omap2/sdrc.c (c1514bbc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init
  - arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init
  - arch/arm/mach-omap2/sdrc.c:omap2_sdrc_init
  - arch/arm/mach-omap2/sdrc.c:omap2_sms_restore_context
```
```
In arch/arm/mach-omap2/omap4-common.c (c033bea8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger
  - arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger
  - arch/arm/mach-omap2/omap4-common.c:gic_timer_retrigger
  - arch/arm/mach-omap2/omap4-common.c:gic_dist_enable
  - arch/arm/mach-omap2/omap4-common.c:gic_dist_disable
  - arch/arm/mach-omap2/omap4-common.c:omap_interconnect_sync
  - arch/arm/mach-omap2/omap4-common.c:omap_interconnect_sync
  - arch/arm/mach-omap2/omap4-common.c:omap4_mb
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c15150f8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:omap_wakeupgen_cpu_dead
  - arch/arm/mach-omap2/omap-wakeupgen.c:omap_wakeupgen_cpu_online
  - arch/arm/mach-omap2/omap-wakeupgen.c:omap_wakeupgen_cpu_online
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_sar_clear
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_unmask
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_mask
```
```
In arch/arm/mach-omap2/omap-smp.c (c1515498)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/omap-smp.c:omap4_boot_secondary
```
```
In arch/arm/mach-omap2/omap-hotplug.c (c033ca84)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-hotplug.c:omap4_cpu_die
```
```
In arch/arm/mach-omap2/ti81xx-restart.c (c033cec0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/ti81xx-restart.c:ti81xx_restart
```
```
In arch/arm/mach-omap2/omap-mpuss-lowpower.c (c15158c0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_early_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_hotplug_cpu
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:scu_pwrst_prepare
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d4f0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
```
```
In arch/arm/mach-omap2/prm2xxx_3xxx.c (c0340788)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_clear_all_wkdeps
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_del_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_add_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_logic_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_assert_hardreset
```
```
In arch/arm/mach-omap2/prm3xxx.c (c0340cb8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_disable_hdwr_sar
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_enable_hdwr_sar
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_clear_all_prev_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_global_cold_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3430_pre_es3_1_reconfigure_io_chain
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_init_pm
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reset_modem
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_reset_modem
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_clear_mod_irqs
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_restore_irqen
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_save_and_clear_irqen
  - arch/arm/mach-omap2/prm3xxx.c:omap3xxx_prm_dpll3_reset
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_rmw
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vcvp_write
  - arch/arm/mach-omap2/prm3xxx.c:omap3_prm_vp_clear_txdone
```
```
In arch/arm/mach-omap2/cm3xxx.c (c0341820)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3_cm_restore_context
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_deny_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_allow_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clear_all_sleepdeps
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_del_sleepdep
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_add_sleepdep
```
```
In arch/arm/mach-omap2/cminst44xx.c (c03421c8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_del_wkup_sleep_dep
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_add_wkup_sleep_dep
  - arch/arm/mach-omap2/cminst44xx.c:omap4_cminst_module_disable
  - arch/arm/mach-omap2/cminst44xx.c:_clktrctrl_write
```
```
In arch/arm/mach-omap2/prm44xx.c (c0342d40)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm44xx.c:prm_restore_context
  - arch/arm/mach-omap2/prm44xx.c:prm_restore_context
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_reconfigure_io_chain
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_restore_irqen
  - arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_save_and_clear_irqen
```
```
In arch/arm/mach-omap2/prcm_mpu44xx.c (c0342dd8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prcm_mpu44xx.c:omap4_prcm_mpu_rmw_inst_reg_bits
```
```
In arch/arm/mach-omap2/prminst44xx.c (c034317c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset
  - arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset
```
```
In arch/arm/mach-omap2/prm33xx.c (c034385c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_restore_context
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_global_warm_sw_reset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_logic_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_clear_all_prev_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_lowpwrstchange
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm33xx.c:am33xx_prm_assert_hardreset
```
```
In arch/arm/mach-omap2/cm33xx.c (c0343c10)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_restore_context
  - arch/arm/mach-omap2/cm33xx.c:am33xx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm33xx.c:am33xx_cm_module_disable
  - arch/arm/mach-omap2/cm33xx.c:am33xx_cm_module_enable
```
```
In arch/arm/mach-omap2/vc.c (c151752c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap4_set_timings
```
```
In arch/arm/mach-omap2/powerdomains3xxx_data.c (c03466f8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomains3xxx_data.c:ti81xx_pwrdm_set_next_pwrst
```
```
In arch/arm/mach-omap2/omap_phy_internal.c (c1518e68)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down
```
```
In arch/arm/mach-qcom/platsmp.c (c0348d1c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv2_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
  - arch/arm/mach-qcom/platsmp.c:kpssv1_release_secondary
```
```
In arch/arm/mach-rockchip/rockchip.c (c1518f74)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
```
```
In arch/arm/mach-rockchip/platsmp.c (c0349604)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In arch/arm/mach-shmobile/setup-r8a7740.c (c151981c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_generic_init
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
```
```
In arch/arm/mach-shmobile/setup-r8a7778.c (c1519960)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
```
```
In arch/arm/mach-shmobile/setup-r8a7779.c (c15199c4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
  - arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_init_irq_dt
```
```
In arch/arm/mach-shmobile/setup-rcar-gen2.c (c1519be4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
```
```
In arch/arm/mach-shmobile/platsmp-apmu.c (c034979c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_boot_secondary
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_cpu_shutdown
```
```
In arch/arm/mach-shmobile/pm-rcar-gen2.c (c151a468)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
```
```
In arch/arm/mach-shmobile/smp-sh73a0.c (c151a500)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_smp_prepare_cpus
  - arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_smp_prepare_cpus
  - arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_boot_secondary
  - arch/arm/mach-shmobile/smp-sh73a0.c:sh73a0_boot_secondary
```
```
In arch/arm/mach-shmobile/smp-r8a7779.c (c151a5e4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-r8a7779.c:r8a7779_smp_prepare_cpus
```
```
In arch/arm/mach-shmobile/smp-emev2.c (c151a638)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus
```
```
In arch/arm/mach-tegra/irq.c (c034a5b4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-tegra/irq.c:tegra_gic_notifier
```
```
In arch/arm/mach-tegra/reset.c (c151a984)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init
  - arch/arm/mach-tegra/reset.c:tegra_cpu_reset_handler_init
```
```
In arch/arm/mach-vexpress/dcscb.c (c034cda8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/dcscb.c:dcscb_cluster_powerup
  - arch/arm/mach-vexpress/dcscb.c:dcscb_cpu_powerup
```
```
In arch/arm/mach-vexpress/spc.c (c034d240)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:spc_set_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
  - arch/arm/mach-vexpress/spc.c:ve_spc_powerdown
  - arch/arm/mach-vexpress/spc.c:ve_spc_set_resume_addr
  - arch/arm/mach-vexpress/spc.c:ve_spc_cpu_wakeup_irq
  - arch/arm/mach-vexpress/spc.c:ve_spc_global_wakeup_irq
```
```
In arch/arm/plat-samsung/cpu.c (c151b8e8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/plat-samsung/cpu.c:s3c64xx_init_cpu
```
```
In arch/arm/plat-samsung/pm-common.c (c034f9cc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - arch/arm/plat-samsung/pm-common.c:s3c_pm_do_restore_core
  - arch/arm/plat-samsung/pm-common.c:s3c_pm_do_restore
```
```
In kernel/irq/generic-chip.c (c03d0a14)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In lib/iomap_copy.c (c07e3a98)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In lib/stmp_device.c (c0810154)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_clear_poll_bit
```
```
In drivers/irqchip/irq-al-fic.c (c1549764)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_retrigger
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/exynos-combiner.c (c08137d8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_resume
  - drivers/irqchip/exynos-combiner.c:combiner_resume
  - drivers/irqchip/exynos-combiner.c:combiner_init
  - drivers/irqchip/exynos-combiner.c:combiner_unmask_irq
  - drivers/irqchip/exynos-combiner.c:combiner_mask_irq
```
```
In drivers/irqchip/irq-hip04.c (c1549cd0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-hip04.c:hip04_irq_starting_cpu
  - drivers/irqchip/irq-hip04.c:hip04_irq_starting_cpu
  - drivers/irqchip/irq-hip04.c:hip04_raise_softirq
  - drivers/irqchip/irq-hip04.c:hip04_handle_irq
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
  - drivers/irqchip/irq-hip04.c:hip04_eoi_irq
  - drivers/irqchip/irq-hip04.c:hip04_unmask_irq
  - drivers/irqchip/irq-hip04.c:hip04_mask_irq
```
```
In drivers/irqchip/irq-tegra.c (c1549e48)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_resume
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_resume
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_resume
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_resume
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_resume
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_resume
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_suspend
  - drivers/irqchip/irq-tegra.c:tegra_retrigger
  - drivers/irqchip/irq-tegra.c:tegra_eoi
  - drivers/irqchip/irq-tegra.c:tegra_unmask
  - drivers/irqchip/irq-tegra.c:tegra_mask
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c154a048)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
```
```
In drivers/irqchip/irq-orion.c (c154a614)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
```
```
In drivers/irqchip/irq-omap-intc.c (c154a9d8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-omap-intc.c:omap_intc_handle_irq
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_suspend
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_irq_soft_reset
  - drivers/irqchip/irq-omap-intc.c:omap_mask_ack_irq
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_resume_idle
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_resume_idle
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_prepare_idle
  - drivers/irqchip/irq-omap-intc.c:omap3_intc_prepare_idle
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
  - drivers/irqchip/irq-omap-intc.c:omap_intc_restore_context
```
```
In drivers/irqchip/irq-gic.c (c0815488)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_send_sgi
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_dist_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_if_down
  - drivers/irqchip/irq-gic.c:gic_cpu_init
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_cpu_if_up
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_irq
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic.c:gic_eoi_irq
  - drivers/irqchip/irq-gic.c:gic_unmask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-common.c (c08162b0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_cpu_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_dist_config
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v3.c (c154ba80)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_poke_irq
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081cc14)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_inv
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
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
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d480)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_mpic_send_doorbell
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_perf_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_smp_cpu_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_smp_cpu_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_smp_cpu_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_smp_cpu_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_irq_unmask
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_irq_unmask
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_irq_mask
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_irq_mask
```
```
In drivers/irqchip/irq-rda-intc.c (c154d688)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda8810_intc_init
  - drivers/irqchip/irq-rda-intc.c:rda_intc_unmask_irq
  - drivers/irqchip/irq-rda-intc.c:rda_intc_mask_irq
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef7c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_write32
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fe98)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/irqchip/irq-crossbar.c (c08208fc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:crossbar_writel
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c0820e74)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-mtk-cirq.c (c0821228)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_resume
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_set_type
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_unmask
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_mask
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c154e408)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
  - drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_restore
  - drivers/irqchip/irq-imx-gpcv2.c:gpcv2_wakeup_source_save
```
```
In drivers/irqchip/irq-aspeed-vic.c (c154e56c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/irqchip/irq-aspeed-vic.c:avic_mask_ack_irq
  - drivers/irqchip/irq-aspeed-vic.c:avic_mask_ack_irq
  - drivers/irqchip/irq-aspeed-vic.c:avic_unmask_irq
  - drivers/irqchip/irq-aspeed-vic.c:avic_mask_irq
  - drivers/irqchip/irq-aspeed-vic.c:avic_ack_irq
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0821e38)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_resume
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_irq_set_type
```
```
In drivers/irqchip/irq-meson-gpio.c (c0822454)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (c08227c4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:pdc_enable_intr
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c0823498)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/arm-cci.c (c0823640)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/bus/brcmstb_gisb.c (c0823f54)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:gisb_write
  - drivers/bus/brcmstb_gisb.c:gisb_write
```
```
In drivers/bus/imx-weim.c (c0824438)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/bus/imx-weim.c:weim_parse_dt
```
```
In drivers/bus/mvebu-mbus.c (c0824d54)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_resume
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_resume
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_resume
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_resume
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_resume
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_resume
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dove_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dove_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_default_save_cpu_target
```
```
In drivers/bus/omap_l3_noc.c (c0825ea4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:l3_resume_noirq
  - drivers/bus/omap_l3_noc.c:l3_resume_noirq
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
```
```
In drivers/bus/qcom-ebi2.c (c0826730)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/bus/ti-sysc.c (c0828c60)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_clk_quirk_i2c
  - drivers/bus/ti-sysc.c:sysc_pre_reset_quirk_hdq1w
  - drivers/bus/ti-sysc.c:sysc_disable_module
  - drivers/bus/ti-sysc.c:sysc_disable_module
  - drivers/bus/ti-sysc.c:sysc_enable_module
  - drivers/bus/ti-sysc.c:sysc_enable_module
  - drivers/bus/ti-sysc.c:sysc_enable_module
```
```
In drivers/bus/uniphier-system-bus.c (c08294dc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_set_reg
```
```
In drivers/phy/marvell/phy-armada375-usb2.c (c082bbd0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_init
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082be74)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c460)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_reset
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_reset
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_reset
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
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_on
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_init
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cc8c)
Location: arch/arm/include/asm/io.h:93
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
In drivers/pinctrl/pinctrl-amd.c (c0834330)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083ab58)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_resume
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_suspend
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083d394)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux
```
```
In drivers/pinctrl/pinctrl-single.c (c083f1e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writel
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c0843164)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_resume
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_set
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_set_mux
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c08434c8)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_off
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
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinmux_set
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0845c68)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c0848644)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set
```
```
In drivers/pinctrl/freescale/pinctrl-imx7ulp.c (c0849bc8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx7ulp.c:imx7ulp_pmx_gpio_set_direction
```
```
In drivers/pinctrl/freescale/pinctrl-vf610.c (c0849c68)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-vf610.c:vf610_pmx_gpio_set_direction
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a86c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_mmio_mpp_ctrl_set
```
```
In drivers/pinctrl/mvebu/pinctrl-dove.c (c084b984)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio1_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_audio0_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_mpp4_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pmu_mpp_ctrl_set
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-xp.c (c084c1c8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-xp.c:armada_xp_pinctrl_resume
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084c820)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_unmask
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_mask
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_ack
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084e818)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_ps_hold_restart
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c08501dc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_direction
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_gpio_set_value
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinconf_rw
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinmux_set_mux
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852b04)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_pinctrl_resume
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_release_resources
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_request_resources
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_unmask
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_ack
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_mask
```
```
In drivers/pinctrl/samsung/pinctrl-exynos-arm.c (c0852d78)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos-arm.c:s5pv210_retention_disable
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853a5c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7778.c (c0855a00)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855c30)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858df4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_resume
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_resume
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_suspend
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_suspend
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_type
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_type
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_ack
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_unmask
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_mask
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_flip_edge
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085ba84)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_hw_set_value
```
```
In drivers/gpio/gpio-mmio.c (c0867f80)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/gpio/gpio-mmio.c:bgpio_write32
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868a30)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_ack_irq
```
```
In drivers/gpio/gpio-mvebu.c (c0869c90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_resume
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
```
```
In drivers/gpio/gpio-mxc.c (c086c45c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
  - drivers/gpio/gpio-mxc.c:gpio_set_irq_type
```
```
In drivers/gpio/gpio-omap.c (c086d6bc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
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
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_restore_context
  - drivers/gpio/gpio-omap.c:omap_gpio_set_multiple
  - drivers/gpio/gpio-omap.c:omap_gpio_set_config
  - drivers/gpio/gpio-omap.c:omap_gpio_set_config
  - drivers/gpio/gpio-omap.c:omap_gpio_set_config
  - drivers/gpio/gpio-omap.c:omap_gpio_output
  - drivers/gpio/gpio-omap.c:omap_gpio_input
  - drivers/gpio/gpio-omap.c:omap_gpio_free
  - drivers/gpio/gpio-omap.c:omap_gpio_free
  - drivers/gpio/gpio-omap.c:omap_mpuio_resume_noirq
  - drivers/gpio/gpio-omap.c:omap_mpuio_suspend_noirq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_unmask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_mask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_mask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_mask_irq
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_shutdown
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_startup
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
  - drivers/gpio/gpio-omap.c:omap_enable_gpio_module
  - drivers/gpio/gpio-omap.c:omap_enable_gpio_module
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_set_gpio_triggering
  - drivers/gpio/gpio-omap.c:omap_clear_gpio_debounce
  - drivers/gpio/gpio-omap.c:omap_clear_gpio_debounce
  - drivers/gpio/gpio-omap.c:omap_set_gpio_dataout_mask
  - drivers/gpio/gpio-omap.c:omap_set_gpio_dataout_reg
```
```
In drivers/gpio/gpio-tegra.c (c087198c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_suspend
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_resume
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_unmask
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_mask
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_ack
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set_config
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set_config
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set_config
  - drivers/gpio/gpio-tegra.c:tegra_gpio_direction_output
  - drivers/gpio/gpio-tegra.c:tegra_gpio_direction_output
  - drivers/gpio/gpio-tegra.c:tegra_gpio_direction_input
  - drivers/gpio/gpio-tegra.c:tegra_gpio_direction_input
  - drivers/gpio/gpio-tegra.c:tegra_gpio_set
  - drivers/gpio/gpio-tegra.c:tegra_gpio_free
```
```
In drivers/gpio/gpio-vf610.c (c0873a04)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_unmask
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_mask
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_ack
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_output
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_output
  - drivers/gpio/gpio-vf610.c:vf610_gpio_direction_input
```
```
In drivers/gpio/gpio-xilinx.c (c0874074)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
```
```
In drivers/gpio/gpio-zevio.c (c08742b8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_probe
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_input
  - drivers/gpio/gpio-zevio.c:zevio_gpio_set
```
```
In drivers/pci/access.c (c08774a0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c0889b78)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/pci/quirks.c (c0894d90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/msi.c (c08a00ec)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msix_desc_mask_irq
```
```
In drivers/pci/controller/pcie-cadence.c (c08a62f4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6aa0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7524)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a82dc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9cfc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_resume
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_rd_conf
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_wr_conf
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_wr_conf
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pci-mvebu.c:mvebu_pci_bridge_emul_base_conf_write
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_setup_hw
```
```
In drivers/pci/controller/pci-tegra.c (c08aca94)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq
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
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_map_bus
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08adab0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_cfg_base
```
```
In drivers/pci/controller/pcie-rcar.c (c08ae134)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
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
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b02e4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b1428)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_unmap_bus
  - drivers/pci/controller/pci-v3-semi.c:v3_unmap_bus
  - drivers/pci/controller/pci-v3-semi.c:v3_map_bus
  - drivers/pci/controller/pci-v3-semi.c:v3_map_bus
```
```
In drivers/pci/controller/pcie-altera.c (c08b2828)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:s10_rp_write_cfg
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2c04)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
```
```
In drivers/pci/controller/pcie-rockchip.c (c08b3618)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b4498)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_start
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5544)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_map_bus
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_msi_ack_irq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_write
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_config_read
```
```
In drivers/pci/controller/dwc/pcie-designware.c (c08b66bc)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9284)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c15523a8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_raise_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_raise_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_raise_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_irq_handler
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_host_init
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_host_init
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_wrapper_interrupts
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_wrapper_interrupts
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_stop_link
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bbcdc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bdd54)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_3_2_ltssm_enable
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_2_1_0_ltssm_enable
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08be614)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_dbi_r_mode
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf084)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_unmask
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_mask
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_ack
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_stop_link
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_establish_link
```
```
In drivers/video/fbdev/core/cfbfillrect.c (c08da520)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (c08dabdc)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/video/fbdev/core/cfbimgblt.c (c08dbf64)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/video/fbdev/imsttfb.c (c08dda80)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_pan_display
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
```
```
In drivers/video/fbdev/amba-clcd.c (c08df460)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_setcolreg
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/video/fbdev/omap2/omapfb/vrfb.c (c08e0870)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_setup
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_setup
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_setup
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_restore_context
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_restore_context
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_restore_context
```
```
In drivers/video/fbdev/mx3fb.c (c08e3354)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/video/fbdev/mx3fb.c:sdc_set_brightness
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/amba/tegra-ahb.c (c08e6118)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/amba/tegra-ahb.c:tegra_ahb_resume
  - drivers/amba/tegra-ahb.c:tegra_ahb_enable_smmu
```
```
In drivers/clk/clk-divider.c (c08ef9d4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (c08f0d78)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (c08f10c4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (c08f15d8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (c08f21b8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
```
```
In drivers/clk/clk-highbank.c (c08f4884)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-highbank.c:clk_periclk_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_set_rate
  - drivers/clk/clk-highbank.c:clk_pll_disable
  - drivers/clk/clk-highbank.c:clk_pll_enable
  - drivers/clk/clk-highbank.c:clk_pll_unprepare
  - drivers/clk/clk-highbank.c:clk_pll_prepare
```
```
In drivers/clk/clk-hsdk-pll.c (c08f4dac)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/clk/clk-milbeaut.c (c08f4eb4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/clk-milbeaut.c:m10v_mux_set_parent
```
```
In drivers/clk/clk-qoriq.c (c08f5788)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:mux_set_parent
  - drivers/clk/clk-qoriq.c:mux_set_parent
```
```
In drivers/clk/berlin/berlin2-avpll.c (c08f6dd0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_enable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_disable
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_enable
```
```
In drivers/clk/berlin/berlin2-div.c (c08f72b0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
```
```
In drivers/clk/hisilicon/clkgate-separated.c (c08f7cc0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (c08f7ea4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (c08f8228)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
```
```
In drivers/clk/hisilicon/clk-hi3620.c (c08f8560)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
  - drivers/clk/hisilicon/clk-hi3620.c:mmc_clk_set_timing
```
```
In drivers/clk/hisilicon/clk-hix5hd2.c (c08f88b0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_disable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_disable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_enable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_complex_enable
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_unprepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
  - drivers/clk/hisilicon/clk-hix5hd2.c:clk_ether_prepare
```
```
In drivers/clk/hisilicon/reset.c (c08f8ee8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/imx/clk.c (c1557ed8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_mmdc_mask_handshake
```
```
In drivers/clk/imx/clk-composite-8m.c (c08f9df0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (c08fa504)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
```
```
In drivers/clk/imx/clk-fixup-div.c (c08fa8e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (c08faae8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-frac-pll.c (c08fae1c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_unprepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-gate2.c (c08fb284)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfd.c (c08fb658)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfd.c:clk_pfd_set_rate
  - drivers/clk/imx/clk-pfd.c:clk_pfd_set_rate
  - drivers/clk/imx/clk-pfd.c:clk_pfd_disable
  - drivers/clk/imx/clk-pfd.c:clk_pfd_enable
```
```
In drivers/clk/imx/clk-pfdv2.c (c08fba80)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv2.c (c08fbe64)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_unprepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_set_rate
```
```
In drivers/clk/imx/clk-pllv3.c (c08fc6f8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_unprepare
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare
```
```
In drivers/clk/imx/clk-pllv4.c (c08fcd30)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_disable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_set_rate
```
```
In drivers/clk/imx/clk-sccg-pll.c (c08fd38c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_parent
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_set_rate
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_unprepare
  - drivers/clk/imx/clk-sccg-pll.c:clk_sccg_pll_prepare
```
```
In drivers/clk/imx/clk-pll14xx.c (c08fe374)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_unprepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
```
```
In drivers/clk/imx/clk-imx5.c (c155bad8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
```
```
In drivers/clk/imx/clk-imx6q.c (c155eca0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
```
```
In drivers/clk/imx/clk-imx6sl.c (c08fe710)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_set_wait_clk
```
```
In drivers/clk/imx/clk-imx6sll.c (c15653a0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
```
```
In drivers/clk/imx/clk-vf610.c (c08fe8b4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/imx/clk-vf610.c:vf610_clk_resume
  - drivers/clk/imx/clk-vf610.c:vf610_clk_resume
  - drivers/clk/imx/clk-vf610.c:vf610_clk_resume
  - drivers/clk/imx/clk-vf610.c:vf610_clk_resume
  - drivers/clk/imx/clk-vf610.c:vf610_clk_resume
  - drivers/clk/imx/clk-vf610.c:vf610_clk_resume
```
```
In drivers/clk/mediatek/clk-pll.c (c08ff364)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
```
```
In drivers/clk/mediatek/clk-apmixed.c (c08fff44)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_unprepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
```
```
In drivers/clk/mvebu/common.c (c09033e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_resume
```
```
In drivers/clk/mvebu/clk-cpu.c (c09036bc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
  - drivers/clk/mvebu/clk-cpu.c:clk_cpu_set_rate
```
```
In drivers/clk/mvebu/clk-corediv.c (c090393c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_set_rate
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_disable
  - drivers/clk/mvebu/clk-corediv.c:clk_corediv_enable
```
```
In drivers/clk/mvebu/dove-divider.c (c0903da4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
```
```
In drivers/clk/renesas/clk-emev2.c (c157e364)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_write
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (c09042ec)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_div_set_rate
  - drivers/clk/renesas/r9a06g032-clocks.c:clk_rdesc_set
```
```
In drivers/clk/renesas/clk-sh73a0.c (c15802ec)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (c0904684)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (c09048b4)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c0905864)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_deassert
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_assert
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_reset
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_reset
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-mstp.c (c0905b38)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/renesas/clk-div6.c (c0905f88)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_parent
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_set_rate
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_disable
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_enable
```
```
In drivers/clk/rockchip/clk.c (c09061d4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_restart_notify
```
```
In drivers/clk/rockchip/clk-pll.c (c0906530)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_disable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3399_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_disable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_disable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_enable
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3036_pll_set_params
```
```
In drivers/clk/rockchip/clk-cpu.c (c0907fb4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_set_dividers
```
```
In drivers/clk/rockchip/clk-half-divider.c (c090874c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (c0908b90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (c0908e94)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_mmc_set_phase
```
```
In drivers/clk/rockchip/softrst.c (c09096b0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/rockchip/clk-rk3036.c (c1583484)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init
```
```
In drivers/clk/rockchip/clk-rk3288.c (c0909860)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_shutdown
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_resume
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend
  - drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_suspend
```
```
In drivers/clk/samsung/clk.c (c09098bc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/samsung/clk.c:samsung_clk_resume
  - drivers/clk/samsung/clk.c:samsung_clk_suspend
```
```
In drivers/clk/samsung/clk-pll.c (c0909dd8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2650x_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll2550xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_upll_disable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_upll_enable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_mpll_disable
  - drivers/clk/samsung/clk-pll.c:samsung_s3c2410_mpll_enable
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll36xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll35xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_disable
  - drivers/clk/samsung/clk-pll.c:samsung_pll3xxx_enable
```
```
In drivers/clk/samsung/clk-cpu.c (c090b570)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_set_safe_div
```
```
In drivers/clk/samsung/clk-exynos5250.c (c158523c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5250.c:exynos5250_clk_of_clk_init_driver
  - drivers/clk/samsung/clk-exynos5250.c:exynos5250_clk_of_clk_init_driver
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c090b7a8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_resume
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_clk_save
```
```
In drivers/clk/samsung/clk-exynos-clkout.c (c090b8d8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_resume
```
```
In drivers/clk/tegra/clk.c (c090b958)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/clk/tegra/clk-dfll.c (c090c260)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config
  - drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config
  - drivers/clk/tegra/clk-dfll.c:dfll_set_open_loop_config
  - drivers/clk/tegra/clk-dfll.c:dfll_enable
  - drivers/clk/tegra/clk-dfll.c:dfll_disable
```
```
In drivers/clk/tegra/clk-divider.c (c090db0c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-divider.c:clk_frac_div_set_rate
```
```
In drivers/clk/tegra/clk-periph-fixed.c (c090e298)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_periph_fixed_disable
  - drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_periph_fixed_enable
```
```
In drivers/clk/tegra/clk-periph-gate.c (c090e668)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_disable
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable
  - drivers/clk/tegra/clk-periph-gate.c:clk_periph_enable
```
```
In drivers/clk/tegra/clk-pll.c (c0911dc0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle_tegra114
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc
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
  - drivers/clk/tegra/clk-pll.c:_program_pll
  - drivers/clk/tegra/clk-pll.c:_program_pll
  - drivers/clk/tegra/clk-pll.c:_program_pll
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
```
```
In drivers/clk/tegra/clk-pll-out.c (c09120c4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-pll-out.c:clk_pll_out_disable
  - drivers/clk/tegra/clk-pll-out.c:clk_pll_out_enable
```
```
In drivers/clk/tegra/clk-sdmmc-mux.c (c09124f0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_set_rate
  - drivers/clk/tegra/clk-sdmmc-mux.c:clk_sdmmc_mux_set_parent
```
```
In drivers/clk/tegra/clk-super.c (c0912884)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-super.c:clk_super_set_parent
  - drivers/clk/tegra/clk-super.c:clk_super_set_parent
```
```
In drivers/clk/tegra/clk-tegra-audio.c (c158660c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra-audio.c:tegra_audio_clk_init
```
```
In drivers/clk/tegra/clk-tegra-pmc.c (c1586bbc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init
```
```
In drivers/clk/tegra/clk-emc.c (c0912e24)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
```
```
In drivers/clk/tegra/clk-tegra20.c (c09137bc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra20.c:tegra20_disable_cpu_clock
  - drivers/clk/tegra/clk-tegra20.c:tegra20_enable_cpu_clock
  - drivers/clk/tegra/clk-tegra20.c:tegra20_cpu_out_of_reset
  - drivers/clk/tegra/clk-tegra20.c:tegra20_put_cpu_in_reset
```
```
In drivers/clk/tegra/clk-tegra30.c (c0913e04)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_clock_suspend
  - drivers/clk/tegra/clk-tegra30.c:tegra30_disable_cpu_clock
  - drivers/clk/tegra/clk-tegra30.c:tegra30_enable_cpu_clock
  - drivers/clk/tegra/clk-tegra30.c:tegra30_cpu_out_of_reset
  - drivers/clk/tegra/clk-tegra30.c:tegra30_put_cpu_in_reset
```
```
In drivers/clk/tegra/clk-tegra114.c (c0914238)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_deassert_dfll_dvco_reset
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_assert_dfll_dvco_reset
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_init
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_init
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_init
  - drivers/clk/tegra/clk-tegra114.c:tegra114_clock_tune_cpu_trimmers_high
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra114.c:tegra114_cpu_clock_suspend
```
```
In drivers/clk/tegra/clk-tegra124.c (c1589848)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre
  - drivers/clk/tegra/clk-tegra124.c:tegra124_reset_deassert
  - drivers/clk/tegra/clk-tegra124.c:tegra124_reset_assert
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_resume
  - drivers/clk/tegra/clk-tegra124.c:tegra124_cpu_clock_suspend
```
```
In drivers/clk/ti/clk.c (c091584c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/ti/clk.c:clk_memmap_rmw
  - drivers/clk/ti/clk.c:clk_memmap_rmw
  - drivers/clk/ti/clk.c:clk_memmap_writel
  - drivers/clk/ti/clk.c:clk_memmap_writel
```
```
In drivers/clk/ti/fapll.c (c091a3e8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/ti/fapll.c:ti_fapll_synth_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_set_frac_rate
  - drivers/clk/ti/fapll.c:ti_fapll_synth_disable
  - drivers/clk/ti/fapll.c:ti_fapll_synth_enable
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_set_rate
  - drivers/clk/ti/fapll.c:ti_fapll_disable
  - drivers/clk/ti/fapll.c:ti_fapll_enable
```
```
In drivers/clk/ti/clk-dra7-atl.c (c091ac04)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/clk-dra7-atl.c:atl_clk_disable
  - drivers/clk/ti/clk-dra7-atl.c:atl_clk_enable
  - drivers/clk/ti/clk-dra7-atl.c:atl_clk_enable
```
```
In drivers/clk/ti/adpll.c (c091b9ec)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_unprepare
  - drivers/clk/ti/adpll.c:ti_adpll_prepare
```
```
In drivers/clk/versatile/clk-sp810.c (c091d454)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
```
```
In drivers/dma/amba-pl08x.c (c09215d0)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
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
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
  - drivers/dma/amba-pl08x.c:pl08x_start_next_txd
```
```
In drivers/dma/mv_xor.c (c0923e20)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_resume
  - drivers/dma/mv_xor.c:mv_xor_resume
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows_a3700
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_conf_mbus_windows
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_add_io_win
  - drivers/dma/mv_xor.c:mv_xor_add_io_win
  - drivers/dma/mv_xor.c:mv_xor_add_io_win
  - drivers/dma/mv_xor.c:mv_xor_add_io_win
  - drivers/dma/mv_xor.c:mv_chan_start_new_chain
  - drivers/dma/mv_xor.c:mv_chan_activate
```
```
In drivers/dma/mxs-dma.c (c158ea64)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/mxs-dma.c:mxs_dma_resume_chan
  - drivers/dma/mxs-dma.c:mxs_dma_resume_chan
  - drivers/dma/mxs-dma.c:mxs_dma_pause_chan
  - drivers/dma/mxs-dma.c:mxs_dma_pause_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_enable_chan
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
```
```
In drivers/dma/ipu/ipu_irq.c (c0926f5c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_ack
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (c158ee6c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
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
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
```
```
In drivers/dma/tegra20-apb-dma.c (c0929bbc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_terminate_all
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc
  - drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc
  - drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc
  - drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc
  - drivers/dma/tegra20-apb-dma.c:tdc_configure_next_head_desc
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_start
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_stop
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_stop
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_stop
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_global_pause
```
```
In drivers/dma/ti/edma.c (c092cabc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_pm_suspend
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_xbar_event_map
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_alloc_chan_resources
  - drivers/dma/ti/edma.c:edma_alloc_chan_resources
  - drivers/dma/ti/edma.c:edma_alloc_chan_resources
  - drivers/dma/ti/edma.c:edma_alloc_chan_resources
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
  - drivers/dma/ti/edma.c:edma_dma_resume
  - drivers/dma/ti/edma.c:edma_dma_pause
  - drivers/dma/ti/edma.c:edma_execute
  - drivers/dma/ti/edma.c:edma_free_channel
  - drivers/dma/ti/edma.c:edma_assign_channel_eventq
  - drivers/dma/ti/edma.c:edma_clean_channel
  - drivers/dma/ti/edma.c:edma_clean_channel
  - drivers/dma/ti/edma.c:edma_clean_channel
  - drivers/dma/ti/edma.c:edma_clean_channel
  - drivers/dma/ti/edma.c:edma_trigger_channel
  - drivers/dma/ti/edma.c:edma_stop
  - drivers/dma/ti/edma.c:edma_stop
  - drivers/dma/ti/edma.c:edma_stop
  - drivers/dma/ti/edma.c:edma_stop
  - drivers/dma/ti/edma.c:edma_stop
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_start
  - drivers/dma/ti/edma.c:edma_link
```
```
In drivers/dma/ti/omap-dma.c (c0930850)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/soc/actions/owl-sps-helper.c (c0933910)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/soc/dove/pmu.c (c158f390)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
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
  - drivers/soc/dove/pmu.c:pmu_reset_reset
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935d0c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/qcom/spm.c (c0938124)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:spm_set_low_power_mode
```
```
In drivers/soc/renesas/r9a06g032-smp.c (c093852c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_boot_secondary
```
```
In drivers/soc/renesas/rcar-rst.c (c0938594)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_enable_wdt_reset
```
```
In drivers/soc/renesas/rcar-sysc.c (c0938618)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/soc/renesas/rmobile-sysc.c (c0938af8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/renesas/rmobile-sysc.c:__rmobile_pd_power_up
  - drivers/soc/renesas/rmobile-sysc.c:rmobile_pd_power_down
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939ea4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-pmu.c:exynos_sys_powerdown_conf
```
```
In drivers/soc/samsung/pm_domains.c (c093a1ec)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c1591d18)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
```
```
In drivers/soc/tegra/flowctrl.c (c093ab2c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_update
```
```
In drivers/soc/tegra/pmc.c (c1593098)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_type
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_wake
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_wake
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_set_wake
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
```
```
In drivers/virtio/virtio_mmio.c (c0944c4c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_notify
  - drivers/virtio/virtio_mmio.c:vm_reset
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
```
```
In drivers/virtio/virtio_pci_modern.c (c0945574)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946cdc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/regulator/ti-abb-regulator.c (c0956228)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_clear_all_txdone
```
```
In drivers/reset/reset-meson.c (c0959d88)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_deassert
  - drivers/reset/reset-meson.c:meson_reset_assert
  - drivers/reset/reset-meson.c:meson_reset_reset
```
```
In drivers/reset/reset-qcom-aoss.c (c0959e4c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_deassert
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_assert
```
```
In drivers/reset/reset-simple.c (c095a054)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/serial/8250/8250_port.c (c0984f00)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_out
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c0989cb0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_pci.c (c098ba40)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (c098ced8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098e010)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/amba-pl011.c (c09905ac)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/amba-pl011.c:pl011_putc
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_putc
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_putchar
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
  - drivers/tty/serial/amba-pl011.c:pl011_put_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_get_poll_char
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_set_mctrl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_tx_char
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_rx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_start_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_stop_tx
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_trigger_dma
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (c09960b4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_early_putchar
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_putchar
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_poll_put_char
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_stop_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
  - drivers/tty/serial/imx.c:imx_uart_start_rx
```
```
In drivers/tty/serial/meson_uart.c (c09993ac)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_serial_early_console_setup
  - drivers/tty/serial/meson_uart.c:meson_serial_console_setup
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/meson_uart.c:meson_uart_stop_rx
```
```
In drivers/tty/serial/msm_serial.c (c099c0b8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
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
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_shutdown
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_break_ctl
  - drivers/tty/serial/msm_serial.c:msm_break_ctl
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_set_mctrl
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
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
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_enable_ms
  - drivers/tty/serial/msm_serial.c:msm_stop_rx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
  - drivers/tty/serial/msm_serial.c:msm_serial_set_mnd_regs
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1f0c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_resume
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_rx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_start_tx
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_stop_tx
```
```
In drivers/tty/serial/owl-uart.c (c09a2828)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_tx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_stop_rx
  - drivers/tty/serial/owl-uart.c:owl_uart_set_mctrl
```
```
In drivers/tty/serial/rda-uart.c (c09a36dc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
  - drivers/tty/serial/rda-uart.c:rda_uart_config_port
  - drivers/tty/serial/rda-uart.c:rda_uart_config_port
  - drivers/tty/serial/rda-uart.c:rda_uart_shutdown
  - drivers/tty/serial/rda-uart.c:rda_uart_startup
  - drivers/tty/serial/rda-uart.c:rda_uart_startup
  - drivers/tty/serial/rda-uart.c:rda_uart_startup
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_interrupt
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_rx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_rx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_tx
  - drivers/tty/serial/rda-uart.c:rda_uart_stop_tx
  - drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl
  - drivers/tty/serial/rda-uart.c:rda_uart_set_mctrl
```
```
In drivers/char/tpm/tpm_tis.c (c09baf8c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c23b4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_resume_noirq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_remove
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_detach_device
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_utlb_enable
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_utlb_enable
```
```
In drivers/iommu/omap-iommu.c (c09c3174)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_suspend
  - drivers/iommu/omap-iommu.c:iommu_fault_handler
  - drivers/iommu/omap-iommu.c:iommu_fault_handler
  - drivers/iommu/omap-iommu.c:flush_iotlb_all
  - drivers/iommu/omap-iommu.c:flush_iotlb_all
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/omap-iommu.c:omap_iommu_restore_ctx
```
```
In drivers/iommu/rockchip-iommu.c (c09c5e90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_command
```
```
In drivers/iommu/tegra-gart.c (c09c7654)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
  - drivers/iommu/tegra-gart.c:tegra_gart_resume
  - drivers/iommu/tegra-gart.c:tegra_gart_resume
  - drivers/iommu/tegra-gart.c:tegra_gart_resume
  - drivers/iommu/tegra-gart.c:tegra_gart_suspend
  - drivers/iommu/tegra-gart.c:tegra_gart_suspend
  - drivers/iommu/tegra-gart.c:gart_iommu_iova_to_phys
  - drivers/iommu/tegra-gart.c:gart_iommu_unmap
  - drivers/iommu/tegra-gart.c:gart_iommu_unmap
  - drivers/iommu/tegra-gart.c:gart_iommu_unmap
  - drivers/iommu/tegra-gart.c:gart_iommu_map
  - drivers/iommu/tegra-gart.c:gart_iommu_map
  - drivers/iommu/tegra-gart.c:gart_iommu_map
```
```
In drivers/iommu/tegra-smmu.c (c09c8bfc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09caff0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:sysmmu_tlb_invalidate_flpdcache
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable
  - drivers/iommu/exynos-iommu.c:__sysmmu_disable
  - drivers/iommu/exynos-iommu.c:__sysmmu_disable
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/iommu/qcom_iommu.c (c09cbc9c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_inv_range_nosync
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_inv_context
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/base/regmap/regmap-mmio.c (c0a01c68)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a4c4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/mfd/sm501.c (c0a0d484)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_plat_resume
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/sm501.c:sm501_init_regs
  - drivers/mfd/sm501.c:sm501_init_regs
  - drivers/mfd/sm501.c:sm501_init_regs
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_output
  - drivers/mfd/sm501.c:sm501_gpio_input
  - drivers/mfd/sm501.c:sm501_gpio_set
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
  - drivers/mfd/sm501.c:sm501_unit_power
  - drivers/mfd/sm501.c:sm501_modify_reg
  - drivers/mfd/sm501.c:sm501_misc_control
```
```
In drivers/mfd/omap-usb-host.c (c0a35024)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a358f4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
```
```
In drivers/mfd/vexpress-sysreg.c (c0a38e2c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_flags_set
  - drivers/mfd/vexpress-sysreg.c:vexpress_flags_set
```
```
In drivers/ata/libata-sff.c (c0a7ebb4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_setup
```
```
In drivers/ata/libahci.c (c0a87480)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_stop
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_freeze
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_handle_port_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_reset_em
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_reset_controller
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_stop_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_scr_write
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_store_em_buffer
```
```
In drivers/ata/libahci_platform.c (c0a87eac)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_suspend_host
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
  - drivers/ata/libahci_platform.c:ahci_platform_shutdown
```
```
In drivers/ata/sata_highbank.c (c0a88b90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_suspend
  - drivers/ata/sata_highbank.c:__combo_phy_reg_write
  - drivers/ata/sata_highbank.c:__combo_phy_reg_write
  - drivers/ata/sata_highbank.c:__combo_phy_reg_read
```
```
In drivers/ata/ahci_imx.c (c0a8ab9c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
```
```
In drivers/mtd/maps/map_funcs.c (c0a996d8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_write
```
```
In drivers/mtd/nand/raw/omap2.c (c0aa9960)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc_bch
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc_bch
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc_bch
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc_bch
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc
  - drivers/mtd/nand/raw/omap2.c:omap_enable_hwecc
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_reset
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_reset
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_enable
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_enable
  - drivers/mtd/nand/raw/omap2.c:omap_prefetch_enable
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aacd40)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_isr
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_decode_bch_error_page
  - drivers/mtd/nand/raw/omap_elm.c:elm_config
```
```
In drivers/spi/spi-fsl-spi.c (c0ab5430)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7ec4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
  - drivers/spi/spi-omap2-mcspi.c:omap_mcspi_runtime_resume
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
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup_transfer
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
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accb48)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_coalesce
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0ace5f8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf2c8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_write32
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_write32
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfa90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_resume
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0fc0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_unregister
  - drivers/net/ethernet/ti/cpts.c:cpts_unregister
  - drivers/net/ethernet/ti/cpts.c:cpts_register
  - drivers/net/ethernet/ti/cpts.c:cpts_register
  - drivers/net/ethernet/ti/cpts.c:cpts_systim_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3da4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_poll_controller
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_poll_controller
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_poll_controller
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_poll_controller
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_fifo_rlimit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fifo_shp_on
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_mq_poll
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad8908)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_int_ctrl
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_process
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_process
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_eoi
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_stop
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_start
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_set_factors
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_on
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_on
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_on
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_set_chan_shaper
  - drivers/net/ethernet/ti/davinci_cpdma.c:_cpdma_control_set
```
```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad99e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_control_set
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_vlan
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_vlan
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_write
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_write
```
```
In drivers/net/ethernet/ti/cpsw_sl.c (c0ada1f8)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adaa08)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce
```
```
In drivers/auxdisplay/arm-charlcd.c (c0ae8894)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/auxdisplay/arm-charlcd.c:charlcd_4bit_command
  - drivers/auxdisplay/arm-charlcd.c:charlcd_4bit_command
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c1a4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/phy/phy-ulpi-viewport.c (c0b0d26c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
```
```
In drivers/usb/dwc2/core.c (c0b0f028)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c0b10474)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
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
```
```
In drivers/usb/dwc2/hcd.c (c0b1a8dc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
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
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1d608)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1f078)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b201c8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (c0b22338)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (c0b29eb0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
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
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_disable_PSE
  - drivers/usb/host/ehci-hcd.c:ehci_disable_ASE
  - drivers/usb/host/ehci-hcd.c:ehci_set_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
```
In drivers/usb/host/ehci-pci.c (c0b2f79c)
Location: arch/arm/include/asm/io.h:93
Inline: True
```
```
In drivers/usb/host/ehci-orion.c (c0b30050)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_reset
```
```
In drivers/usb/host/ehci-exynos.c (c0b308c8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_resume
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In drivers/usb/host/ohci-hcd.c (c0b36b48)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
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
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (c0b3f540)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_generic_reset_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/usb/host/xhci.c (c0b476e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
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
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
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
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_quiesce
```
```
In drivers/usb/host/xhci-mem.c (c0b4e714)
Location: arch/arm/include/asm/io.h:93
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
```
```
In drivers/usb/host/xhci-ring.c (c0b4f520)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:giveback_first_trb
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
```
```
In drivers/usb/host/xhci-hub.c (c0b59d24)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_link_state
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e324)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/host/xhci-debugfs.c (c0b62004)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (c0b62944)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/usb/musb/musb_core.c (c0b63fb8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_writel
```
```
In drivers/rtc/rtc-mv.c (c15a05a0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_interrupt
  - drivers/rtc/rtc-mv.c:mv_rtc_alarm_irq_enable
  - drivers/rtc/rtc-mv.c:mv_rtc_alarm_irq_enable
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
```
```
In drivers/rtc/rtc-omap.c (c0b8c7d4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_scratch_write
  - drivers/rtc/rtc-omap.c:rtc_pinconf_set
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-omap.c:am3352_rtc_lock
  - drivers/rtc/rtc-omap.c:am3352_rtc_lock
  - drivers/rtc/rtc-omap.c:am3352_rtc_unlock
  - drivers/rtc/rtc-omap.c:am3352_rtc_unlock
```
```
In drivers/rtc/rtc-pl031.c (c0b8db78)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-pl031.c:pl031_set_alarm
  - drivers/rtc/rtc-pl031.c:pl031_set_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_set_alarm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_set_alarm
  - drivers/rtc/rtc-pl031.c:pl031_stv2_set_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_set_time
  - drivers/rtc/rtc-pl031.c:pl031_alarm_irq_enable
  - drivers/rtc/rtc-pl031.c:pl031_alarm_irq_enable
  - drivers/rtc/rtc-pl031.c:pl031_alarm_irq_enable
```
```
In drivers/rtc/rtc-s3c.c (c0b8df6c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_restore_tick_cnt
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2443_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2443_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2416_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2416_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2416_rtc_setfreq
  - drivers/rtc/rtc-s3c.c:s3c2410_rtc_setfreq
```
```
In drivers/i2c/busses/i2c-designware-common.c (c0b989ac)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99b54)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:mscc_twi_set_sda_hold_time
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9de90)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
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
```
```
In drivers/power/avs/smartreflex.c (c0ba9b88)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/power/avs/smartreflex.c:sr_enable
  - drivers/power/avs/smartreflex.c:sr_enable
  - drivers/power/avs/smartreflex.c:sr_configure_minmax
  - drivers/power/avs/smartreflex.c:sr_configure_minmax
  - drivers/power/avs/smartreflex.c:sr_configure_minmax
  - drivers/power/avs/smartreflex.c:sr_configure_minmax
  - drivers/power/avs/smartreflex.c:sr_configure_minmax
  - drivers/power/avs/smartreflex.c:sr_disable_errgen
  - drivers/power/avs/smartreflex.c:sr_disable_errgen
  - drivers/power/avs/smartreflex.c:sr_configure_errgen
  - drivers/power/avs/smartreflex.c:sr_configure_errgen
  - drivers/power/avs/smartreflex.c:sr_configure_errgen
  - drivers/power/avs/smartreflex.c:sr_interrupt
  - drivers/power/avs/smartreflex.c:sr_interrupt
```
```
In drivers/power/reset/brcm-kona-reset.c (c0baa174)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/power/reset/brcm-kona-reset.c:kona_reset_handler
  - drivers/power/reset/brcm-kona-reset.c:kona_reset_handler
```
```
In drivers/power/reset/hisi-reboot.c (c0baa778)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/power/reset/hisi-reboot.c:hisi_restart_handler
```
```
In drivers/power/reset/msm-poweroff.c (c0baa8b8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/power/reset/msm-poweroff.c:deassert_pshold
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe250)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_clear_irqs
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_initialize
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp
```
```
In drivers/watchdog/npcm_wdt.c (c0bc24cc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_restart
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_stop
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_start
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_ping
```
```
In drivers/watchdog/aspeed_wdt.c (c0bc2c94)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:access_cs0_store
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_set_timeout
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_set_timeout
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_ping
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_stop
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_enable
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_enable
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_enable
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_enable
```
```
In drivers/edac/armada_xp_edac.c (c0bf2638)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/edac/armada_xp_edac.c:aurora_l2_probe
  - drivers/edac/armada_xp_edac.c:aurora_l2_probe
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:aurora_l2_check
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
  - drivers/edac/armada_xp_edac.c:axp_mc_check
```
```
In drivers/mmc/host/mmci.c (c0c20090)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_set_mask1
  - drivers/mmc/host/mmci.c:mmci_set_mask1
  - drivers/mmc/host/mmci.c:mmci_dma_start
  - drivers/mmc/host/mmci.c:mmci_write_datactrlreg
```
```
In drivers/mmc/host/mmci_qcom_dml.c (c0c2136c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_setup
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
  - drivers/mmc/host/mmci_qcom_dml.c:qcom_dma_start
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c21604)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_finalize
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start
```
```
In drivers/mmc/host/sdhci.c (c0c2544c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_runtime_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_runtime_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_end_tuning
  - drivers/mmc/host/sdhci.c:sdhci_end_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_tuning
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_set_sdma_addr
  - drivers/mmc/host/sdhci.c:sdhci_set_default_irqs
  - drivers/mmc/host/sdhci.c:sdhci_set_default_irqs
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a5a8)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
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
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_request
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_dma_transfer
  - drivers/mmc/host/omap_hsmmc.c:set_data_timeout
  - drivers/mmc/host/omap_hsmmc.c:set_sd_bus_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_command
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_command
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_command
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_command
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_command
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_start_command
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_bus_width
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_irq
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_irq
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f328)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_timeout
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_reset
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_reset
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
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
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
```
```
In drivers/mmc/host/cqhci.c (c0c31648)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_off
  - drivers/mmc/host/cqhci.c:cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_disable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:cqhci_set_irqs
  - drivers/mmc/host/cqhci.c:cqhci_set_irqs
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37968)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39864)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c441ac)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_write32
```
```
In drivers/clocksource/renesas-ostm.c (c15aa950)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/renesas-ostm.c:ostm_set_periodic
  - drivers/clocksource/renesas-ostm.c:ostm_clock_event_next
```
```
In drivers/clocksource/sh_tmu.c (c0c46360)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/clocksource/em_sti.c (c0c46d98)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_stop
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47220)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_write_status
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_enable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_enable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:omap_timer_restore_context
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_write_reg
```
```
In drivers/clocksource/dw_apb_timer.c (c0c48f40)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_start
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_register
  - drivers/clocksource/dw_apb_timer.c:apbt_next_event
  - drivers/clocksource/dw_apb_timer.c:apbt_next_event
  - drivers/clocksource/dw_apb_timer.c:apbt_next_event
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_shutdown
  - drivers/clocksource/dw_apb_timer.c:apbt_enable_int
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_pause
```
```
In drivers/clocksource/timer-rockchip.c (c15ab2a8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_interrupt
  - drivers/clocksource/timer-rockchip.c:rk_timer_interrupt
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_periodic
  - drivers/clocksource/timer-rockchip.c:rk_timer_shutdown
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
  - drivers/clocksource/timer-rockchip.c:rk_timer_set_next_event
```
```
In drivers/clocksource/timer-armada-370-xp.c (c15ab420)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_resume
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_resume
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_resume
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_resume
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_starting_cpu
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_interrupt
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_set_periodic
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_set_periodic
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_set_periodic
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_shutdown
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_shutdown
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_next_event
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_next_event
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_clkevt_next_event
```
```
In drivers/clocksource/timer-orion.c (c15ab85c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/timer-orion.c:orion_clkevt_set_periodic
  - drivers/clocksource/timer-orion.c:orion_clkevt_set_periodic
  - drivers/clocksource/timer-orion.c:orion_clkevt_next_event
```
```
In drivers/clocksource/timer-meson6.c (c15ab9fc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event
  - drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event
  - drivers/clocksource/timer-meson6.c:meson6_clkevt_next_event
  - drivers/clocksource/timer-meson6.c:meson6_set_periodic
  - drivers/clocksource/timer-meson6.c:meson6_set_periodic
  - drivers/clocksource/timer-meson6.c:meson6_set_periodic
  - drivers/clocksource/timer-meson6.c:meson6_set_oneshot
  - drivers/clocksource/timer-meson6.c:meson6_set_oneshot
  - drivers/clocksource/timer-meson6.c:meson6_shutdown
```
```
In drivers/clocksource/timer-tegra.c (c15abc40)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
  - drivers/clocksource/timer-tegra.c:tegra_timer_resume
  - drivers/clocksource/timer-tegra.c:tegra_timer_suspend
  - drivers/clocksource/timer-tegra.c:tegra_timer_isr
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_periodic
  - drivers/clocksource/timer-tegra.c:tegra_timer_shutdown
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_next_event
```
```
In drivers/clocksource/exynos_mct.c (c0c49cf4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:exynos4_mct_write
  - drivers/clocksource/exynos_mct.c:exynos4_mct_write
```
```
In drivers/clocksource/timer-qcom.c (c15ac544)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/timer-qcom.c:msm_timer_shutdown
  - drivers/clocksource/timer-qcom.c:msm_timer_set_next_event
  - drivers/clocksource/timer-qcom.c:msm_timer_set_next_event
  - drivers/clocksource/timer-qcom.c:msm_timer_set_next_event
  - drivers/clocksource/timer-qcom.c:msm_timer_set_next_event
  - drivers/clocksource/timer-qcom.c:msm_timer_interrupt
```
```
In drivers/clocksource/timer-mediatek.c (c15ac798)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_interrupt
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_handler
```
```
In drivers/clocksource/timer-owl.c (c15aca6c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer1_interrupt
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_next_event
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_oneshot
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_oneshot
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_oneshot
  - drivers/clocksource/timer-owl.c:owl_timer_set_state_shutdown
```
```
In drivers/clocksource/timer-milbeaut.c (c15acb70)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event
  - drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event
  - drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_shutdown
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_oneshot
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_oneshot
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_interrupt
```
```
In drivers/clocksource/timer-npcm7xx.c (c15acc38)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer0_interrupt
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_oneshot
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_shutdown
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_resume
```
```
In drivers/clocksource/timer-rda.c (c0c4af5c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-rda.c:rda_ostimer_interrupt
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_next_event
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_next_event
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_next_event
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_shutdown
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_shutdown
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad548)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_set_next_event_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_handler_phys_mem
```
```
In drivers/clocksource/arm_global_timer.c (c15ad9f0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/arm_global_timer.c:gt_clockevent_shutdown
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
  - drivers/clocksource/arm_global_timer.c:gt_compare_set
```
```
In drivers/clocksource/timer-sp804.c (c15ae028)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-sp804.c:integrator_cp_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/clocksource/timer-sp804.c:sp804_of_init
  - drivers/clocksource/timer-sp804.c:__sp804_clockevents_init
  - drivers/clocksource/timer-sp804.c:sp804_set_next_event
  - drivers/clocksource/timer-sp804.c:sp804_set_next_event
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_shutdown
  - drivers/clocksource/timer-sp804.c:sp804_timer_interrupt
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-sp804.c:sp804_timer_disable
```
```
In drivers/clocksource/timer-imx-gpt.c (c15ae21c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-gpt.c:imx6dl_gpt_setup_tctl
  - drivers/clocksource/timer-imx-gpt.c:imx6dl_gpt_setup_tctl
  - drivers/clocksource/timer-imx-gpt.c:imx31_gpt_setup_tctl
  - drivers/clocksource/timer-imx-gpt.c:imx1_gpt_setup_tctl
  - drivers/clocksource/timer-imx-gpt.c:mxc_set_oneshot
  - drivers/clocksource/timer-imx-gpt.c:mxc_shutdown
  - drivers/clocksource/timer-imx-gpt.c:v2_set_next_event
  - drivers/clocksource/timer-imx-gpt.c:mx1_2_set_next_event
  - drivers/clocksource/timer-imx-gpt.c:imx31_gpt_irq_acknowledge
  - drivers/clocksource/timer-imx-gpt.c:imx21_gpt_irq_acknowledge
  - drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_acknowledge
  - drivers/clocksource/timer-imx-gpt.c:imx31_gpt_irq_enable
  - drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_enable
  - drivers/clocksource/timer-imx-gpt.c:imx31_gpt_irq_disable
  - drivers/clocksource/timer-imx-gpt.c:imx1_gpt_irq_disable
```
```
In drivers/clocksource/timer-imx-tpm.c (c15ae6a4)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_interrupt
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_state_shutdown
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_state_oneshot
  - drivers/clocksource/timer-imx-tpm.c:tpm_set_next_event
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5cd8c)
Location: arch/arm/include/asm/io.h:93
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
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_in_transfer
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
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_out_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep0_in_transfer
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_dma_abort
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_dma_abort
```
```
In drivers/mailbox/pl320-ipc.c (c0c603a0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c605e0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_irq
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_shutdown
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_startup
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_send_data
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_send_data
```
```
In drivers/mailbox/tegra-hsp.c (c0c61778)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_shutdown
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_shutdown
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_shutdown
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_startup
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_startup
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_startup
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_send_data
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_send_data
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_shutdown
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_startup
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_send_data
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_irq
```
```
In drivers/memory/omap-gpmc.c (c0c71854)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_cs_program_settings
  - drivers/memory/omap-gpmc.c:gpmc_handle_irq
  - drivers/memory/omap-gpmc.c:gpmc_irq_set_type
  - drivers/memory/omap-gpmc.c:gpmc_irq_set_type
  - drivers/memory/omap-gpmc.c:gpmc_irq_ack
  - drivers/memory/omap-gpmc.c:gpmc_irq_enable
  - drivers/memory/omap-gpmc.c:gpmc_irq_disable
  - drivers/memory/omap-gpmc.c:gpmc_cs_free
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
```
```
In drivers/memory/mvebu-devbus.c (c0c72838)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
```
```
In drivers/memory/mtk-smi.c (c0c7325c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen1
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_mt8173
  - drivers/memory/mtk-smi.c:mtk_smi_larb_config_port_gen2_general
```
```
In drivers/memory/samsung/exynos-srom.c (c0c732fc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_resume
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
```
In drivers/memory/tegra/mc.c (c0c74038)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_write_emem_configuration
  - drivers/memory/tegra/mc.c:tegra_mc_unblock_dma_common
  - drivers/memory/tegra/mc.c:tegra_mc_block_dma_common
```
```
In drivers/memory/tegra/tegra20.c (c0c747fc)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20.c:tegra20_mc_unblock_dma
  - drivers/memory/tegra/tegra20.c:tegra20_mc_block_dma
  - drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_deassert
  - drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_assert
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74d2c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify
  - drivers/memory/tegra/tegra20-emc.c:emc_prepare_timing_change
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_isr
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c765b8)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_complete_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_prepare_timing_change
  - drivers/memory/tegra/tegra124-emc.c:emc_ccfifo_writel
  - drivers/memory/tegra/tegra124-emc.c:emc_ccfifo_writel
```
```
In drivers/perf/arm-cci.c (c0c7afb0)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_stop
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:pmu_handle_irq
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In drivers/perf/arm-ccn.c (c0c7be7c)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_remove
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_overflow_handler
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_disable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_enable
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
```
```
In sound/soc/fsl/imx-audmux.c (c0cc1b94)
Location: arch/arm/include/asm/io.h:93
Inline: True
Inline callers:
  - sound/soc/fsl/imx-audmux.c:imx_audmux_resume
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v1_configure_port
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
In lib/iomap_copy.c (c0000000007e7430)
Location: arch/powerpc/include/asm/io.h:322
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/gpio/gpio-xilinx.c (c00000000084e190)
Location: arch/powerpc/include/asm/io.h:322
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
```
```
In drivers/video/fbdev/core/cfbimgblt.c (c0000000008be750)
Location: arch/powerpc/include/asm/io.h:322
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092c62c)
Location: arch/powerpc/include/asm/io.h:322
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
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
In arch/riscv/mm/sifive_l2_cache.c (ffffffe0000ba40c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - arch/riscv/mm/sifive_l2_cache.c:l2_write
```
```
In kernel/irq/generic-chip.c (ffffffe000118cc2)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In lib/iomap_copy.c (ffffffe00046b35e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/irqchip/irq-al-fic.c (ffffffe00002a9a2)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_retrigger
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002ad3e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_eoi
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_mask
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_mask
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e96e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fdfc)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writel
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004adf80)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/gpio/gpio-mmio.c:bgpio_write32
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004aeab0)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_unmask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_mask_irq
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_ack_irq
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b2e92)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_apply
  - drivers/pwm/pwm-sifive.c:pwm_sifive_update_clock
```
```
In drivers/pci/access.c (ffffffe0004b3d80)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffe0004cc33e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dcf06)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
```
In drivers/pci/msi.c (ffffffe0004dee92)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msix_desc_mask_irq
```
```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e401e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e4798)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e5504)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e654a)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6e52)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e76cc)
Location: arch/riscv/include/asm/io.h:45
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea02e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
```
In drivers/video/fbdev/imsttfb.c (ffffffe000506780)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_copyarea
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_fillrect
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_pan_display
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
```
```
In drivers/clk/clk-divider.c (ffffffe00051180e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffffffe000512ace)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffe000512e68)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffffffe000513208)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe000513f8a)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
```
```
In drivers/clk/clk-hsdk-pll.c (ffffffe0005151bc)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/clk/sifive/fu540-prci.c (ffffffe00051596a)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_wrpll_set_rate
  - drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_corepll
  - drivers/clk/sifive/fu540-prci.c:__prci_coreclksel_use_hfclk
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d230)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_notify
  - drivers/virtio/virtio_mmio.c:vm_reset
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_set
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
  - drivers/virtio/virtio_mmio.c:vm_get_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d90c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_iowrite64_twopart
  - drivers/virtio/virtio_pci_modern.c:vp_iowrite64_twopart
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f50c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551658)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_out
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555a96)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557952)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe00055992c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sifive.c (ffffffe00055dbd2)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/tty/serial/sifive.c:sifive_serial_console_write
  - drivers/tty/serial/sifive.c:sifive_serial_console_write
  - drivers/tty/serial/sifive.c:sifive_serial_console_putchar
  - drivers/tty/serial/sifive.c:early_sifive_serial_putc
  - drivers/tty/serial/sifive.c:sifive_serial_set_termios
  - drivers/tty/serial/sifive.c:sifive_serial_set_termios
  - drivers/tty/serial/sifive.c:sifive_serial_set_termios
  - drivers/tty/serial/sifive.c:sifive_serial_shutdown
  - drivers/tty/serial/sifive.c:sifive_serial_shutdown
  - drivers/tty/serial/sifive.c:sifive_serial_startup
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/tty/serial/sifive.c:sifive_serial_start_tx
  - drivers/tty/serial/sifive.c:sifive_serial_stop_rx
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe0005739e4)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059c0c0)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le
```
```
In drivers/ata/libata-sff.c (ffffffe00060c53c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061be74)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c23e)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_remove
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_set_cs
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
```
```
In drivers/usb/dwc2/core.c (ffffffe0006578ea)
Location: arch/riscv/include/asm/io.h:45
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
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe000659562)
Location: arch/riscv/include/asm/io.h:45
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000665000)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
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
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000668004)
Location: arch/riscv/include/asm/io.h:45
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe0006699ce)
Location: arch/riscv/include/asm/io.h:45
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066aac6)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066c926)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000677384)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:end_iaa_cycle
  - drivers/usb/host/ehci-hcd.c:ehci_port_power
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
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_disable_PSE
  - drivers/usb/host/ehci-hcd.c:ehci_disable_ASE
  - drivers/usb/host/ehci-hcd.c:ehci_set_command_bit
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
```
In drivers/usb/host/ehci-pci.c (ffffffe00067932c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067ff38)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
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
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:td_submit_urb
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:start_ed_unlink
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:ed_schedule
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
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
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000680c20)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
```
In drivers/usb/host/xhci.c (ffffffe00068bda0)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
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
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_quiesce
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692420)
Location: arch/riscv/include/asm/io.h:45
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
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006991da)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
  - drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069c5fc)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
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
  - drivers/usb/host/xhci-hub.c:xhci_set_link_state
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f8bc)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a286a)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a3906)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006be18c)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006beffe)
Location: arch/riscv/include/asm/io.h:45
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:mscc_twi_set_sda_hold_time
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
