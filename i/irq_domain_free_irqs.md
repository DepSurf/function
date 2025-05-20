# Function: <code>irq_domain_free_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e1680)
Location: kernel/irq/irqdomain.c:1230
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff810e1680-ffffffff810e17eb: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6e00)
Location: kernel/irq/irqdomain.c:1286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff810e6e00-ffffffff810e6f6b: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed7f0)
Location: kernel/irq/irqdomain.c:1312
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff810ed7f0-ffffffff810ed95b: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed1d0)
Location: kernel/irq/irqdomain.c:1456
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff810ed1d0-ffffffff810ed338: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5bf0)
Location: kernel/irq/irqdomain.c:1626
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff810f5bf0-ffffffff810f5d37: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fdfa0)
Location: kernel/irq/irqdomain.c:1510
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff810fdfa0-ffffffff810fe0db: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109770)
Location: kernel/irq/irqdomain.c:1510
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff81109770-ffffffff811098ab: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112d60)
Location: kernel/irq/irqdomain.c:1547
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff81112d60-ffffffff81112e9a: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111eff0)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff8111eff0-ffffffff8111f12a: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b540)
Location: kernel/irq/irqdomain.c:1552
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8112b540-ffffffff8112b670: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127010)
Location: kernel/irq/irqdomain.c:1674
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
```
**Symbols:**

```
ffffffff81127010-ffffffff81127126: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127160)
Location: kernel/irq/irqdomain.c:1641
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81127160-ffffffff8112731b: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811476c0)
Location: kernel/irq/irqdomain.c:1686
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff811476c0-ffffffff81147874: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116bb00)
Location: kernel/irq/irqdomain.c:1690
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff8116bb00-ffffffff8116bcd6: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0cf0)
Location: kernel/irq/irqdomain.c:1758
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff811a0cf0-ffffffff811a0ec9: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2b80)
Location: kernel/irq/irqdomain.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff811b2b80-ffffffff811b2d34: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c29a0)
Location: kernel/irq/irqdomain.c:1736
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
```
**Symbols:**

```
ffffffff811c29a0-ffffffff811c2b54: irq_domain_free_irqs (STB_GLOBAL)
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184b10)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
  - drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs
```
**Symbols:**

```
ffff800010184b10-ffff800010184c74: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3bbc)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
  - drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs
```
**Symbols:**

```
c03d3bbc-c03d3d1c: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:546
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b9ea)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffe00011b9ea-ffffffe00011bb18: irq_domain_free_irqs (STB_GLOBAL)
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811175d0)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff811175d0-ffffffff8111770a: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811082c0)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff811082c0-ffffffff811083fa: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811154c0)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff811154c0-ffffffff811155fa: irq_domain_free_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120af0)
Location: kernel/irq/irqdomain.c:1550
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unmap_irq
  - arch/x86/kernel/apic/msi.c:dmar_free_hwirq
  - arch/x86/kernel/apic/msi.c:native_teardown_msi_irq
  - arch/x86/platform/uv/uv_irq.c:uv_teardown_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_free_irqs
```
**Symbols:**

```
ffffffff81120af0-ffffffff81120c2a: irq_domain_free_irqs (STB_GLOBAL)
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
