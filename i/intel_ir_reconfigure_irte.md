# Function: <code>intel_ir_reconfigure_irte</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163bd60)
Location: drivers/iommu/intel_irq_remapping.c:1125
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff8163bd60-ffffffff8163bdad: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677670)
Location: drivers/iommu/intel_irq_remapping.c:1125
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81677670-ffffffff816776c1: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696750)
Location: drivers/iommu/intel_irq_remapping.c:1127
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81696750-ffffffff816967a1: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf060)
Location: drivers/iommu/intel_irq_remapping.c:1152
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff816cf060-ffffffff816cf0b7: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f2ea0)
Location: drivers/iommu/intel_irq_remapping.c:1152
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff816f2ea0-ffffffff816f2ef7: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ac0c5)
Location: drivers/iommu/intel/irq_remapping.c:1166
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff817ab720-ffffffff817ab772: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8585)
Location: drivers/iommu/intel/irq_remapping.c:1131
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff817b7b00-ffffffff817b7b52: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b6d5)
Location: drivers/iommu/intel/irq_remapping.c:1135
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff8179ac70-ffffffff8179acc2: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff818242e5)
Location: drivers/iommu/intel/irq_remapping.c:1142
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff818237a0-ffffffff818237f2: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81964075)
Location: drivers/iommu/intel/irq_remapping.c:1142
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81963210-ffffffff81963269: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd0d5)
Location: drivers/iommu/intel/irq_remapping.c:1136
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81acc2b0-ffffffff81acc309: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19c45)
Location: drivers/iommu/intel/irq_remapping.c:1129
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81b18e40-ffffffff81b18e99: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6f8a5)
Location: drivers/iommu/intel/irq_remapping.c:1129
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81b6f5d0-ffffffff81b6f629: intel_ir_reconfigure_irte (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8690)
Location: drivers/iommu/intel_irq_remapping.c:1152
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff816b8690-ffffffff816b86e7: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816962d0)
Location: drivers/iommu/intel_irq_remapping.c:1152
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff816962d0-ffffffff81696327: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6b60)
Location: drivers/iommu/intel_irq_remapping.c:1152
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff816e6b60-ffffffff816e6bb7: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_ir_reconfigure_irte(struct irq_data *irqd, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701260)
Location: drivers/iommu/intel_irq_remapping.c:1152
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81701260-ffffffff817012b7: intel_ir_reconfigure_irte (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
