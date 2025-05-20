# Function: <code>iommu_disable_irq_remapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153d290)
Location: drivers/iommu/intel_irq_remapping.c:616
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8153d290-ffffffff8153d331: iommu_disable_irq_remapping.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592ceb)
Location: drivers/iommu/intel_irq_remapping.c:616
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81591ec0-ffffffff81591f81: iommu_disable_irq_remapping.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c05ab)
Location: drivers/iommu/intel_irq_remapping.c:616
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff815bf780-ffffffff815bf841: iommu_disable_irq_remapping.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d615e)
Location: drivers/iommu/intel_irq_remapping.c:623
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff815d5250-ffffffff815d52f1: iommu_disable_irq_remapping.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163cf0e)
Location: drivers/iommu/intel_irq_remapping.c:624
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff8163c000-ffffffff8163c0a1: iommu_disable_irq_remapping.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81678248)
Location: drivers/iommu/intel_irq_remapping.c:624
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81677200-ffffffff816772be: iommu_disable_irq_remapping.part.4 (STB_LOCAL)
ffffffff8167846f-ffffffff8167847b: iommu_disable_irq_remapping.part.4.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81697328)
Location: drivers/iommu/intel_irq_remapping.c:626
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81696320-ffffffff816963de: iommu_disable_irq_remapping.part.6 (STB_LOCAL)
ffffffff8169754f-ffffffff8169755b: iommu_disable_irq_remapping.part.6.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfc8d)
Location: drivers/iommu/intel_irq_remapping.c:651
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816cebf0-ffffffff816cec89: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff816cfeb4-ffffffff816cfec0: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3acd)
Location: drivers/iommu/intel_irq_remapping.c:651
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816f2a30-ffffffff816f2ac9: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff816f3cf4-ffffffff816f3d00: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_disable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ac282)
Location: drivers/iommu/intel/irq_remapping.c:665
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff817ab030-ffffffff817ab0cc: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff817ac42e-ffffffff817ac43a: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
ffffffff817ac43a-ffffffff817ac451: iommu_disable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_disable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8792)
Location: drivers/iommu/intel/irq_remapping.c:663
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff817b7490-ffffffff817b752c: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff81c0d1a2-ffffffff81c0d1ae: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
ffffffff81c0d1ae-ffffffff81c0d1c5: iommu_disable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_disable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b91d)
Location: drivers/iommu/intel/irq_remapping.c:664
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff8179a600-ffffffff8179a6a2: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff81bff518-ffffffff81bff524: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
ffffffff81bff524-ffffffff81bff53b: iommu_disable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_disable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8182452d)
Location: drivers/iommu/intel/irq_remapping.c:671
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81822f70-ffffffff81823012: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff81d01442-ffffffff81d0144e: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
ffffffff81d0144e-ffffffff81d01465: iommu_disable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_disable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff819642a2)
Location: drivers/iommu/intel/irq_remapping.c:671
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81962c50-ffffffff81962d00: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff81ec995d-ffffffff81ec9969: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
ffffffff81ec9969-ffffffff81ec998c: iommu_disable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd332)
Location: drivers/iommu/intel/irq_remapping.c:664
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81acbca0-ffffffff81acbd66: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19ea2)
Location: drivers/iommu/intel/irq_remapping.c:657
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b18820-ffffffff81b188e7: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6fafc)
Location: drivers/iommu/intel/irq_remapping.c:657
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b6e160-ffffffff81b6e227: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b92bd)
Location: drivers/iommu/intel_irq_remapping.c:651
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816b8220-ffffffff816b82b9: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff816b94e4-ffffffff816b94f0: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ed5)
Location: drivers/iommu/intel_irq_remapping.c:651
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81695e60-ffffffff81695ef9: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff81697119-ffffffff81697125: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e778d)
Location: drivers/iommu/intel_irq_remapping.c:651
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816e66f0-ffffffff816e6789: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff816e79b4-ffffffff816e79c0: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701e8d)
Location: drivers/iommu/intel_irq_remapping.c:651
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81700df0-ffffffff81700e89: iommu_disable_irq_remapping.part.0 (STB_LOCAL)
ffffffff817020b4-ffffffff817020c0: iommu_disable_irq_remapping.part.0.cold (STB_LOCAL)
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
