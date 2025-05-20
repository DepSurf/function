# Function: <code>ir_parse_ioapic_hpet_scope</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153cb00)
Location: drivers/iommu/intel_irq_remapping.c:889
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8153cb00-ffffffff8153cd9b: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815916f0)
Location: drivers/iommu/intel_irq_remapping.c:889
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff815916f0-ffffffff8159196e: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815befb0)
Location: drivers/iommu/intel_irq_remapping.c:889
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff815befb0-ffffffff815bf22e: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4ae0)
Location: drivers/iommu/intel_irq_remapping.c:896
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff815d4ae0-ffffffff815d4d70: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b870)
Location: drivers/iommu/intel_irq_remapping.c:897
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8163b870-ffffffff8163bb00: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:897
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81676e70-ffffffff8167700c: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81678384-ffffffff8167846f: ir_parse_ioapic_hpet_scope.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:899
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81695f20-ffffffff816960bc: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81697464-ffffffff8169754f: ir_parse_ioapic_hpet_scope.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:924
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff816ce830-ffffffff816ce9d9: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff816cfdc3-ffffffff816cfeb4: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:924
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff816f2670-ffffffff816f2819: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff816f3c03-ffffffff816f3cf4: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aada0)
Location: drivers/iommu/intel/irq_remapping.c:938
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir
```
**Symbols:**

```
ffffffff817aada0-ffffffff817aae41: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7300)
Location: drivers/iommu/intel/irq_remapping.c:936
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir
```
**Symbols:**

```
ffffffff817b7300-ffffffff817b73a1: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:940
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8179a450-ffffffff8179a5fa: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81bff426-ffffffff81bff518: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:947
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81822a90-ffffffff81822f67: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81d0141e-ffffffff81d01442: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:947
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81962750-ffffffff81962c41: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81ec98e5-ffffffff81ec9909: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb4e0)
Location: drivers/iommu/intel/irq_remapping.c:941
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81acb4e0-ffffffff81acb9f8: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18040)
Location: drivers/iommu/intel/irq_remapping.c:934
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81b18040-ffffffff81b1856d: ir_parse_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d980)
Location: drivers/iommu/intel/irq_remapping.c:934
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81b6d980-ffffffff81b6dead: ir_parse_ioapic_hpet_scope (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:924
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff816b7e60-ffffffff816b8009: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff816b93f3-ffffffff816b94e4: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:924
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81695aa0-ffffffff81695c49: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81697028-ffffffff81697119: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:924
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff816e6330-ffffffff816e64d9: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff816e78c3-ffffffff816e79b4: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ir_parse_ioapic_hpet_scope(struct acpi_dmar_header *header, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:924
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81700a30-ffffffff81700bd9: ir_parse_ioapic_hpet_scope (STB_LOCAL)
ffffffff81701fc3-ffffffff817020b4: ir_parse_ioapic_hpet_scope.cold (STB_LOCAL)
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
