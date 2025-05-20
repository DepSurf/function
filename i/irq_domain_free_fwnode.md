# Function: <code>irq_domain_free_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0080)
Location: kernel/irq/irqdomain.c:70
Inline: False
```
**Symbols:**

```
ffffffff810e0080-ffffffff810e00bf: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5a40)
Location: kernel/irq/irqdomain.c:68
Inline: False
```
**Symbols:**

```
ffffffff810e5a40-ffffffff810e5a7f: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec3b0)
Location: kernel/irq/irqdomain.c:68
Inline: False
```
**Symbols:**

```
ffffffff810ec3b0-ffffffff810ec3ef: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebdc0)
Location: kernel/irq/irqdomain.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff810ebdc0-ffffffff810ebdee: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4290)
Location: kernel/irq/irqdomain.c:101
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff810f4290-ffffffff810f42c5: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc670)
Location: kernel/irq/irqdomain.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff810fc670-ffffffff810fc6a5: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107e40)
Location: kernel/irq/irqdomain.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff81107e40-ffffffff81107e75: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8111324a-ffffffff8111325d: irq_domain_free_fwnode.cold (STB_LOCAL)
ffffffff81111450-ffffffff8111148a: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d6b0)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8111d6b0-ffffffff8111d6e8: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811298d0)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff811298d0-ffffffff8112990c: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125180)
Location: kernel/irq/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_create_irq_domain
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81125180-ffffffff811251bc: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811254e0)
Location: kernel/irq/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff811254e0-ffffffff8112551c: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81145ba0)
Location: kernel/irq/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81145ba0-ffffffff81145bdc: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81169d20)
Location: kernel/irq/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81169d20-ffffffff81169d67: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119e710)
Location: kernel/irq/irqdomain.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8119e710-ffffffff8119e75e: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b0620)
Location: kernel/irq/irqdomain.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff811b0620-ffffffff811b066e: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c03a0)
Location: kernel/irq/irqdomain.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff811c03a0-ffffffff811c03ee: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101829f0)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_teardown
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3-its.c:gic_acpi_parse_madt_its
  - drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
**Symbols:**

```
ffff8000101829f0-ffff800010182a4c: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d1db0)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
**Symbols:**

```
c03d1db0-c03d1e10: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dd3e0)
Location: kernel/irq/irqdomain.c:104
Inline: False
```
**Symbols:**

```
c0000000001dd3e0-c0000000001dd46c: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe000119f44)
Location: kernel/irq/irqdomain.c:104
Inline: False
```
**Symbols:**

```
ffffffe000119f44-ffffffe000119f94: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115c90)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81115c90-ffffffff81115cc8: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106980)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81106980-ffffffff811069b8: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113b80)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81113b80-ffffffff81113bb8: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_free_fwnode(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f1a0)
Location: kernel/irq/irqdomain.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:arch_init_msi_domain
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8111f1a0-ffffffff8111f1d8: irq_domain_free_fwnode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
