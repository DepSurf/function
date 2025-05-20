# Function: <code>is_midr_in_range_list</code>

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
In arch/arm64/kernel/irq.c (ffff800011433744)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/setup.c (ffff80001008f730)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In arch/arm64/kernel/insn.c (ffff800010da7768)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800010098bc8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation
  - arch/arm64/kernel/cpu_errata.c:is_affected_midr_range_list
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009a544)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_can_use_dbm
  - arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0
```
```
In arch/arm64/kernel/module.c (ffff8000100a2028)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
```
```
In arch/arm64/kernel/efi.c (ffff8000100a78a0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9230)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a9738)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In arch/arm64/kernel/kaslr.c (ffff800011436d20)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
```
```
In arch/arm64/kernel/sdei.c (ffff8000100abc84)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
```
```
In arch/arm64/mm/ioremap.c (ffff8000100adfe4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In arch/arm64/mm/mmu.c (ffff8000100af698)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:arch_add_memory
  - arch/arm64/mm/mmu.c:mark_rodata_ro
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:set_swapper_pgd
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4f10)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb904)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
```
```
In kernel/fork.c (ffff8000100f32cc)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/groups.c (ffff800010130c2c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/dma/remap.c (ffff800010197730)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_alloc
```
```
In kernel/module.c (ffff8000101c598c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/module.c:__do_sys_init_module
```
```
In kernel/kexec_core.c (ffff8000101c9340)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
```
In kernel/relay.c (ffff80001020bc58)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025edc4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/iomem.c (ffff8000102abd48)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:ioremap_cache
```
```
In mm/percpu.c (ffff8000102e1ea0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffff800010310980)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
```
```
In mm/page_alloc.c (ffff80001145820c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse-vmemmap.c (ffff800010da0d78)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/zsmalloc.c (ffff800010375520)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/early_ioremap.c (ffff8000103768c0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In fs/ext4/super.c (ffff8000104b87f4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_kvzalloc
```
```
In security/keys/big_key.c (ffff800010539bac)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In lib/pci_iomap.c (ffff80001063d740)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffff80001063de18)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470c5c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic.c (ffff80001066ccf4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011471f44)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f810)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473aa4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800011475304)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c154)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
```
```
In drivers/bus/arm-cci.c (ffff80001067ef30)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106e5b38)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_remap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/rom.c (ffff8000106ef7d4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffff8000106fefb8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710ef8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/msi.c (ffff800010714f84)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/pci/ecam.c (ffff800010719a1c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cde4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001073007c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075ae14)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c7f0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075d68c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e374)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760944)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761478)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a9570)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffff8000107adae8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/amba/bus.c (ffff8000107b989c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/clk-qoriq.c (ffff800011483dd0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
```
```
In drivers/dma/amba-pl08x.c (ffff800010802b10)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d888)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010811080)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff8000108116cc)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/renesas/renesas-soc.c (ffff800011490cac)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff800010835508)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
```
In drivers/xen/xlate_mmu.c (ffff8000114923d4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/reset/reset-sunxi.c (ffff800011492978)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
```
In drivers/tty/serial/earlycon.c (ffff800011493c64)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886ef8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fc60)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a18a0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_request_port
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca5bc)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d034)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/mfd/syscon.c (ffff80001094e7ec)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/core.c (ffff80001094ffa8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109edd78)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc408)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50dac)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/edac/altera_edac.c (ffff800010b16e08)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/firmware/efi/earlycon.c (ffff800010d9f738)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b645a8)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b657f4)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67f1c)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
```
In drivers/of/address.c (ffff800010b73ecc)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7ada0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/cputype.h:172
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
