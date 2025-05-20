# Function: <code>dmar_disable_qi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81534f60)
Location: drivers/iommu/dmar.c:1340
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff81534f60-ffffffff8153506f: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815897c0)
Location: drivers/iommu/dmar.c:1353
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff815897c0-ffffffff8158991a: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b6e80)
Location: drivers/iommu/dmar.c:1354
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff815b6e80-ffffffff815b6fda: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cccc0)
Location: drivers/iommu/dmar.c:1363
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff815cccc0-ffffffff815ccdd0: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81633ab0)
Location: drivers/iommu/dmar.c:1366
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff81633ab0-ffffffff81633bc7: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1366
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff8166f4cf-ffffffff8166f4db: dmar_disable_qi.cold.29 (STB_LOCAL)
ffffffff8166ec30-ffffffff8166ed70: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1385
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff8168da36-ffffffff8168da42: dmar_disable_qi.cold.28 (STB_LOCAL)
ffffffff8168d180-ffffffff8168d2c0: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1374
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff816c5462-ffffffff816c546e: dmar_disable_qi.cold (STB_LOCAL)
ffffffff816c4bb0-ffffffff816c4cb7: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1383
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff816e8399-ffffffff816e83a5: dmar_disable_qi.cold (STB_LOCAL)
ffffffff816e7ae0-ffffffff816e7be7: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1499
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff8179eed7-ffffffff8179eee3: dmar_disable_qi.cold (STB_LOCAL)
ffffffff8179e620-ffffffff8179e727: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1536
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff81c0c31f-ffffffff81c0c32b: dmar_disable_qi.cold (STB_LOCAL)
ffffffff817ac370-ffffffff817ac477: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1605
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff81bfdb89-ffffffff81bfdb95: dmar_disable_qi.cold (STB_LOCAL)
ffffffff8178f240-ffffffff8178f34d: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1634
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff81cff212-ffffffff81cff21e: dmar_disable_qi.cold (STB_LOCAL)
ffffffff81816b60-ffffffff81816c6d: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1630
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81ec7a21-ffffffff81ec7a2d: dmar_disable_qi.cold (STB_LOCAL)
ffffffff81957b40-ffffffff81957c69: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abeaf0)
Location: drivers/iommu/intel/dmar.c:1619
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81abeaf0-ffffffff81abec20: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b0b480)
Location: drivers/iommu/intel/dmar.c:1640
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b0b480-ffffffff81b0b5b1: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5f4f0)
Location: drivers/iommu/intel/dmar.c:1658
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b5f4f0-ffffffff81b5f621: dmar_disable_qi (STB_GLOBAL)
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
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1383
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff816ade79-ffffffff816ade85: dmar_disable_qi.cold (STB_LOCAL)
ffffffff816ad5c0-ffffffff816ad6c7: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1383
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff8168b7d9-ffffffff8168b7e5: dmar_disable_qi.cold (STB_LOCAL)
ffffffff8168af20-ffffffff8168b027: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1383
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff816dc059-ffffffff816dc065: dmar_disable_qi.cold (STB_LOCAL)
ffffffff816db7a0-ffffffff816db8a7: dmar_disable_qi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dmar_disable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1383
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff816f6629-ffffffff816f6635: dmar_disable_qi.cold (STB_LOCAL)
ffffffff816f5d70-ffffffff816f5e77: dmar_disable_qi (STB_GLOBAL)
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
