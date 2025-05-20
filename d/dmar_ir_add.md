# Function: <code>dmar_ir_add</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff8153dd5e)
Location: drivers/iommu/intel_irq_remapping.c:1412
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81592d32)
Location: drivers/iommu/intel_irq_remapping.c:1412
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815c05f2)
Location: drivers/iommu/intel_irq_remapping.c:1412
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815d60d1)
Location: drivers/iommu/intel_irq_remapping.c:1420
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ce81)
Location: drivers/iommu/intel_irq_remapping.c:1426
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8167828a)
Location: drivers/iommu/intel_irq_remapping.c:1426
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8169736a)
Location: drivers/iommu/intel_irq_remapping.c:1428
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfccd)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3b0d)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dmar_ir_add(struct dmar_drhd_unit *dmaru, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:1467
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff817abb10-ffffffff817abbcd: dmar_ir_add (STB_LOCAL)
ffffffff817ac5c9-ffffffff817ac62a: dmar_ir_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dmar_ir_add(struct dmar_drhd_unit *dmaru, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:1437
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff817b7ef0-ffffffff817b7fad: dmar_ir_add (STB_LOCAL)
ffffffff81c0d33d-ffffffff81c0d39e: dmar_ir_add.cold (STB_LOCAL)
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
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b943)
Location: drivers/iommu/intel/irq_remapping.c:1442
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81824553)
Location: drivers/iommu/intel/irq_remapping.c:1449
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel/irq_remapping.c (ffffffff8196430e)
Location: drivers/iommu/intel/irq_remapping.c:1449
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd39c)
Location: drivers/iommu/intel/irq_remapping.c:1450
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19f0c)
Location: drivers/iommu/intel/irq_remapping.c:1441
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmar_ir_add(struct dmar_drhd_unit *dmaru, struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e630)
Location: drivers/iommu/intel/irq_remapping.c:1441
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81b6e630-ffffffff81b6e786: dmar_ir_add (STB_LOCAL)
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816b92fd)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f15)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816e77cd)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81701ecd)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
