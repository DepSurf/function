# Function: <code>intel_cap_audit</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:171
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81bff1db-ffffffff81bff21a: intel_cap_audit.cold (STB_LOCAL)
ffffffff817983e0-ffffffff817984d1: intel_cap_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:171
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81d010a7-ffffffff81d010e6: intel_cap_audit.cold (STB_LOCAL)
ffffffff81820c20-ffffffff81820d11: intel_cap_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:180
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81ec95a5-ffffffff81ec95e6: intel_cap_audit.cold (STB_LOCAL)
ffffffff81960d20-ffffffff81960e46: intel_cap_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81ac97e0)
Location: drivers/iommu/intel/cap_audit.c:180
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81ac97e0-ffffffff81ac9942: intel_cap_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b16360)
Location: drivers/iommu/intel/cap_audit.c:178
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81b16360-ffffffff81b164db: intel_cap_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b6bca0)
Location: drivers/iommu/intel/cap_audit.c:178
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81b6bca0-ffffffff81b6be1b: intel_cap_audit (STB_GLOBAL)
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
