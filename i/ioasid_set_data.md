# Function: <code>ioasid_set_data</code>

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
int ioasid_set_data(ioasid_t ioasid, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81792dd0)
Location: drivers/iommu/ioasid.c:268
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81792dd0-ffffffff81792e3b: ioasid_set_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ioasid_set_data(ioasid_t ioasid, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff817bf760)
Location: drivers/iommu/ioasid.c:269
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817bf760-ffffffff817bf7cb: ioasid_set_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ioasid_set_data(ioasid_t ioasid, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff817a2980)
Location: drivers/iommu/ioasid.c:269
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817a2980-ffffffff817a29eb: ioasid_set_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ioasid_set_data(ioasid_t ioasid, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff8182bcc0)
Location: drivers/iommu/ioasid.c:269
Inline: False
```
**Symbols:**

```
ffffffff8182bcc0-ffffffff8182bd2b: ioasid_set_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioasid_set_data(ioasid_t ioasid, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff8196d140)
Location: drivers/iommu/ioasid.c:268
Inline: False
```
**Symbols:**

```
ffffffff8196d140-ffffffff8196d1ab: ioasid_set_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioasid_set_data(ioasid_t ioasid, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7900)
Location: drivers/iommu/ioasid.c:268
Inline: False
```
**Symbols:**

```
ffffffff81ad7900-ffffffff81ad796b: ioasid_set_data (STB_GLOBAL)
```
</details>
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
</ul>
