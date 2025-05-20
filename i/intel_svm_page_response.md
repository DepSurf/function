# Function: <code>intel_svm_page_response</code>

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
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817b6c60)
Location: drivers/iommu/intel/svm.c:1153
Inline: False
```
**Symbols:**

```
ffffffff817b6c60-ffffffff817b6ea6: intel_svm_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81799f20)
Location: drivers/iommu/intel/svm.c:1109
Inline: False
```
**Symbols:**

```
ffffffff81799f20-ffffffff8179a18c: intel_svm_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff818224e0)
Location: drivers/iommu/intel/svm.c:1101
Inline: False
```
**Symbols:**

```
ffffffff818224e0-ffffffff81822740: intel_svm_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff819621b0)
Location: drivers/iommu/intel/svm.c:882
Inline: False
```
**Symbols:**

```
ffffffff819621b0-ffffffff819623b5: intel_svm_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81acaea0)
Location: drivers/iommu/intel/svm.c:773
Inline: False
```
**Symbols:**

```
ffffffff81acaea0-ffffffff81acb012: intel_svm_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b179f0)
Location: drivers/iommu/intel/svm.c:759
Inline: False
```
**Symbols:**

```
ffffffff81b179f0-ffffffff81b17b61: intel_svm_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_svm_page_response(struct device *dev, struct iommu_fault_event *evt, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b6d3b0)
Location: drivers/iommu/intel/svm.c:745
Inline: False
```
**Symbols:**

```
ffffffff81b6d3b0-ffffffff81b6d4db: intel_svm_page_response (STB_GLOBAL)
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
