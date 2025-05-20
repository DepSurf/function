# Function: <code>fq_ring_free</code>

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
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629e80)
Location: drivers/iommu/iova.c:471
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81629e80-ffffffff81629f4d: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664b90)
Location: drivers/iommu/iova.c:471
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81664b90-ffffffff81664c5d: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81683190)
Location: drivers/iommu/iova.c:480
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81683190-ffffffff8168325d: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba760)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff816ba760-ffffffff816ba80f: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd5a0)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff816dd5a0-ffffffff816dd64f: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81794320)
Location: drivers/iommu/iova.c:479
Inline: False
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81794320-ffffffff81794429: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0e10)
Location: drivers/iommu/iova.c:494
Inline: False
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff817c0e10-ffffffff817c0ebf: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a4260)
Location: drivers/iommu/iova.c:559
Inline: False
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff817a4260-ffffffff817a430f: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182d3d0)
Location: drivers/iommu/iova.c:561
Inline: False
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff8182d3d0-ffffffff8182d52d: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fq_ring_free(struct iommu_dma_cookie *cookie, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81969ff0)
Location: drivers/iommu/dma-iommu.c:123
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81969ff0-ffffffff8196a13b: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fq_ring_free(struct iommu_dma_cookie *cookie, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad4080)
Location: drivers/iommu/dma-iommu.c:126
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81ad4080-ffffffff81ad41cb: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fq_ring_free(struct iommu_dma_cookie *cookie, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b22850)
Location: drivers/iommu/dma-iommu.c:127
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff81b22850-ffffffff81b2299b: fq_ring_free (STB_LOCAL)
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
In drivers/iommu/dma-iommu.c (ffffffff81b79ef4)
Location: drivers/iommu/dma-iommu.c:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd940)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffff8000108cd940-ffff8000108cda00: fq_ring_free (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2ff0)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff816a2ff0-ffffffff816a309f: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816809e0)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff816809e0-ffffffff81680a8f: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d1260)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff816d1260-ffffffff816d130f: fq_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fq_ring_free(struct iova_domain *iovad, struct iova_fq *fq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ebb70)
Location: drivers/iommu/iova.c:479
Inline: True
Direct callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
```
**Symbols:**

```
ffffffff816ebb70-ffffffff816ebc1f: fq_ring_free (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_dma_cookie *cookie</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iova_domain *iovad</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
