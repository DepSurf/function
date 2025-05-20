# Function: <code>irq_domain_create_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0f24)
Location: include/linux/irqdomain.h:274
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e64f4)
Location: include/linux/irqdomain.h:300
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecee4)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
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
In arch/x86/kernel/apic/vector.c (ffffffff820b70a7)
Location: include/linux/irqdomain.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff820b82a2)
Location: include/linux/irqdomain.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
```
```
In kernel/irq/irqdomain.c (ffffffff810ec884)
Location: include/linux/irqdomain.h:342
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff815ca05a)
Location: include/linux/irqdomain.h:342
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff826bd9c4)
Location: include/linux/irqdomain.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810f50f4)
Location: include/linux/irqdomain.h:351
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff81630a2a)
Location: include/linux/irqdomain.h:351
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff826e7791)
Location: include/linux/irqdomain.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff810fd4c4)
Location: include/linux/irqdomain.h:357
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166b4a5)
Location: include/linux/irqdomain.h:357
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff8289e2da)
Location: include/linux/irqdomain.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff81108f74)
Location: include/linux/irqdomain.h:359
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff81689bb5)
Location: include/linux/irqdomain.h:359
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828b616a)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff81112544)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c1195)
Location: include/linux/irqdomain.h:361
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828b962d)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109869d)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8111e7d4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e41f5)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff82cde61c)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109de8d)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81129f14)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179a4a5)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff82fca9da)
Location: include/linux/irqdomain.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099a60)
Location: include/linux/irqdomain.h:376
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811258d4)
Location: include/linux/irqdomain.h:376
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a8ba5)
Location: include/linux/irqdomain.h:376
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff831d5339)
Location: include/linux/irqdomain.h:381
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a26d)
Location: include/linux/irqdomain.h:381
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81125bc4)
Location: include/linux/irqdomain.h:381
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178a945)
Location: include/linux/irqdomain.h:381
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff832b7e6b)
Location: include/linux/irqdomain.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa297)
Location: include/linux/irqdomain.h:378
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81146364)
Location: include/linux/irqdomain.h:378
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd/iommu.c (ffffffff81811c25)
Location: include/linux/irqdomain.h:378
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff83469b36)
Location: include/linux/irqdomain.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfd01)
Location: include/linux/irqdomain.h:392
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8116a626)
Location: include/linux/irqdomain.h:392
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd/iommu.c (ffffffff81952a25)
Location: include/linux/irqdomain.h:392
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff83e8e82a)
Location: include/linux/irqdomain.h:380
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbbf1)
Location: include/linux/irqdomain.h:380
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff836b20ca)
Location: include/linux/irqdomain.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff838e258a)
Location: include/linux/irqdomain.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
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
In kernel/irq/irqdomain.c (ffff8000101840b4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d7cc)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472d88)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (ffff800011473830)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011474348)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
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
In kernel/irq/irqdomain.c (c03d322c)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b540)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
```
```
In drivers/irqchip/irq-gic-v3.c (c154b8c8)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (c154c4d4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154c9c4)
Location: include/linux/irqdomain.h:368
Inline: True
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b180)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
</details>
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
In arch/x86/kernel/apic/vector.c (ffffffff828a7634)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff81116db4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a9cd5)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff8289f731)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff81107aa4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687635)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828ba544)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In kernel/irq/irqdomain.c (ffffffff81114ca4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d7eb5)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff828ba65a)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099b6d)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff811202d4)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f2465)
Location: include/linux/irqdomain.h:368
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
</details>
</li>
</ul>

## Differences
