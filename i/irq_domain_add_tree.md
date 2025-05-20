# Function: <code>irq_domain_add_tree</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff81f72666)
Location: include/linux/irqdomain.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff81058e91)
Location: include/linux/irqdomain.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff815324d6)
Location: include/linux/irqdomain.h:259
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff81f9ae89)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff810591e1)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff81586cb6)
Location: include/linux/irqdomain.h:285
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
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
In arch/x86/kernel/apic/vector.c (ffffffff81fd637d)
Location: include/linux/irqdomain.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff8105bf71)
Location: include/linux/irqdomain.h:292
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b42a6)
Location: include/linux/irqdomain.h:292
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
</details>
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-alpine-msi.c (c0813590)
Location: include/linux/irqdomain.h:353
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
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
In arch/powerpc/sysdev/xics/xics-common.c (c00000000135944c)
Location: include/linux/irqdomain.h:353
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_init
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
