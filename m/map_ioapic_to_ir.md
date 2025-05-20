# Function: <code>map_ioapic_to_ir</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c851)
Location: drivers/iommu/intel_irq_remapping.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815913dc)
Location: drivers/iommu/intel_irq_remapping.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815bec9c)
Location: drivers/iommu/intel_irq_remapping.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815d48b0)
Location: drivers/iommu/intel_irq_remapping.c:213
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b650)
Location: drivers/iommu/intel_irq_remapping.c:214
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81676c04)
Location: drivers/iommu/intel_irq_remapping.c:214
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81695cb4)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce5f0)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816f2430)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *map_ioapic_to_ir(int apic);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ac020)
Location: drivers/iommu/intel/irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_get_ir_irq_domain
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir
```
**Symbols:**

```
ffffffff817ac2cb-ffffffff817ac2fe: map_ioapic_to_ir (STB_LOCAL)
```
</details>
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7c20)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81695860)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816e60f0)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
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
In drivers/iommu/intel_irq_remapping.c (ffffffff817007f0)
Location: drivers/iommu/intel_irq_remapping.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_get_ir_irq_domain
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
