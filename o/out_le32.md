# Function: <code>out_le32</code>

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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006dac8)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
```
```
In arch/powerpc/sysdev/mpic.c (c0000000000b4978)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_end_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_end_irq
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
```
```
In kernel/irq/generic-chip.c (c0000000001dd268)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
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
In lib/iomap.c (c0000000007e52f0)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
```
```
In drivers/irqchip/irq-al-fic.c (c0000000013a0cfc)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_retrigger
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f0fc)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/pinctrl/pinctrl-single.c (c000000000832638)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writel
```
```
In drivers/gpio/gpio-mmio.c (c000000000847cfc)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write32
```
```
In drivers/gpio/gpio-ftgpio010.c (c0000000008499d8)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/pci/access.c (c000000000852ae8)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c00000000086b690)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
```
```
In drivers/pci/quirks.c (c00000000087e3e8)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/msi.c (c000000000885650)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msix_desc_mask_irq
```
```
In drivers/pci/controller/pcie-cadence.c (c00000000088def0)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/pci/controller/pcie-cadence-host.c (c00000000088ea8c)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f734)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/pci/controller/pci-ftpci100.c (c000000000891310)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/pci/controller/pcie-xilinx.c (c0000000008920d8)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/video/fbdev/imsttfb.c (c0000000008c0b34)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/video/fbdev/gxt4500.c (c0000000008c3108)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/video/fbdev/gxt4500.c:gxt4500_blank
  - drivers/video/fbdev/gxt4500.c:gxt4500_blank
  - drivers/video/fbdev/gxt4500.c:gxt4500_pan_display
  - drivers/video/fbdev/gxt4500.c:gxt4500_setcolreg
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
```
```
In drivers/video/fbdev/offb.c (c0000000008c420c)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_set_par
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_blank
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
  - drivers/video/fbdev/offb.c:offb_setcolreg
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d2424)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
  - drivers/virtio/virtio_mmio.c:vm_notify
  - drivers/virtio/virtio_mmio.c:vm_reset
  - drivers/virtio/virtio_mmio.c:vm_set_status
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
In drivers/tty/serial/8250/8250_port.c (c00000000092c6e0)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_out
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c000000000934f8c)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000938928)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/tty/serial/8250/8250_early.c (c00000000093a52c)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/char/agp/generic.c (c000000000956f60)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_remove_memory
  - drivers/char/agp/generic.c:agp_generic_insert_memory
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0c00)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le
```
```
In drivers/usb/dwc2/core.c (c000000000afa9b8)
Location: arch/powerpc/include/asm/io.h:160
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
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c000000000afceb8)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/dwc2/hcd.c (c000000000b0d49c)
Location: arch/powerpc/include/asm/io.h:160
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
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b12048)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/dwc2/hcd_queue.c (c000000000b14364)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15b60)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/pci-quirks.c (c000000000b195c4)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/ehci-hcd.c (c000000000b24660)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/ehci-pci.c (c000000000b2c404)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b35910)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/uhci-hcd.c (c000000000b378dc)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
```
In drivers/usb/host/xhci.c (c000000000b49870)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/xhci-mem.c (c000000000b52a8c)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/xhci-ring.c (c000000000b56184)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/xhci-hub.c (c000000000b6103c)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/xhci-dbgcap.c (c000000000b66c94)
Location: arch/powerpc/include/asm/io.h:160
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
In drivers/usb/host/xhci-debugfs.c (c000000000b6a60c)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (c000000000b6d358)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bb80)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9da10)
Location: arch/powerpc/include/asm/io.h:160
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:mscc_twi_set_sda_hold_time
```
</details>
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
