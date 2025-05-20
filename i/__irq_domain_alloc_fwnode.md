# Function: <code>__irq_domain_alloc_fwnode</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec990)
Location: kernel/irq/irqdomain.c:60
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
ffffffff810ec990-ffffffff810eca64: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5200)
Location: kernel/irq/irqdomain.c:62
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
ffffffff810f5200-ffffffff810f52d6: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd5d0)
Location: kernel/irq/irqdomain.c:64
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
ffffffff810fd5d0-ffffffff810fd6a6: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107e80)
Location: kernel/irq/irqdomain.c:64
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
ffffffff81107e80-ffffffff81107f56: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111370)
Location: kernel/irq/irqdomain.c:64
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
ffffffff81111370-ffffffff81111447: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d5d0)
Location: kernel/irq/irqdomain.c:64
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
ffffffff8111d5d0-ffffffff8111d6a7: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81129f30)
Location: kernel/irq/irqdomain.c:64
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
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
ffffffff81129f30-ffffffff8112a007: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811258f0)
Location: kernel/irq/irqdomain.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_create_irq_domain
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff811258f0-ffffffff811259e8: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125be0)
Location: kernel/irq/irqdomain.c:73
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff81125be0-ffffffff81125cd5: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146380)
Location: kernel/irq/irqdomain.c:73
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:arch_create_remap_msi_irq_domain
  - arch/x86/kernel/apic/msi.c:native_create_pci_msi_domain
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff81146380-ffffffff81146475: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a640)
Location: kernel/irq/irqdomain.c:73
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
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
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff8116a640-ffffffff8116a742: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f1f0)
Location: kernel/irq/irqdomain.c:76
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff8119f1f0-ffffffff8119f2f2: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b10e0)
Location: kernel/irq/irqdomain.c:76
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff811b10e0-ffffffff811b11db: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0e60)
Location: kernel/irq/irqdomain.c:76
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_create_pci_msi_domain
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - arch/x86/pci/xen.c:xen_create_pci_msi_domain
```
**Symbols:**

```
ffffffff811c0e60-ffffffff811c0f8a: __irq_domain_alloc_fwnode (STB_GLOBAL)
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
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101828f8)
Location: kernel/irq/irqdomain.c:64
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3-its.c:gic_acpi_parse_madt_its
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
**Symbols:**

```
ffff8000101828f8-ffff8000101829ec: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d1ccc)
Location: kernel/irq/irqdomain.c:64
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
**Symbols:**

```
c03d1ccc-c03d1db0: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de8c0)
Location: kernel/irq/irqdomain.c:64
Inline: False
```
**Symbols:**

```
c0000000001de8c0-c0000000001dea10: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe000119e5e)
Location: kernel/irq/irqdomain.c:64
Inline: False
```
**Symbols:**

```
ffffffe000119e5e-ffffffe000119f44: __irq_domain_alloc_fwnode (STB_GLOBAL)
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
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115bb0)
Location: kernel/irq/irqdomain.c:64
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
ffffffff81115bb0-ffffffff81115c87: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811068a0)
Location: kernel/irq/irqdomain.c:64
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
ffffffff811068a0-ffffffff81106977: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113aa0)
Location: kernel/irq/irqdomain.c:64
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
ffffffff81113aa0-ffffffff81113b77: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *__irq_domain_alloc_fwnode(unsigned int type, int id, const char *name, phys_addr_t *pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f0c0)
Location: kernel/irq/irqdomain.c:64
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
ffffffff8111f0c0-ffffffff8111f197: __irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t *pa</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
