# Function: <code>iopf_queue_free</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iopf_queue_free(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff8182fde0)
Location: drivers/iommu/io-pgfault.c:448
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
**Symbols:**

```
ffffffff8182fde0-ffffffff8182fe46: iopf_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iopf_queue_free(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81971010)
Location: drivers/iommu/io-pgfault.c:448
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
**Symbols:**

```
ffffffff81971010-ffffffff81971093: iopf_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iopf_queue_free(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81adc210)
Location: drivers/iommu/io-pgfault.c:405
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
**Symbols:**

```
ffffffff81adc210-ffffffff81adc293: iopf_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iopf_queue_free(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b2a480)
Location: drivers/iommu/io-pgfault.c:405
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
**Symbols:**

```
ffffffff81b2a480-ffffffff81b2a503: iopf_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iopf_queue_free(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b81650)
Location: drivers/iommu/io-pgfault.c:405
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
**Symbols:**

```
ffffffff81b81650-ffffffff81b816d3: iopf_queue_free (STB_GLOBAL)
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
