# Function: <code>iommu_enable_irq_remapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c990)
Location: drivers/iommu/intel_irq_remapping.c:480
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
**Symbols:**

```
ffffffff8153c990-ffffffff8153ca56: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81591560)
Location: drivers/iommu/intel_irq_remapping.c:480
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81591560-ffffffff8159164a: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bee20)
Location: drivers/iommu/intel_irq_remapping.c:480
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff815bee20-ffffffff815bef0a: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4a10)
Location: drivers/iommu/intel_irq_remapping.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff815d4a10-ffffffff815d4ad2: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b7a0)
Location: drivers/iommu/intel_irq_remapping.c:473
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff8163b7a0-ffffffff8163b867: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:473
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81676d90-ffffffff81676e66: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81678378-ffffffff81678384: iommu_enable_irq_remapping.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:475
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81695e40-ffffffff81695f16: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81697458-ffffffff81697464: iommu_enable_irq_remapping.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff816ce780-ffffffff816ce82c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff816cfdb7-ffffffff816cfdc3: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff816f25c0-ffffffff816f266c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff816f3bf7-ffffffff816f3c03: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff817aab10-ffffffff817aabfc: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff817ac30a-ffffffff817ac316: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:499
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff817b7070-ffffffff817b715c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81c0d0a8-ffffffff81c0d0b4: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:500
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff8179a360-ffffffff8179a44f: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81bff41a-ffffffff81bff426: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:500
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff818229a0-ffffffff81822a8f: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81d01412-ffffffff81d0141e: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:500
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81962650-ffffffff8196274d: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81ec98d9-ffffffff81ec98e5: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb3d0)
Location: drivers/iommu/intel/irq_remapping.c:499
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81acb3d0-ffffffff81acb4cc: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17de0)
Location: drivers/iommu/intel/irq_remapping.c:491
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81b17de0-ffffffff81b17ee5: iommu_enable_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d720)
Location: drivers/iommu/intel/irq_remapping.c:491
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81b6d720-ffffffff81b6d825: iommu_enable_irq_remapping (STB_LOCAL)
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
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff816b7db0-ffffffff816b7e5c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff816b93e7-ffffffff816b93f3: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff816959f0-ffffffff81695a9c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff8169701c-ffffffff81697028: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff816e6280-ffffffff816e632c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff816e78b7-ffffffff816e78c3: iommu_enable_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void iommu_enable_irq_remapping(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:501
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel_irq_remapping.c:intel_enable_irq_remapping
```
**Symbols:**

```
ffffffff81700980-ffffffff81700a2c: iommu_enable_irq_remapping (STB_LOCAL)
ffffffff81701fb7-ffffffff81701fc3: iommu_enable_irq_remapping.cold (STB_LOCAL)
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
