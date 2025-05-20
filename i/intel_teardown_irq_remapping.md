# Function: <code>intel_teardown_irq_remapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153ca60)
Location: drivers/iommu/intel_irq_remapping.c:594
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8153ca60-ffffffff8153caf7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81591650)
Location: drivers/iommu/intel_irq_remapping.c:594
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81591650-ffffffff815916e7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bef10)
Location: drivers/iommu/intel_irq_remapping.c:594
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff815bef10-ffffffff815befa7: intel_teardown_irq_remapping (STB_LOCAL)
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815d6200)
Location: drivers/iommu/intel_irq_remapping.c:601
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff815d53c0-ffffffff815d5443: intel_teardown_irq_remapping.part.7 (STB_LOCAL)
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8163cfb0)
Location: drivers/iommu/intel_irq_remapping.c:602
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff8163c170-ffffffff8163c1f3: intel_teardown_irq_remapping.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677370)
Location: drivers/iommu/intel_irq_remapping.c:602
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81677370-ffffffff81677407: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696430)
Location: drivers/iommu/intel_irq_remapping.c:604
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81696430-ffffffff816964c7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ced40)
Location: drivers/iommu/intel_irq_remapping.c:629
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816ced40-ffffffff816cedd7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f2b80)
Location: drivers/iommu/intel_irq_remapping.c:629
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816f2b80-ffffffff816f2c17: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab0d0)
Location: drivers/iommu/intel/irq_remapping.c:635
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff817ab0d0-ffffffff817ab187: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7530)
Location: drivers/iommu/intel/irq_remapping.c:633
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff817b7530-ffffffff817b75e7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a6b0)
Location: drivers/iommu/intel/irq_remapping.c:634
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff8179a6b0-ffffffff8179a767: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823020)
Location: drivers/iommu/intel/irq_remapping.c:641
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81823020-ffffffff818230d7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962d00)
Location: drivers/iommu/intel/irq_remapping.c:641
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81962d00-ffffffff81962dcb: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbd80)
Location: drivers/iommu/intel/irq_remapping.c:641
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81acbd80-ffffffff81acbe21: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18900)
Location: drivers/iommu/intel/irq_remapping.c:634
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81b18900-ffffffff81b189a1: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e240)
Location: drivers/iommu/intel/irq_remapping.c:634
Inline: True
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81b6e240-ffffffff81b6e2e1: intel_teardown_irq_remapping (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8370)
Location: drivers/iommu/intel_irq_remapping.c:629
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816b8370-ffffffff816b8407: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695fb0)
Location: drivers/iommu/intel_irq_remapping.c:629
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81695fb0-ffffffff81696047: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6840)
Location: drivers/iommu/intel_irq_remapping.c:629
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff816e6840-ffffffff816e68d7: intel_teardown_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void intel_teardown_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81700f40)
Location: drivers/iommu/intel_irq_remapping.c:629
Inline: True
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:intel_cleanup_irq_remapping
```
**Symbols:**

```
ffffffff81700f40-ffffffff81700fd7: intel_teardown_irq_remapping (STB_LOCAL)
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
