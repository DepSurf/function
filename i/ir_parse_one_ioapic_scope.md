# Function: <code>ir_parse_one_ioapic_scope</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff8153cb59)
Location: drivers/iommu/intel_irq_remapping.c:844
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81591748)
Location: drivers/iommu/intel_irq_remapping.c:844
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf008)
Location: drivers/iommu/intel_irq_remapping.c:844
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4b33)
Location: drivers/iommu/intel_irq_remapping.c:851
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b8c3)
Location: drivers/iommu/intel_irq_remapping.c:852
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81676ed1)
Location: drivers/iommu/intel_irq_remapping.c:852
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81695f81)
Location: drivers/iommu/intel_irq_remapping.c:854
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce884)
Location: drivers/iommu/intel_irq_remapping.c:879
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816f26c4)
Location: drivers/iommu/intel_irq_remapping.c:879
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
int ir_parse_one_ioapic_scope(struct acpi_dmar_device_scope *scope, struct intel_iommu *iommu, struct acpi_dmar_hardware_unit *drhd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:893
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff817aac00-ffffffff817aacc4: ir_parse_one_ioapic_scope (STB_LOCAL)
ffffffff817ac316-ffffffff817ac392: ir_parse_one_ioapic_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ir_parse_one_ioapic_scope(struct acpi_dmar_device_scope *scope, struct intel_iommu *iommu, struct acpi_dmar_hardware_unit *drhd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:891
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff817b7160-ffffffff817b7228: ir_parse_one_ioapic_scope (STB_LOCAL)
ffffffff81c0d0b4-ffffffff81c0d130: ir_parse_one_ioapic_scope.cold (STB_LOCAL)
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
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a4ac)
Location: drivers/iommu/intel/irq_remapping.c:895
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81822ae8)
Location: drivers/iommu/intel/irq_remapping.c:902
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
In drivers/iommu/intel/irq_remapping.c (ffffffff819627ab)
Location: drivers/iommu/intel/irq_remapping.c:902
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb53b)
Location: drivers/iommu/intel/irq_remapping.c:896
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81b1809b)
Location: drivers/iommu/intel/irq_remapping.c:889
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d9db)
Location: drivers/iommu/intel/irq_remapping.c:889
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7eb4)
Location: drivers/iommu/intel_irq_remapping.c:879
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81695af4)
Location: drivers/iommu/intel_irq_remapping.c:879
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6384)
Location: drivers/iommu/intel_irq_remapping.c:879
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81700a84)
Location: drivers/iommu/intel_irq_remapping.c:879
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
