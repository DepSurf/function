# Function: <code>intel_unmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153a170)
Location: drivers/iommu/intel-iommu.c:3580
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff8153a170-ffffffff8153a37c: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ec20)
Location: drivers/iommu/intel-iommu.c:3669
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff8158ec20-ffffffff8158ee21: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bc740)
Location: drivers/iommu/intel-iommu.c:3760
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff815bc740-ffffffff815bc943: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d25b0)
Location: drivers/iommu/intel-iommu.c:3752
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff815d25b0-ffffffff815d27ba: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81639390)
Location: drivers/iommu/intel-iommu.c:3656
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff81639390-ffffffff816394c0: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816745c0)
Location: drivers/iommu/intel-iommu.c:3704
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816745c0-ffffffff816746f3: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692bf0)
Location: drivers/iommu/intel-iommu.c:3721
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff81692bf0-ffffffff81692d23: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ca950)
Location: drivers/iommu/intel-iommu.c:3568
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816ca950-ffffffff816caaac: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816edaa0)
Location: drivers/iommu/intel-iommu.c:3583
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816edaa0-ffffffff816edc53: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a3d30)
Location: drivers/iommu/intel/iommu.c:3464
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_unmap_single
  - drivers/iommu/intel/iommu.c:intel_unmap_sg
  - drivers/iommu/intel/iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff817a3d30-ffffffff817a3f54: intel_unmap (STB_LOCAL)
```
</details>
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
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b3210)
Location: drivers/iommu/intel-iommu.c:3583
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816b3210-ffffffff816b33c3: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690ed0)
Location: drivers/iommu/intel-iommu.c:3583
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff81690ed0-ffffffff81691083: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e1760)
Location: drivers/iommu/intel-iommu.c:3583
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816e1760-ffffffff816e1913: intel_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_unmap(struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fbd70)
Location: drivers/iommu/intel-iommu.c:3583
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:intel_unmap_resource
  - drivers/iommu/intel-iommu.c:intel_unmap_page
```
**Symbols:**

```
ffffffff816fbd70-ffffffff816fbf2b: intel_unmap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
