# Function: <code>intel_svm_unbind_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8153b800)
Location: drivers/iommu/intel-svm.c:428
Inline: False
```
**Symbols:**

```
ffffffff8153b800-ffffffff8153b9d5: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81590320)
Location: drivers/iommu/intel-svm.c:428
Inline: False
```
**Symbols:**

```
ffffffff81590320-ffffffff81590504: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815bdbb0)
Location: drivers/iommu/intel-svm.c:434
Inline: False
```
**Symbols:**

```
ffffffff815bdbb0-ffffffff815bdd95: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815d3cb0)
Location: drivers/iommu/intel-svm.c:426
Inline: False
```
**Symbols:**

```
ffffffff815d3cb0-ffffffff815d3e6a: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8163a9e0)
Location: drivers/iommu/intel-svm.c:430
Inline: False
```
**Symbols:**

```
ffffffff8163a9e0-ffffffff8163abb4: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81675fd0)
Location: drivers/iommu/intel-svm.c:447
Inline: False
```
**Symbols:**

```
ffffffff81675fd0-ffffffff816761a2: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81695870)
Location: drivers/iommu/intel-svm.c:383
Inline: False
```
**Symbols:**

```
ffffffff81695870-ffffffff816959e8: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816cdb40)
Location: drivers/iommu/intel-svm.c:392
Inline: False
```
**Symbols:**

```
ffffffff816cdb40-ffffffff816cdcae: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816f1980)
Location: drivers/iommu/intel-svm.c:388
Inline: False
```
**Symbols:**

```
ffffffff816f1980-ffffffff816f1afe: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817a99f0)
Location: drivers/iommu/intel/svm.c:600
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind
```
**Symbols:**

```
ffffffff817a99f0-ffffffff817a9b2f: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817b6280)
Location: drivers/iommu/intel/svm.c:681
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind
```
**Symbols:**

```
ffffffff817b6280-ffffffff817b644b: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81799510)
Location: drivers/iommu/intel/svm.c:634
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind
```
**Symbols:**

```
ffffffff81799510-ffffffff817996dd: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81821a40)
Location: drivers/iommu/intel/svm.c:639
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind
```
**Symbols:**

```
ffffffff81821a40-ffffffff81821be2: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81961c20)
Location: drivers/iommu/intel/svm.c:423
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind
```
**Symbols:**

```
ffffffff81961c20-ffffffff81961d97: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/svm.c (ffffffff81aca930)
Location: drivers/iommu/intel/svm.c:389
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
```
**Symbols:**

```
ffffffff81aca930-ffffffff81acaae0: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/svm.c (ffffffff81b16e90)
Location: drivers/iommu/intel/svm.c:375
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
```
**Symbols:**

```
ffffffff81b16e90-ffffffff81b17067: intel_svm_unbind_mm.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816b7170)
Location: drivers/iommu/intel-svm.c:388
Inline: False
```
**Symbols:**

```
ffffffff816b7170-ffffffff816b72ee: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81694db0)
Location: drivers/iommu/intel-svm.c:388
Inline: False
```
**Symbols:**

```
ffffffff81694db0-ffffffff81694f2e: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816e5640)
Location: drivers/iommu/intel-svm.c:388
Inline: False
```
**Symbols:**

```
ffffffff816e5640-ffffffff816e57be: intel_svm_unbind_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_svm_unbind_mm(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff817002f0)
Location: drivers/iommu/intel-svm.c:388
Inline: False
```
**Symbols:**

```
ffffffff817002f0-ffffffff8170046e: intel_svm_unbind_mm (STB_GLOBAL)
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
