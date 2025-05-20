# Function: <code>kaslr_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:76
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/setup.h:76
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:77
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/setup.h:77
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff8143dfc4)
Location: arch/x86/include/asm/setup.h:77
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:77
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/setup.h:77
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff8145af44)
Location: arch/x86/include/asm/setup.h:77
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:76
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/setup.h:76
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff818fcce4)
Location: arch/x86/include/asm/setup.h:76
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (0)
Location: arch/x86/include/asm/setup.h:80
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/setup.h:80
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff81984794)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81033912)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106550d)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff819e0cb5)
Location: arch/x86/include/asm/setup.h:80
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81034c72)
Location: arch/x86/include/asm/setup.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106b17d)
Location: arch/x86/include/asm/setup.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1bc65)
Location: arch/x86/include/asm/setup.h:83
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81036bd0)
Location: arch/x86/include/asm/setup.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ec56)
Location: arch/x86/include/asm/setup.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81a8ba25)
Location: arch/x86/include/asm/setup.h:83
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff810373a1)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070206)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81ac2ce5)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81039250)
Location: arch/x86/include/asm/setup.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff81076a6e)
Location: arch/x86/include/asm/setup.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff815ff375)
Location: arch/x86/include/asm/setup.h:91
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81bd3afe)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff8107709e)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81624345)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81bc5f70)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff81077afe)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81607d35)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81c98e5e)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810852fe)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81676975)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81e48409)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff8109562d)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81791815)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81053952)
Location: arch/x86/include/asm/setup.h:95
Inline: True
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810ab1ed)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff8204f4f5)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81054932)
Location: arch/x86/include/asm/setup.h:95
Inline: True
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810aedad)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff820cdd75)
Location: arch/x86/include/asm/setup.h:95
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff8105bb72)
Location: arch/x86/include/asm/setup.h:93
Inline: True
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810b592d)
Location: arch/x86/include/asm/setup.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff821a8595)
Location: arch/x86/include/asm/setup.h:93
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
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
In arch/arm64/kernel/irq.c (ffff800011433784)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/setup.c (ffff80001008f674)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:dump_kernel_offset
```
```
In arch/arm64/kernel/insn.c (ffff800010da766c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009a198)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0
```
```
In arch/arm64/kernel/module.c (ffff8000100a1f1c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
```
```
In arch/arm64/kernel/efi.c (ffff8000100a78f0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a915c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a966c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In arch/arm64/kernel/kaslr.c (ffff800011436d60)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
```
```
In arch/arm64/kernel/crash_core.c (ffff8000100abb20)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo
```
```
In arch/arm64/kernel/sdei.c (ffff8000100abbe0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
```
```
In arch/arm64/mm/ioremap.c (ffff8000100adfb4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In arch/arm64/mm/mmu.c (ffff8000100af610)
Location: arch/arm64/include/asm/memory.h:192
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
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4e90)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb838)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
```
```
In kernel/fork.c (ffff8000100f321c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/groups.c (ffff800010130bcc)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/dma/remap.c (ffff8000101976b0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_alloc
```
```
In kernel/module.c (ffff8000101c5934)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/module.c:__do_sys_init_module
```
```
In kernel/kexec_core.c (ffff8000101c9310)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
```
```
In kernel/relay.c (ffff80001020baf4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025ec58)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/iomem.c (ffff8000102abbb4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:ioremap_cache
```
```
In mm/percpu.c (ffff8000102e1d00)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffff8000103108f8)
Location: arch/arm64/include/asm/memory.h:192
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
In mm/page_alloc.c (ffff800011458254)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/sparse-vmemmap.c (ffff800010da0db8)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/zsmalloc.c (ffff800010375438)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/early_ioremap.c (ffff800010376910)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In fs/ext4/super.c (ffff8000104b8798)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_kvzalloc
```
```
In security/keys/big_key.c (ffff800010539b7c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In lib/pci_iomap.c (ffff80001063d6e8)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffff80001063dd6c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470c9c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic.c (ffff80001066cd44)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011471f84)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f860)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473ae4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800011475340)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c124)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
```
```
In drivers/bus/arm-cci.c (ffff80001067eecc)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106e5a8c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_remap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/rom.c (ffff8000106ef750)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffff8000106feee4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710e64)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/msi.c (ffff800010714f54)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/pci/ecam.c (ffff8000107199ec)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cd40)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072ff48)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075ae64)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c830)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075d4e0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e3c4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107606d0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761234)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a93ac)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffff8000107adab8)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/amba/bus.c (ffff8000107b96d4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/clk-qoriq.c (ffff800011483e10)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
```
```
In drivers/dma/amba-pl08x.c (ffff800010802674)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d8d8)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810ecc)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff8000108114a4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/renesas/renesas-soc.c (ffff800011490cec)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff800010835408)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
```
In drivers/xen/xlate_mmu.c (ffff800011492414)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/reset/reset-sunxi.c (ffff8000114929b0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
```
In drivers/tty/serial/earlycon.c (ffff800011493ca4)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886e90)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fbc0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1830)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_request_port
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca3d0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/base/firmware_loader/main.c (ffff80001090cfb0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/mfd/syscon.c (ffff80001094e7bc)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/core.c (ffff80001094ff2c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109edcd0)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc35c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50d7c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/edac/altera_edac.c (ffff800010b16d70)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/firmware/efi/earlycon.c (ffff800010d9f67c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64308)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b655dc)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67f6c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
```
```
In drivers/of/address.c (ffff800010b73e6c)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7acb8)
Location: arch/arm64/include/asm/memory.h:192
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/memory.h:192
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81037501)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f1a6)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81a61b35)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81026ee1)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f576)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1eba5)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81037361)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f656)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81acdf25)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81038361)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:dump_kernel_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810718d6)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/lib/kaslr.c (ffffffff81ada435)
Location: arch/x86/include/asm/setup.h:81
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
</ul>

## Differences
