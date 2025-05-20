# Function: <code>iopf_queue_add_device</code>

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
int iopf_queue_add_device(struct iopf_queue *queue, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff818300f0)
Location: drivers/iommu/io-pgfault.c:332
Inline: False
```
**Symbols:**

```
ffffffff818300f0-ffffffff818301dc: iopf_queue_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iopf_queue_add_device(struct iopf_queue *queue, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81971370)
Location: drivers/iommu/io-pgfault.c:332
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81971370-ffffffff8197146d: iopf_queue_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iopf_queue_add_device(struct iopf_queue *queue, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81adc4a0)
Location: drivers/iommu/io-pgfault.c:289
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81adc4a0-ffffffff81adc59d: iopf_queue_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iopf_queue_add_device(struct iopf_queue *queue, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b2a710)
Location: drivers/iommu/io-pgfault.c:289
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81b2a710-ffffffff81b2a80d: iopf_queue_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iopf_queue_add_device(struct iopf_queue *queue, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b81910)
Location: drivers/iommu/io-pgfault.c:289
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81b81910-ffffffff81b81a3c: iopf_queue_add_device (STB_GLOBAL)
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
