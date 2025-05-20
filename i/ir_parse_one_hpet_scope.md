# Function: <code>ir_parse_one_hpet_scope</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff8153cc11)
Location: drivers/iommu/intel_irq_remapping.c:799
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815917fb)
Location: drivers/iommu/intel_irq_remapping.c:799
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf0bb)
Location: drivers/iommu/intel_irq_remapping.c:799
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4bea)
Location: drivers/iommu/intel_irq_remapping.c:806
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b97a)
Location: drivers/iommu/intel_irq_remapping.c:807
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676f72)
Location: drivers/iommu/intel_irq_remapping.c:807
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696022)
Location: drivers/iommu/intel_irq_remapping.c:809
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce93c)
Location: drivers/iommu/intel_irq_remapping.c:834
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f277c)
Location: drivers/iommu/intel_irq_remapping.c:834
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ir_parse_one_hpet_scope(struct acpi_dmar_device_scope *scope, struct intel_iommu *iommu, struct acpi_dmar_hardware_unit *drhd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:848
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff817aacd0-ffffffff817aad92: ir_parse_one_hpet_scope (STB_LOCAL)
ffffffff817ac392-ffffffff817ac404: ir_parse_one_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ir_parse_one_hpet_scope(struct acpi_dmar_device_scope *scope, struct intel_iommu *iommu, struct acpi_dmar_hardware_unit *drhd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:846
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff817b7230-ffffffff817b72f6: ir_parse_one_hpet_scope (STB_LOCAL)
ffffffff81c0d130-ffffffff81c0d1a2: ir_parse_one_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a560)
Location: drivers/iommu/intel/irq_remapping.c:850
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81822bbc)
Location: drivers/iommu/intel/irq_remapping.c:857
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962892)
Location: drivers/iommu/intel/irq_remapping.c:857
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb622)
Location: drivers/iommu/intel/irq_remapping.c:851
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81b1818b)
Location: drivers/iommu/intel/irq_remapping.c:844
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6dacb)
Location: drivers/iommu/intel/irq_remapping.c:844
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7f6c)
Location: drivers/iommu/intel_irq_remapping.c:834
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695bac)
Location: drivers/iommu/intel_irq_remapping.c:834
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e643c)
Location: drivers/iommu/intel_irq_remapping.c:834
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81700b3c)
Location: drivers/iommu/intel_irq_remapping.c:834
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
