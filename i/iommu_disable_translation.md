# Function: <code>iommu_disable_translation</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535d40)
Location: drivers/iommu/intel-iommu.c:1600
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:disable_dmar_iommu
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81535d40-ffffffff81535dc8: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158a430)
Location: drivers/iommu/intel-iommu.c:1639
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:disable_dmar_iommu
```
**Symbols:**

```
ffffffff8158a430-ffffffff8158a4d8: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b7aa0)
Location: drivers/iommu/intel-iommu.c:1653
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815b7aa0-ffffffff815b7b48: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cdb80)
Location: drivers/iommu/intel-iommu.c:1658
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815cdb80-ffffffff815cdc08: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816349c0)
Location: drivers/iommu/intel-iommu.c:1660
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816349c0-ffffffff81634a48: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1688
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8166ff20-ffffffff8166ffc5: iommu_disable_translation (STB_LOCAL)
ffffffff816753cb-ffffffff816753d7: iommu_disable_translation.cold.79 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1565
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168e440-ffffffff8168e4e5: iommu_disable_translation (STB_LOCAL)
ffffffff81693842-ffffffff8169384e: iommu_disable_translation.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1576
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c5ab0-ffffffff816c5b30: iommu_disable_translation (STB_LOCAL)
ffffffff816cbd05-ffffffff816cbd11: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1587
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816e8ae0-ffffffff816e8b60: iommu_disable_translation (STB_LOCAL)
ffffffff816ef60b-ffffffff816ef617: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1628
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8179fa60-ffffffff8179fb13: iommu_disable_translation (STB_LOCAL)
ffffffff817a69f5-ffffffff817a6a01: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1726
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817ad600-ffffffff817ad6b3: iommu_disable_translation (STB_LOCAL)
ffffffff81c0c32b-ffffffff81c0c337: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1750
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8178ff90-ffffffff81790046: iommu_disable_translation (STB_LOCAL)
ffffffff81bfdb95-ffffffff81bfdba1: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1754
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81817800-ffffffff818178b6: iommu_disable_translation (STB_LOCAL)
ffffffff81cff21e-ffffffff81cff22a: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1673
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81958780-ffffffff81958856: iommu_disable_translation (STB_LOCAL)
ffffffff81ec7a2d-ffffffff81ec7a39: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81abf910)
Location: drivers/iommu/intel/iommu.c:1641
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:disable_dmar_iommu
```
**Symbols:**

```
ffffffff81abf910-ffffffff81abf9ee: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0c170)
Location: drivers/iommu/intel/iommu.c:1612
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:disable_dmar_iommu
```
**Symbols:**

```
ffffffff81b0c170-ffffffff81b0c24e: iommu_disable_translation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b607e0)
Location: drivers/iommu/intel/iommu.c:1562
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_shutdown
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:iommu_suspend
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:disable_dmar_iommu
```
**Symbols:**

```
ffffffff81b607e0-ffffffff81b608be: iommu_disable_translation (STB_LOCAL)
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
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1587
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816ae5c0-ffffffff816ae640: iommu_disable_translation (STB_LOCAL)
ffffffff816b4dfb-ffffffff816b4e07: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1587
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168bf20-ffffffff8168bfa0: iommu_disable_translation (STB_LOCAL)
ffffffff81692a3b-ffffffff81692a47: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1587
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816dc7a0-ffffffff816dc820: iommu_disable_translation (STB_LOCAL)
ffffffff816e32cb-ffffffff816e32d7: iommu_disable_translation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void iommu_disable_translation(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1587
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:iommu_suspend
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f6de0-ffffffff816f6e60: iommu_disable_translation (STB_LOCAL)
ffffffff816fd95b-ffffffff816fd967: iommu_disable_translation.cold (STB_LOCAL)
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
