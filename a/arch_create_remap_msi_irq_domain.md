# Function: <code>arch_create_remap_msi_irq_domain</code>

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
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105b010)
Location: arch/x86/kernel/apic/msi.c:177
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8105b010-ffffffff8105b065: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105f520)
Location: arch/x86/kernel/apic/msi.c:173
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8105f520-ffffffff8105f575: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81062630)
Location: arch/x86/kernel/apic/msi.c:174
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff81062630-ffffffff8106268b: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81068330)
Location: arch/x86/kernel/apic/msi.c:174
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff81068330-ffffffff8106838b: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106bb20)
Location: arch/x86/kernel/apic/msi.c:171
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8106bb20-ffffffff8106bb7e: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c6d0)
Location: arch/x86/kernel/apic/msi.c:293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8106c6d0-ffffffff8106c72e: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810739f0)
Location: arch/x86/kernel/apic/msi.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff810739f0-ffffffff81073a67: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81074750)
Location: arch/x86/kernel/apic/msi.c:234
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff81074750-ffffffff810747c7: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81075200)
Location: arch/x86/kernel/apic/msi.c:238
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff81075200-ffffffff81075277: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810826f0)
Location: arch/x86/kernel/apic/msi.c:238
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff810826f0-ffffffff81082767: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810922d0)
Location: arch/x86/kernel/apic/msi.c:236
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff810922d0-ffffffff8109233e: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c1c0)
Location: arch/x86/kernel/apic/msi.c:293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8106c1c0-ffffffff8106c21e: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105c4e0)
Location: arch/x86/kernel/apic/msi.c:293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8105c4e0-ffffffff8105c53e: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c670)
Location: arch/x86/kernel/apic/msi.c:293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8106c670-ffffffff8106c6ce: arch_create_remap_msi_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *arch_create_remap_msi_irq_domain(struct irq_domain *parent, const char *name, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106dd70)
Location: arch/x86/kernel/apic/msi.c:293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
```
**Symbols:**

```
ffffffff8106dd70-ffffffff8106ddce: arch_create_remap_msi_irq_domain (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
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
