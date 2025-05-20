# Function: <code>amd_iommu_iova_to_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152ea70)
Location: drivers/iommu/amd_iommu.c:3017
Inline: False
```
**Symbols:**

```
ffffffff8152ea70-ffffffff8152eafe: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815829a0)
Location: drivers/iommu/amd_iommu.c:3021
Inline: False
```
**Symbols:**

```
ffffffff815829a0-ffffffff81582a31: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815aec90)
Location: drivers/iommu/amd_iommu.c:3129
Inline: False
```
**Symbols:**

```
ffffffff815aec90-ffffffff815aed1e: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4890)
Location: drivers/iommu/amd_iommu.c:3269
Inline: False
```
**Symbols:**

```
ffffffff815c4890-ffffffff815c491e: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162b6f0)
Location: drivers/iommu/amd_iommu.c:3052
Inline: False
```
**Symbols:**

```
ffffffff8162b6f0-ffffffff8162b77e: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81666340)
Location: drivers/iommu/amd_iommu.c:3060
Inline: False
```
**Symbols:**

```
ffffffff81666340-ffffffff816663ce: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684c00)
Location: drivers/iommu/amd_iommu.c:3124
Inline: True
```
**Symbols:**

```
ffffffff81684c00-ffffffff81684c9d: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bc110)
Location: drivers/iommu/amd_iommu.c:3103
Inline: True
```
**Symbols:**

```
ffffffff816bc110-ffffffff816bc1b0: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816defa0)
Location: drivers/iommu/amd_iommu.c:3138
Inline: True
```
**Symbols:**

```
ffffffff816defa0-ffffffff816df040: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795e60)
Location: drivers/iommu/amd/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffffffff81795e60-ffffffff81795ef6: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4580)
Location: drivers/iommu/amd/iommu.c:2619
Inline: False
```
**Symbols:**

```
ffffffff817a4580-ffffffff817a4616: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81785e40)
Location: drivers/iommu/amd/iommu.c:2063
Inline: False
```
**Symbols:**

```
ffffffff81785e40-ffffffff81785e61: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180cce0)
Location: drivers/iommu/amd/iommu.c:2124
Inline: False
```
**Symbols:**

```
ffffffff8180cce0-ffffffff8180cd01: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194d380)
Location: drivers/iommu/amd/iommu.c:2140
Inline: False
```
**Symbols:**

```
ffffffff8194d380-ffffffff8194d3ab: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab18a0)
Location: drivers/iommu/amd/iommu.c:2278
Inline: False
```
**Symbols:**

```
ffffffff81ab18a0-ffffffff81ab18cb: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afd910)
Location: drivers/iommu/amd/iommu.c:2299
Inline: False
```
**Symbols:**

```
ffffffff81afd910-ffffffff81afd93b: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b50ef0)
Location: drivers/iommu/amd/iommu.c:2398
Inline: False
```
**Symbols:**

```
ffffffff81b50ef0-ffffffff81b50f1b: amd_iommu_iova_to_phys (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a49f0)
Location: drivers/iommu/amd_iommu.c:3138
Inline: True
```
**Symbols:**

```
ffffffff816a49f0-ffffffff816a4a90: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816823e0)
Location: drivers/iommu/amd_iommu.c:3138
Inline: True
```
**Symbols:**

```
ffffffff816823e0-ffffffff81682480: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2c60)
Location: drivers/iommu/amd_iommu.c:3138
Inline: True
```
**Symbols:**

```
ffffffff816d2c60-ffffffff816d2d00: amd_iommu_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t amd_iommu_iova_to_phys(struct iommu_domain *dom, dma_addr_t iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ed300)
Location: drivers/iommu/amd_iommu.c:3138
Inline: True
```
**Symbols:**

```
ffffffff816ed300-ffffffff816ed3a0: amd_iommu_iova_to_phys (STB_LOCAL)
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
