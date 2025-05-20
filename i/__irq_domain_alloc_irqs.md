# Function: <code>__irq_domain_alloc_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e1130)
Location: kernel/irq/irqdomain.c:1172
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810e1130-ffffffff810e1453: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6af0)
Location: kernel/irq/irqdomain.c:1227
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810e6af0-ffffffff810e6dfc: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed4e0)
Location: kernel/irq/irqdomain.c:1253
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810ed4e0-ffffffff810ed7ec: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810eceb0)
Location: kernel/irq/irqdomain.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810eceb0-ffffffff810ed1ca: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f58f0)
Location: kernel/irq/irqdomain.c:1398
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810f58f0-ffffffff810f5bed: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fdca0)
Location: kernel/irq/irqdomain.c:1282
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810fdca0-ffffffff810fdf9c: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109470)
Location: kernel/irq/irqdomain.c:1282
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81109470-ffffffff8110976c: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112a70)
Location: kernel/irq/irqdomain.c:1319
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81112a70-ffffffff81112d52: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111ed00)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8111ed00-ffffffff8111efe2: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b260)
Location: kernel/irq/irqdomain.c:1328
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8112b260-ffffffff8112b535: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126cf0)
Location: kernel/irq/irqdomain.c:1441
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
```
**Symbols:**

```
ffffffff81126cf0-ffffffff81127009: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:1408
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81bd3cac-ffffffff81bd3ceb: __irq_domain_alloc_irqs.cold (STB_LOCAL)
ffffffff81126d30-ffffffff8112715c: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:1448
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81cadcbc-ffffffff81cadcfb: __irq_domain_alloc_irqs.cold (STB_LOCAL)
ffffffff81147290-ffffffff811476bd: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:1451
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81e5e1ab-ffffffff81e5e1eb: __irq_domain_alloc_irqs.cold (STB_LOCAL)
ffffffff8116b4e0-ffffffff8116b8fa: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0a10)
Location: kernel/irq/irqdomain.c:1557
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff811a0a10-ffffffff811a0ab9: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b28c0)
Location: kernel/irq/irqdomain.c:1536
Inline: True
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff811b28c0-ffffffff811b296e: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c26b0)
Location: kernel/irq/irqdomain.c:1536
Inline: True
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
```
**Symbols:**

```
ffffffff811c26b0-ffffffff811c275e: __irq_domain_alloc_irqs (STB_GLOBAL)
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
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101847c8)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffff8000101847c8-ffff800010184b10: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3878)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
c03d3878-c03d3bbc: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b73a)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffe00011b73a-ffffffe00011b9ea: __irq_domain_alloc_irqs (STB_GLOBAL)
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
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811172e0)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff811172e0-ffffffff811175c2: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107fd0)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81107fd0-ffffffff811082b2: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811151d0)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff811151d0-ffffffff811154b2: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __irq_domain_alloc_irqs(struct irq_domain *domain, int irq_base, unsigned int nr_irqs, int node, void *arg, bool realloc, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120800)
Location: kernel/irq/irqdomain.c:1321
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81120800-ffffffff81120ae2: __irq_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask *affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask *affinity</code> ➡️ <code>const struct irq_affinity_desc *affinity</code>
</li>
</ul>
</details>
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
