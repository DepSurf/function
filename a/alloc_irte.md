# Function: <code>alloc_irte</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff8153d442)
Location: drivers/iommu/intel_irq_remapping.c:103
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8159209f)
Location: drivers/iommu/intel_irq_remapping.c:103
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815bf95f)
Location: drivers/iommu/intel_irq_remapping.c:103
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5502)
Location: drivers/iommu/intel_irq_remapping.c:103
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c2b2)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81677819)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816968f9)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf20f)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816f304f)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int alloc_irte(struct intel_iommu *iommu, struct irq_2_iommu *irq_iommu, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:104
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff817aae50-ffffffff817aaf42: alloc_irte (STB_LOCAL)
ffffffff817ac404-ffffffff817ac42e: alloc_irte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8223)
Location: drivers/iommu/intel/irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b373)
Location: drivers/iommu/intel/irq_remapping.c:105
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81823e93)
Location: drivers/iommu/intel/irq_remapping.c:105
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel/irq_remapping.c (ffffffff819636c8)
Location: drivers/iommu/intel/irq_remapping.c:105
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81acc7b6)
Location: drivers/iommu/intel/irq_remapping.c:106
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19349)
Location: drivers/iommu/intel/irq_remapping.c:106
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int alloc_irte(struct intel_iommu *iommu, struct irq_2_iommu *irq_iommu, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:106
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81b6e7a0-ffffffff81b6e92b: alloc_irte (STB_LOCAL)
ffffffff821f6821-ffffffff821f683f: alloc_irte.cold (STB_LOCAL)
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816b883f)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8169647f)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6d0f)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8170140f)
Location: drivers/iommu/intel_irq_remapping.c:104
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
