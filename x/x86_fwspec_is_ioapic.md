# Function: <code>x86_fwspec_is_ioapic</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ff60)
Location: arch/x86/kernel/apic/vector.c:643
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff8106ff60-ffffffff8106ffca: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff81071680-ffffffff810716f3: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070ab0)
Location: arch/x86/kernel/apic/vector.c:651
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff81070ab0-ffffffff81070b1c: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff81072180-ffffffff810721f5: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107c730)
Location: arch/x86/kernel/apic/vector.c:651
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff8107c730-ffffffff8107c79c: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff8107e030-ffffffff8107e0a5: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108bc1b)
Location: arch/x86/kernel/apic/vector.c:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff8108baf0-ffffffff8108bb66: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff8108d640-ffffffff8108d6c9: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a00cb)
Location: arch/x86/kernel/apic/vector.c:647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff8109ff80-ffffffff8109fff6: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff810a1d00-ffffffff810a1d89: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a304b)
Location: arch/x86/kernel/apic/vector.c:647
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff810a2f00-ffffffff810a2f76: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff810a4ce0-ffffffff810a4d69: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_ioapic(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a9f86)
Location: arch/x86/kernel/apic/vector.c:658
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_select
```
**Symbols:**

```
ffffffff810a9e40-ffffffff810a9eb6: x86_fwspec_is_ioapic.part.0 (STB_LOCAL)
ffffffff810abd30-ffffffff810abdb9: x86_fwspec_is_ioapic (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
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
