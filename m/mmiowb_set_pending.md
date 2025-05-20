# Function: <code>mmiowb_set_pending</code>

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
In arch/powerpc/kernel/rtas_pci.c (c0000000000401f8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb
```
```
In arch/powerpc/kernel/legacy_serial.c (c000000000068680)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:tsi_serial_out
```
```
In arch/powerpc/kernel/udbg_16550.c (c000000000068a24)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_out_mmio
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_out_pio
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006dab0)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
```
```
In arch/powerpc/sysdev/mpic.c (c0000000000b4908)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
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
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_end_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_end_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_end_irq
  - arch/powerpc/sysdev/mpic.c:mpic_end_irq
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
```
```
In arch/powerpc/sysdev/fsl_lbc.c (c0000000000b8984)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_irq
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_irq
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_irq
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_upm_run_pattern
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_upm_run_pattern
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_upm_run_pattern
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_upm_run_pattern
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b9c28)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c0000000000bac7c)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_ipi_action
  - arch/powerpc/sysdev/xics/icp-native.c:xics_wake_cpu
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_flush_interrupt
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_flush_interrupt
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_cause_ipi
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_get_irq
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_flush_ipi
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_teardown_cpu
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_eoi
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_set_cpu_priority
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bef14)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_teardown_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_smp_disable_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_smp_disable_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_setup_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_cause_ipi
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
```
```
In arch/powerpc/sysdev/xive/native.c (c0000000000bfee0)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_setup_cpu
  - arch/powerpc/sysdev/xive/native.c:xive_native_setup_cpu
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000dc3ec)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_set_inbB
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_set_inbA
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_set_outb
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e2a84)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
  - arch/powerpc/platforms/powernv/vas-window.c:reset_window_regs
```
```
In kernel/irq/generic-chip.c (c0000000001dd270)
Location: include/asm-generic/mmiowb.h:35
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
In lib/iomap.c (c0000000007e5264)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/irqchip/irq-al-fic.c (c0000000013a0d04)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_retrigger
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f104)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pinctrl/pinctrl-single.c (c000000000832640)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writel
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/gpio/gpio-mmio.c (c000000000847d20)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
  - drivers/gpio/gpio-mmio.c:bgpio_write32
  - drivers/gpio/gpio-mmio.c:bgpio_write16
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/gpio/gpio-ftgpio010.c (c0000000008499e0)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pci/access.c (c000000000852af0)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write
  - drivers/pci/access.c:pci_generic_config_write
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c00000000086b638)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/pci/quirks.c (c00000000087e3f4)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/msi.c (c000000000885658)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msix_desc_mask_irq
```
```
In drivers/pci/controller/pcie-cadence.c (c00000000088def8)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pci/controller/pcie-cadence-host.c (c00000000088ea94)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
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
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f73c)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c00000000089131c)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
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
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pcie-xilinx.c (c0000000008920e4)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/video/console/vgacon.c (c00000000089d878)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/video/fbdev/imsttfb.c (c0000000008c0b3c)
Location: include/asm-generic/mmiowb.h:35
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
```
```
In drivers/video/fbdev/asiliantfb.c (c0000000008c1fa4)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
  - drivers/video/fbdev/asiliantfb.c:asiliant_set_timing
```
```
In drivers/video/fbdev/gxt4500.c (c0000000008c3114)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/video/fbdev/offb.c (c0000000008c4218)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/virtio/virtio_mmio.c (c0000000008d2430)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/tty/serial/8250/8250_port.c (c0000000009339c8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c000000000934f94)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_pci.c (c0000000009383d0)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a5c8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (c00000000093c650)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/mem.c (c000000000942aec)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/agp/generic.c (c000000000956f68)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_remove_memory
  - drivers/char/agp/generic.c:agp_generic_insert_memory
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0c38)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/nvdimm/region_devs.c (c000000000a05d44)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/ata/libata-sff.c (c000000000a79bc8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/dwc2/core.c (c000000000afa9c0)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/dwc2/core_intr.c (c000000000afcec4)
Location: include/asm-generic/mmiowb.h:35
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
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0d4a8)
Location: include/asm-generic/mmiowb.h:35
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
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b12050)
Location: include/asm-generic/mmiowb.h:35
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b1436c)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15b68)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/pci-quirks.c (c000000000b18b6c)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1c3c8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
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
In drivers/usb/host/ehci-pci.c (c000000000b2c418)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b35918)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/uhci-hcd.c (c000000000b3e6b8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
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
In drivers/usb/host/xhci.c (c000000000b49878)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-mem.c (c000000000b52a94)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-ring.c (c000000000b5618c)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-hub.c (c000000000b61044)
Location: include/asm-generic/mmiowb.h:35
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
  - drivers/usb/host/xhci-hub.c:xhci_test_and_clear_bit
  - drivers/usb/host/xhci-hub.c:xhci_set_link_state
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66c9c)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-debugfs.c (c000000000b6a614)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (c000000000b6d360)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/input/serio/i8042.c (c000000000b70af8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_kbd_write
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f580)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bb50)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9da20)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:mscc_twi_set_sda_hold_time
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
In arch/riscv/mm/sifive_l2_cache.c (ffffffe0000ba41e)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - arch/riscv/mm/sifive_l2_cache.c:l2_write
```
```
In kernel/irq/generic-chip.c (ffffffe000118cea)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002ac32)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e934)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fe00)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writel
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
  - drivers/pinctrl/pinctrl-single.c:pcs_writeb
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004adfa8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/gpio/gpio-mmio.c:bgpio_write16be
  - drivers/gpio/gpio-mmio.c:bgpio_write64
  - drivers/gpio/gpio-mmio.c:bgpio_write32
  - drivers/gpio/gpio-mmio.c:bgpio_write16
  - drivers/gpio/gpio-mmio.c:bgpio_write8
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004aeabc)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pwm/pwm-sifive.c (ffffffe0004b2ec2)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_apply
  - drivers/pwm/pwm-sifive.c:pwm_sifive_update_clock
```
```
In drivers/pci/access.c (ffffffe0004b3d8a)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write32
  - drivers/pci/access.c:pci_generic_config_write
  - drivers/pci/access.c:pci_generic_config_write
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/quirks.c (ffffffe0004cc342)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/quirks.c:disable_igfx_irq
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_resume_early
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dcf10)
Location: include/asm-generic/mmiowb.h:35
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
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/msi.c (ffffffe0004dee98)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_msix_desc_mask_irq
```
```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e402c)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e47ac)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
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
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e5516)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e655a)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
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
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6e5e)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7692)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea036)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
```
In drivers/video/console/vgacon.c (ffffffe0004f0bce)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/imsttfb.c (ffffffe000506788)
Location: include/asm-generic/mmiowb.h:35
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
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffe00050748a)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_set_par
  - drivers/video/fbdev/asiliantfb.c:mm_write_cr
  - drivers/video/fbdev/asiliantfb.c:mm_write_cr
  - drivers/video/fbdev/asiliantfb.c:mm_write_fr
  - drivers/video/fbdev/asiliantfb.c:mm_write_fr
  - drivers/video/fbdev/asiliantfb.c:mm_write_xr
  - drivers/video/fbdev/asiliantfb.c:mm_write_xr
```
```
In drivers/clk/clk-divider.c (ffffffe000511812)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffffffe000512ad4)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffe000512e6e)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffffffe00051320c)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe000513f8e)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
```
```
In drivers/clk/clk-hsdk-pll.c (ffffffe0005151be)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d23c)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d550)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
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
In drivers/virtio/virtio_pci_common.c (ffffffe00051ea60)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_notify
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f4a4)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe00055167e)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem32_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
  - drivers/tty/serial/8250/8250_port.c:mem_serial_out
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555aa0)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000556a7e)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe0005598bc)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055c174)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_write
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe0005739e8)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059be60)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write8
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c69ca)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/ata/libata-sff.c (ffffffe00060db82)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer32
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_data_xfer
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061be78)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/spi/spi-sifive.c (ffffffe00061c242)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/dwc2/core.c (ffffffe000657916)
Location: include/asm-generic/mmiowb.h:35
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
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
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe00065956a)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/dwc2/hcd.c (ffffffe00066500a)
Location: include/asm-generic/mmiowb.h:35
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
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
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe00066800e)
Location: include/asm-generic/mmiowb.h:35
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe0006699f4)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066aad6)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066d526)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000677386)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/ehci-pci.c (ffffffe00067933a)
Location: include/asm-generic/mmiowb.h:35
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067ff3c)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci.c (ffffffe00068bdac)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-mem.c (ffffffe00069242a)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-ring.c (ffffffe0006991e4)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-hub.c (ffffffe00069c604)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f8c4)
Location: include/asm-generic/mmiowb.h:35
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
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a2878)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a390e)
Location: include/asm-generic/mmiowb.h:35
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pme_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
  - drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf00e)
Location: include/asm-generic/mmiowb.h:35
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
