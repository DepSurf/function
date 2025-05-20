# Function: <code>intel_svm_drain_prq</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, int pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817a9280)
Location: drivers/iommu/intel/svm.c:727
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
**Symbols:**

```
ffffffff817a9280-ffffffff817a946d: intel_svm_drain_prq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817b5270)
Location: drivers/iommu/intel/svm.c:803
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
**Symbols:**

```
ffffffff817b5270-ffffffff817b545d: intel_svm_drain_prq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81798690)
Location: drivers/iommu/intel/svm.c:756
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
**Symbols:**

```
ffffffff81798690-ffffffff81798880: intel_svm_drain_prq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81820e00)
Location: drivers/iommu/intel/svm.c:746
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
```
**Symbols:**

```
ffffffff81820e00-ffffffff81821059: intel_svm_drain_prq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81960f50)
Location: drivers/iommu/intel/svm.c:525
Inline: False
```
**Symbols:**

```
ffffffff81960f50-ffffffff819611f1: intel_svm_drain_prq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81ac9af0)
Location: drivers/iommu/intel/svm.c:491
Inline: False
```
**Symbols:**

```
ffffffff81ac9af0-ffffffff81ac9d42: intel_svm_drain_prq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_svm_drain_prq(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b16680)
Location: drivers/iommu/intel/svm.c:477
Inline: False
```
**Symbols:**

```
ffffffff81b16680-ffffffff81b168ce: intel_svm_drain_prq (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
</ul>
