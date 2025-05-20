# Function: <code>intel_pasid_lookup_id</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81693f40)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff81693f40-ffffffff81693f7e: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816cc850)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff816cc850-ffffffff816cc88e: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f0090)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff816f0090-ffffffff816f00ce: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b5880)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff816b5880-ffffffff816b58be: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816934c0)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff816934c0-ffffffff816934fe: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e3d50)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff816e3d50-ffffffff816e3d8e: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *intel_pasid_lookup_id(int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe420)
Location: drivers/iommu/intel-pasid.c:55
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
**Symbols:**

```
ffffffff816fe420-ffffffff816fe460: intel_pasid_lookup_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
