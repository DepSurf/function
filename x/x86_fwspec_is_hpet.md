# Function: <code>x86_fwspec_is_hpet</code>

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
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ffd0)
Location: arch/x86/kernel/apic/vector.c:658
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff8106ffd0-ffffffff8107003a: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff81071700-ffffffff81071773: x86_fwspec_is_hpet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070b20)
Location: arch/x86/kernel/apic/vector.c:666
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff81070b20-ffffffff81070b8c: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff81072200-ffffffff81072275: x86_fwspec_is_hpet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107c7a0)
Location: arch/x86/kernel/apic/vector.c:666
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff8107c7a0-ffffffff8107c80c: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff8107e0b0-ffffffff8107e125: x86_fwspec_is_hpet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108bc44)
Location: arch/x86/kernel/apic/vector.c:666
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff8108bb70-ffffffff8108bbe6: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff8108d6d0-ffffffff8108d759: x86_fwspec_is_hpet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a00f4)
Location: arch/x86/kernel/apic/vector.c:662
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff810a0010-ffffffff810a0086: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff810a1da0-ffffffff810a1e29: x86_fwspec_is_hpet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3074)
Location: arch/x86/kernel/apic/vector.c:662
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff810a2f90-ffffffff810a3006: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff810a4d80-ffffffff810a4e09: x86_fwspec_is_hpet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_fwspec_is_hpet(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a9fab)
Location: arch/x86/kernel/apic/vector.c:673
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_select
  - drivers/iommu/amd/iommu.c:irq_remapping_select
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_select
```
**Symbols:**

```
ffffffff810a9ed0-ffffffff810a9f46: x86_fwspec_is_hpet.part.0 (STB_LOCAL)
ffffffff810abdd0-ffffffff810abe59: x86_fwspec_is_hpet (STB_GLOBAL)
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
