# Function: <code>iommu_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067bc0)
Location: arch/x86/kernel/pci-calgary_64.c:290
Inline: True
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
```
**Symbols:**

```
ffffffff81067bc0-ffffffff81067c63: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067920)
Location: arch/x86/kernel/pci-calgary_64.c:290
Inline: True
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff81067920-ffffffff810679bd: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b570)
Location: arch/x86/kernel/pci-calgary_64.c:290
Inline: True
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8106b570-ffffffff8106b60d: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a290)
Location: arch/x86/kernel/pci-calgary_64.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8106a290-ffffffff8106a320: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106eba0)
Location: arch/x86/kernel/pci-calgary_64.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8106eba0-ffffffff8106ec30: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81071a70)
Location: arch/x86/kernel/pci-calgary_64.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff81071a70-ffffffff81071af7: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81077a90)
Location: arch/x86/kernel/pci-calgary_64.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff81077a90-ffffffff81077b14: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b5f0)
Location: arch/x86/kernel/pci-calgary_64.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8107b5f0-ffffffff8107b684: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107c6e0)
Location: arch/x86/kernel/pci-calgary_64.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8107c6e0-ffffffff8107c774: iommu_free (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000051b90)
Location: arch/powerpc/kernel/iommu.c:405
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_free_coherent
  - arch/powerpc/kernel/iommu.c:iommu_unmap_page
```
**Symbols:**

```
c000000000051b90-c000000000051bf0: iommu_free (STB_LOCAL)
```
</details>
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
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b6e0)
Location: arch/x86/kernel/pci-calgary_64.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8107b6e0-ffffffff8107b774: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ae10)
Location: arch/x86/kernel/pci-calgary_64.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8106ae10-ffffffff8106aea4: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b690)
Location: arch/x86/kernel/pci-calgary_64.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8107b690-ffffffff8107b724: iommu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_free(struct iommu_table *tbl, dma_addr_t dma_addr, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107d790)
Location: arch/x86/kernel/pci-calgary_64.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
**Symbols:**

```
ffffffff8107d790-ffffffff8107d824: iommu_free (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
