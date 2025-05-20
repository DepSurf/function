# Function: <code>intel_iommu_iova_to_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81538170)
Location: drivers/iommu/intel-iommu.c:4931
Inline: False
```
**Symbols:**

```
ffffffff81538170-ffffffff815381cf: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158cc60)
Location: drivers/iommu/intel-iommu.c:5069
Inline: False
```
**Symbols:**

```
ffffffff8158cc60-ffffffff8158ccbf: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ba3a0)
Location: drivers/iommu/intel-iommu.c:5162
Inline: False
```
**Symbols:**

```
ffffffff815ba3a0-ffffffff815ba3ff: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cf8a0)
Location: drivers/iommu/intel-iommu.c:5196
Inline: False
```
**Symbols:**

```
ffffffff815cf8a0-ffffffff815cf901: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636630)
Location: drivers/iommu/intel-iommu.c:5110
Inline: False
```
**Symbols:**

```
ffffffff81636630-ffffffff81636691: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81671ba0)
Location: drivers/iommu/intel-iommu.c:5148
Inline: False
```
**Symbols:**

```
ffffffff81671ba0-ffffffff81671c01: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816904d0)
Location: drivers/iommu/intel-iommu.c:5203
Inline: False
```
**Symbols:**

```
ffffffff816904d0-ffffffff81690531: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c8660)
Location: drivers/iommu/intel-iommu.c:5243
Inline: False
```
**Symbols:**

```
ffffffff816c8660-ffffffff816c86c5: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eb610)
Location: drivers/iommu/intel-iommu.c:5523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff816eb610-ffffffff816eb69f: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2750)
Location: drivers/iommu/intel/iommu.c:5582
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_unmap_single
  - drivers/iommu/intel/iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff817a2750-ffffffff817a27e3: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af9b0)
Location: drivers/iommu/intel/iommu.c:5026
Inline: False
```
**Symbols:**

```
ffffffff817af9b0-ffffffff817afa43: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817929a0)
Location: drivers/iommu/intel/iommu.c:5124
Inline: False
```
**Symbols:**

```
ffffffff817929a0-ffffffff81792a33: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181a7b0)
Location: drivers/iommu/intel/iommu.c:5148
Inline: False
```
**Symbols:**

```
ffffffff8181a7b0-ffffffff8181a843: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195aed0)
Location: drivers/iommu/intel/iommu.c:4498
Inline: False
```
**Symbols:**

```
ffffffff8195aed0-ffffffff8195af6f: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac2a80)
Location: drivers/iommu/intel/iommu.c:4408
Inline: False
```
**Symbols:**

```
ffffffff81ac2a80-ffffffff81ac2b1c: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0f910)
Location: drivers/iommu/intel/iommu.c:4299
Inline: False
```
**Symbols:**

```
ffffffff81b0f910-ffffffff81b0f9b1: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b64200)
Location: drivers/iommu/intel/iommu.c:4194
Inline: False
```
**Symbols:**

```
ffffffff81b64200-ffffffff81b642a1: intel_iommu_iova_to_phys (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0f40)
Location: drivers/iommu/intel-iommu.c:5523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff816b0f40-ffffffff816b0fcf: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168ea40)
Location: drivers/iommu/intel-iommu.c:5523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff8168ea40-ffffffff8168eacf: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816df2d0)
Location: drivers/iommu/intel-iommu.c:5523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff816df2d0-ffffffff816df35f: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t intel_iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f98e0)
Location: drivers/iommu/intel-iommu.c:5523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff816f98e0-ffffffff816f996f: intel_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
