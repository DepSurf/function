# Function: <code>init_iova_flush_queue</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816291d0)
Location: drivers/iommu/iova.c:85
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816291d0-ffffffff816292a5: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81663ef0)
Location: drivers/iommu/iova.c:85
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81663ef0-ffffffff81663fcc: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682780)
Location: drivers/iommu/iova.c:86
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81682780-ffffffff8168285c: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816b9b30)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816b9b30-ffffffff816b9c05: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dc920)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816dc920-ffffffff816dc9f5: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81793500)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffffffff81793500-ffffffff817935d5: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817bfe50)
Location: drivers/iommu/iova.c:80
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff817bfe50-ffffffff817bff25: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3c40)
Location: drivers/iommu/iova.c:98
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff817a3c40-ffffffff817a3d14: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182d9d0)
Location: drivers/iommu/iova.c:97
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff8182d9d0-ffffffff8182dad9: init_iova_flush_queue (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cc898)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffff8000108cc898-ffff8000108cc97c: init_iova_flush_queue (STB_GLOBAL)
```
</details>
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
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2370)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816a2370-ffffffff816a2445: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8167fd60)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8167fd60-ffffffff8167fe35: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d05e0)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816d05e0-ffffffff816d06b5: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_iova_flush_queue(struct iova_domain *iovad, iova_flush_cb flush_cb, iova_entry_dtor entry_dtor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eab70)
Location: drivers/iommu/iova.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816eab70-ffffffff816eac45: init_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
