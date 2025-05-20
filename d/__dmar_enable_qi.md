# Function: <code>__dmar_enable_qi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533440)
Location: drivers/iommu/dmar.c:1375
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_reenable_qi
```
**Symbols:**

```
ffffffff81533440-ffffffff81533525: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815879d0)
Location: drivers/iommu/dmar.c:1388
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff815879d0-ffffffff81587ae3: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b5090)
Location: drivers/iommu/dmar.c:1389
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff815b5090-ffffffff815b51a3: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815caf50)
Location: drivers/iommu/dmar.c:1398
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff815caf50-ffffffff815cb03b: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81631d20)
Location: drivers/iommu/dmar.c:1401
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff81631d20-ffffffff81631e0b: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1401
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff8166d0b0-ffffffff8166d1b8: __dmar_enable_qi (STB_LOCAL)
ffffffff8166f1fc-ffffffff8166f208: __dmar_enable_qi.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1420
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff8168b4b0-ffffffff8168b5c9: __dmar_enable_qi (STB_LOCAL)
ffffffff8168d75c-ffffffff8168d768: __dmar_enable_qi.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1409
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff816c2ee0-ffffffff816c2fd4: __dmar_enable_qi (STB_LOCAL)
ffffffff816c514b-ffffffff816c5157: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1418
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff816e5dd0-ffffffff816e5ec4: __dmar_enable_qi (STB_LOCAL)
ffffffff816e807b-ffffffff816e8087: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1534
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff8179c6b0-ffffffff8179c7a7: __dmar_enable_qi (STB_LOCAL)
ffffffff8179ec59-ffffffff8179ec65: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1571
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff817aa380-ffffffff817aa477: __dmar_enable_qi (STB_LOCAL)
ffffffff81c0c084-ffffffff81c0c090: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1640
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff8178d120-ffffffff8178d21a: __dmar_enable_qi (STB_LOCAL)
ffffffff81bfd8c0-ffffffff81bfd8cc: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1669
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff81814480-ffffffff8181457a: __dmar_enable_qi (STB_LOCAL)
ffffffff81cfece5-ffffffff81cfecf1: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1665
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff819552d0-ffffffff819553d8: __dmar_enable_qi (STB_LOCAL)
ffffffff81ec74f2-ffffffff81ec74fe: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abb8d0)
Location: drivers/iommu/intel/dmar.c:1654
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff81abb8d0-ffffffff81abb9df: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b081b0)
Location: drivers/iommu/intel/dmar.c:1675
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff81b081b0-ffffffff81b082c0: __dmar_enable_qi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5c1d0)
Location: drivers/iommu/intel/dmar.c:1693
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_reenable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff81b5c1d0-ffffffff81b5c2e0: __dmar_enable_qi (STB_LOCAL)
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
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1418
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff816ab8b0-ffffffff816ab9a4: __dmar_enable_qi (STB_LOCAL)
ffffffff816adb5b-ffffffff816adb67: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1418
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff81689210-ffffffff81689304: __dmar_enable_qi (STB_LOCAL)
ffffffff8168b4bb-ffffffff8168b4c7: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1418
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff816d9a90-ffffffff816d9b84: __dmar_enable_qi (STB_LOCAL)
ffffffff816dbd3b-ffffffff816dbd47: __dmar_enable_qi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __dmar_enable_qi(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1418
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_reenable_qi
  - drivers/iommu/dmar.c:dmar_enable_qi
```
**Symbols:**

```
ffffffff816f4040-ffffffff816f4134: __dmar_enable_qi (STB_LOCAL)
ffffffff816f630b-ffffffff816f6317: __dmar_enable_qi.cold (STB_LOCAL)
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
