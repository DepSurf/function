# Function: <code>ir_remove_ioapic_hpet_scope</code>

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
In drivers/iommu/intel_irq_remapping.c (ffffffff8153dd3a)
Location: drivers/iommu/intel_irq_remapping.c:913
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81592d11)
Location: drivers/iommu/intel_irq_remapping.c:913
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815c05d1)
Location: drivers/iommu/intel_irq_remapping.c:913
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff815d6220)
Location: drivers/iommu/intel_irq_remapping.c:920
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8163cfd0)
Location: drivers/iommu/intel_irq_remapping.c:921
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8167825a)
Location: drivers/iommu/intel_irq_remapping.c:921
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff8169733a)
Location: drivers/iommu/intel_irq_remapping.c:923
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfca1)
Location: drivers/iommu/intel_irq_remapping.c:948
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3ae1)
Location: drivers/iommu/intel_irq_remapping.c:948
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aa990)
Location: drivers/iommu/intel/irq_remapping.c:962
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
**Symbols:**

```
ffffffff817aa990-ffffffff817aa9f5: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b6ef0)
Location: drivers/iommu/intel/irq_remapping.c:960
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
**Symbols:**

```
ffffffff817b6ef0-ffffffff817b6f55: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a1d0)
Location: drivers/iommu/intel/irq_remapping.c:964
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8179a1d0-ffffffff8179a235: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81822780)
Location: drivers/iommu/intel/irq_remapping.c:971
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81822780-ffffffff81822874: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962410)
Location: drivers/iommu/intel/irq_remapping.c:971
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81962410-ffffffff8196250c: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb140)
Location: drivers/iommu/intel/irq_remapping.c:965
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81acb140-ffffffff81acb23c: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17c80)
Location: drivers/iommu/intel/irq_remapping.c:958
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff81b17c80-ffffffff81b17d82: ir_remove_ioapic_hpet_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ir_remove_ioapic_hpet_scope(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d5c0)
Location: drivers/iommu/intel/irq_remapping.c:958
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
**Symbols:**

```
ffffffff81b6d5c0-ffffffff81b6d6c2: ir_remove_ioapic_hpet_scope (STB_LOCAL)
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816b92d1)
Location: drivers/iommu/intel_irq_remapping.c:948
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ee9)
Location: drivers/iommu/intel_irq_remapping.c:948
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff816e77a1)
Location: drivers/iommu/intel_irq_remapping.c:948
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
In drivers/iommu/intel_irq_remapping.c (ffffffff81701ea1)
Location: drivers/iommu/intel_irq_remapping.c:948
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
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
