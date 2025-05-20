# Function: <code>intel_svm_check</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:98
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817aa8c4-ffffffff817aa8ee: intel_svm_check.cold (STB_LOCAL)
ffffffff817aa150-ffffffff817aa1a1: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:99
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81c0cfef-ffffffff81c0d019: intel_svm_check.cold (STB_LOCAL)
ffffffff817b65f0-ffffffff817b6641: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:99
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81bff387-ffffffff81bff3b1: intel_svm_check.cold (STB_LOCAL)
ffffffff81799890-ffffffff817998e8: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:176
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81d01341-ffffffff81d0136b: intel_svm_check.cold (STB_LOCAL)
ffffffff81821df0-ffffffff81821e48: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:171
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ec9865-ffffffff81ec988f: intel_svm_check.cold (STB_LOCAL)
ffffffff81961fc0-ffffffff81962029: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81acadf0)
Location: drivers/iommu/intel/svm.c:154
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81acadf0-ffffffff81acae8d: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b17940)
Location: drivers/iommu/intel/svm.c:152
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b17940-ffffffff81b179dd: intel_svm_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_svm_check(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b6cf30)
Location: drivers/iommu/intel/svm.c:150
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b6cf30-ffffffff81b6cfcd: intel_svm_check (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
