# Function: <code>intel_flush_svm_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8153b9e0)
Location: drivers/iommu/intel-svm.c:195
Inline: True
Direct callers:
  - drivers/iommu/intel-svm.c:intel_change_pte
  - drivers/iommu/intel-svm.c:intel_invalidate_page
  - drivers/iommu/intel-svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff8153b9e0-ffffffff8153ba7e: intel_flush_svm_range.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81590510)
Location: drivers/iommu/intel-svm.c:195
Inline: True
Direct callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
  - drivers/iommu/intel-svm.c:intel_invalidate_page
  - drivers/iommu/intel-svm.c:intel_change_pte
```
**Symbols:**

```
ffffffff81590510-ffffffff815905b3: intel_flush_svm_range.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815bdda0)
Location: drivers/iommu/intel-svm.c:201
Inline: True
Direct callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
  - drivers/iommu/intel-svm.c:intel_invalidate_page
  - drivers/iommu/intel-svm.c:intel_change_pte
```
**Symbols:**

```
ffffffff815bdda0-ffffffff815bde43: intel_flush_svm_range.constprop.7 (STB_LOCAL)
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
In drivers/iommu/intel-svm.c (ffffffff815d3e70)
Location: drivers/iommu/intel-svm.c:202
Inline: True
Direct callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
  - drivers/iommu/intel-svm.c:intel_change_pte
```
**Symbols:**

```
ffffffff815d3e70-ffffffff815d3f0c: intel_flush_svm_range.constprop.7 (STB_LOCAL)
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
In drivers/iommu/intel-svm.c (ffffffff8163abc0)
Location: drivers/iommu/intel-svm.c:206
Inline: True
Direct callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
  - drivers/iommu/intel-svm.c:intel_change_pte
```
**Symbols:**

```
ffffffff8163abc0-ffffffff8163ac5a: intel_flush_svm_range.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816761b0)
Location: drivers/iommu/intel-svm.c:218
Inline: True
Direct callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
  - drivers/iommu/intel-svm.c:intel_change_pte
```
**Symbols:**

```
ffffffff816761b0-ffffffff8167624a: intel_flush_svm_range.constprop.9 (STB_LOCAL)
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
In drivers/iommu/intel-svm.c (ffffffff81695728)
Location: drivers/iommu/intel-svm.c:172
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
  - drivers/iommu/intel-svm.c:intel_change_pte
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
In drivers/iommu/intel-svm.c (ffffffff816cdae3)
Location: drivers/iommu/intel-svm.c:158
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
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
In drivers/iommu/intel-svm.c (ffffffff816f1923)
Location: drivers/iommu/intel-svm.c:154
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817a9623)
Location: drivers/iommu/intel/svm.c:172
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
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
In drivers/iommu/intel/svm.c (ffffffff817b5600)
Location: drivers/iommu/intel/svm.c:191
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff817b5600-ffffffff817b56d5: intel_flush_svm_range.constprop.0 (STB_LOCAL)
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
In drivers/iommu/intel/svm.c (ffffffff81798880)
Location: drivers/iommu/intel/svm.c:154
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
**Symbols:**

```
ffffffff81798880-ffffffff817989ec: intel_flush_svm_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff8182108b)
Location: drivers/iommu/intel/svm.c:231
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81961226)
Location: drivers/iommu/intel/svm.c:226
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81aca806)
Location: drivers/iommu/intel/svm.c:212
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b17516)
Location: drivers/iommu/intel/svm.c:210
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_invalidate_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b6cb41)
Location: drivers/iommu/intel/svm.c:208
Inline: True
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
In drivers/iommu/intel-svm.c (ffffffff816b7113)
Location: drivers/iommu/intel-svm.c:154
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
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
In drivers/iommu/intel-svm.c (ffffffff81694d53)
Location: drivers/iommu/intel-svm.c:154
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
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
In drivers/iommu/intel-svm.c (ffffffff816e55e3)
Location: drivers/iommu/intel-svm.c:154
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
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
In drivers/iommu/intel-svm.c (ffffffff8170029d)
Location: drivers/iommu/intel-svm.c:154
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_invalidate_range
```
</details>
</li>
</ul>

## Differences
