# Function: <code>iommu_set_irq_remapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c8a0)
Location: drivers/iommu/intel_irq_remapping.c:453
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff8153c8a0-ffffffff8153c984: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81591440)
Location: drivers/iommu/intel_irq_remapping.c:453
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff81591440-ffffffff81591551: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bed00)
Location: drivers/iommu/intel_irq_remapping.c:453
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff815bed00-ffffffff815bee11: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4910)
Location: drivers/iommu/intel_irq_remapping.c:445
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff815d4910-ffffffff815d4a01: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b6a0)
Location: drivers/iommu/intel_irq_remapping.c:446
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff8163b6a0-ffffffff8163b791: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:446
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff81676ca0-ffffffff81676d85: iommu_set_irq_remapping (STB_LOCAL)
ffffffff8167836c-ffffffff81678378: iommu_set_irq_remapping.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:448
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff81695d50-ffffffff81695e35: iommu_set_irq_remapping (STB_LOCAL)
ffffffff8169744c-ffffffff81697458: iommu_set_irq_remapping.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff816ce690-ffffffff816ce77b: iommu_set_irq_remapping (STB_LOCAL)
ffffffff816cfdab-ffffffff816cfdb7: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff816f24d0-ffffffff816f25bb: iommu_set_irq_remapping (STB_LOCAL)
ffffffff816f3beb-ffffffff816f3bf7: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff817aaa20-ffffffff817aab0e: iommu_set_irq_remapping (STB_LOCAL)
ffffffff817ac2fe-ffffffff817ac30a: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:472
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff817b6f80-ffffffff817b706e: iommu_set_irq_remapping (STB_LOCAL)
ffffffff81c0d09c-ffffffff81c0d0a8: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:473
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff8179a260-ffffffff8179a359: iommu_set_irq_remapping (STB_LOCAL)
ffffffff81bff40e-ffffffff81bff41a: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:473
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff818228a0-ffffffff81822999: iommu_set_irq_remapping (STB_LOCAL)
ffffffff81d01406-ffffffff81d01412: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:473
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81962540-ffffffff81962641: iommu_set_irq_remapping (STB_LOCAL)
ffffffff81ec98cd-ffffffff81ec98d9: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb290)
Location: drivers/iommu/intel/irq_remapping.c:471
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81acb290-ffffffff81acb3b5: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17f00)
Location: drivers/iommu/intel/irq_remapping.c:463
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b17f00-ffffffff81b18026: iommu_set_irq_remapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d840)
Location: drivers/iommu/intel/irq_remapping.c:463
Inline: False
Direct callers:
  - drivers/iommu/intel/irq_remapping.c:reenable_irq_remapping
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b6d840-ffffffff81b6d966: iommu_set_irq_remapping (STB_LOCAL)
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
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff816b7cc0-ffffffff816b7dab: iommu_set_irq_remapping (STB_LOCAL)
ffffffff816b93db-ffffffff816b93e7: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff81695900-ffffffff816959eb: iommu_set_irq_remapping (STB_LOCAL)
ffffffff81697010-ffffffff8169701c: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff816e6190-ffffffff816e627b: iommu_set_irq_remapping (STB_LOCAL)
ffffffff816e78ab-ffffffff816e78b7: iommu_set_irq_remapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void iommu_set_irq_remapping(struct intel_iommu *iommu, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:474
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:reenable_irq_remapping
```
**Symbols:**

```
ffffffff81700890-ffffffff8170097b: iommu_set_irq_remapping (STB_LOCAL)
ffffffff81701fab-ffffffff81701fb7: iommu_set_irq_remapping.cold (STB_LOCAL)
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
