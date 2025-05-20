# Function: <code>arm64_kernel_use_ng_mappings</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/irq.c (ffff800011433714)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/setup.c (ffff800011434050)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:setup_arch
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/insn.c (ffff800010da765c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/module.c (ffff8000100a1f0c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
```
```
In arch/arm64/kernel/efi.c (ffff800011436124)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
Direct callers:
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
  - arch/arm64/kernel/efi.c:efi_create_mapping
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a914c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a965c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In arch/arm64/kernel/kaslr.c (ffff800011436cf0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
```
```
In arch/arm64/kernel/sdei.c (ffff8000100abbd0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
```
```
In arch/arm64/mm/ioremap.c (ffff8000100adfa4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In arch/arm64/mm/mmu.c (ffff8000100af600)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:arch_add_memory
  - arch/arm64/mm/mmu.c:arch_add_memory
  - arch/arm64/mm/mmu.c:vmemmap_populate
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:mark_rodata_ro
  - arch/arm64/mm/mmu.c:mark_rodata_ro
  - arch/arm64/mm/mmu.c:mark_linear_text_alias_ro
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
  - arch/arm64/mm/mmu.c:set_swapper_pgd
  - arch/arm64/mm/mmu.c:set_swapper_pgd
Direct callers:
  - arch/arm64/mm/mmu.c:vmemmap_populate
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:map_entry_trampoline
  - arch/arm64/mm/mmu.c:mark_linear_text_alias_ro
  - arch/arm64/mm/mmu.c:early_pgtable_alloc
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4e80)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb824)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
```
```
In kernel/fork.c (ffff8000100f320c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/groups.c (ffff800010130bbc)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/dma/remap.c (ffff8000101976a0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_alloc
  - kernel/dma/remap.c:arch_dma_alloc
  - kernel/dma/remap.c:dma_atomic_pool_init
Direct callers:
  - kernel/dma/remap.c:dma_atomic_pool_init
```
```
In kernel/module.c (ffff8000101c5924)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/module.c:__do_sys_init_module
```
```
In kernel/kexec_core.c (ffff8000101c9300)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
```
In kernel/relay.c (ffff80001020bae4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025ec48)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/iomem.c (ffff8000102abba4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:ioremap_cache
  - kernel/iomem.c:ioremap_cache
```
```
In mm/percpu.c (ffff8000102e1cf0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffff8000103108e8)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc_node_flags_caller
```
```
In mm/page_alloc.c (ffff8000114581dc)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse-vmemmap.c (ffff800010da0d48)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/zsmalloc.c (ffff800010375428)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/early_ioremap.c (ffff80001145c800)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
  - mm/early_ioremap.c:early_ioremap
Direct callers:
  - mm/early_ioremap.c:early_memremap_ro
  - mm/early_ioremap.c:early_memremap
  - mm/early_ioremap.c:early_ioremap
```
```
In fs/ext4/super.c (ffff8000104b8788)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvmalloc
Direct callers:
  - fs/ext4/super.c:ext4_kvmalloc
```
```
In security/keys/big_key.c (ffff800010539b6c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In lib/pci_iomap.c (ffff80001063d6d0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_range
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffff80001063dd5c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470c2c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic.c (ffff800011471820)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011471f14)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3.c (ffff8000114733f0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_gicc
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_redist
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_gicc
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_redist
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473a74)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000114752d4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c114)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
```
```
In drivers/bus/arm-cci.c (ffff80001067eebc)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106e5a7c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_remap_iospace
  - drivers/pci/pci.c:pci_remap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/rom.c (ffff8000106ef740)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffff8000106feed4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710e54)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/msi.c (ffff800010714f44)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In drivers/pci/ecam.c (ffff8000107199d8)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cd30)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072ff38)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075b000)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c7c0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075d4d0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e368)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107606c0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761224)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a939c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffff8000107adab0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/amba/bus.c (ffff8000107b96c4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/clk-qoriq.c (ffff800011483da0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
```
```
In drivers/dma/amba-pl08x.c (ffff800010802660)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f3fc)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
Direct callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810ebc)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff800010811494)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/renesas/renesas-soc.c (ffff800011490c7c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108353f8)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
```
In drivers/xen/xlate_mmu.c (ffff8000114923a4)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/reset/reset-sunxi.c (ffff800011492948)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
```
In drivers/tty/serial/earlycon.c (ffff800011493c34)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886e80)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fbb0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1820)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_request_port
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: False
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca3c0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/base/firmware_loader/main.c (ffff80001090cf9c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
```
```
In drivers/mfd/syscon.c (ffff80001094e7ac)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/core.c (ffff80001094ff1c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109edcc0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc34c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50d6c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/edac/altera_edac.c (ffff800010b16d60)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/firmware/efi/earlycon.c (ffff800010d9f66c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b642f8)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b655cc)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a938c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq
Direct callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq
```
```
In drivers/of/address.c (ffff800010b73e5c)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
  - drivers/of/address.c:of_iomap
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7aca8)
Location: arch/arm64/include/asm/mmu.h:38
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/mmu.h:38
Inline: False
```
**Symbols:**

```
ffff80001066cce8-ffff80001066cd68: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff80001066f804-ffff80001066f884: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff80001008f724-ffff80001008f7a4: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff8000100a7894-ffff8000100a7914: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff8000100ae2c0-ffff8000100ae328: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff8000101971d8-ffff800010197240: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff8000103768b4-ffff800010376934: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff8000104ad428-ffff8000104ad490: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff80001075ae08-ffff80001075ae88: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff80001075e368-ffff80001075e3e8: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff80001080d87c-ffff80001080d8fc: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
ffff800010b67f10-ffff800010b67f90: arm64_kernel_use_ng_mappings.part.0 (STB_LOCAL)
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
