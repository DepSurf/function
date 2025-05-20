# Function: <code>intel_svm_prq_report</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_svm_prq_report(struct device *dev, struct page_req_dsc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817b5710)
Location: drivers/iommu/intel/svm.c:892
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff817b5710-ffffffff817b581a: intel_svm_prq_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_svm_prq_report(struct device *dev, struct page_req_dsc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81798a20)
Location: drivers/iommu/intel/svm.c:845
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81798a20-ffffffff81798b2d: intel_svm_prq_report (STB_LOCAL)
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
In drivers/iommu/intel/svm.c (ffffffff818213db)
Location: drivers/iommu/intel/svm.c:848
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81961558)
Location: drivers/iommu/intel/svm.c:627
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81ac9f0a)
Location: drivers/iommu/intel/svm.c:593
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81b16a8a)
Location: drivers/iommu/intel/svm.c:579
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81b6c16a)
Location: drivers/iommu/intel/svm.c:565
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
