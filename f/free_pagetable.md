# Function: <code>free_pagetable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181bb2c)
Location: arch/x86/mm/init_64.c:713
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152f060)
Location: drivers/iommu/amd_iommu.c:1675
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8181bb2c-ffffffff8181bbe0: free_pagetable (STB_LOCAL)
ffffffff8152f060-ffffffff8152f137: free_pagetable.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81895d26)
Location: arch/x86/mm/init_64.c:677
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In drivers/iommu/amd_iommu.c (ffffffff81582c40)
Location: drivers/iommu/amd_iommu.c:1570
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:dma_ops_domain_free
```
**Symbols:**

```
ffffffff81895d26-ffffffff81895df5: free_pagetable (STB_LOCAL)
ffffffff81582c40-ffffffff81582d05: free_pagetable.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818ca446)
Location: arch/x86/mm/init_64.c:667
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In drivers/iommu/amd_iommu.c (ffffffff815af050)
Location: drivers/iommu/amd_iommu.c:1660
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:dma_ops_domain_free
```
**Symbols:**

```
ffffffff818ca446-ffffffff818ca512: free_pagetable (STB_LOCAL)
ffffffff815af050-ffffffff815af115: free_pagetable.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819019c5)
Location: arch/x86/mm/init_64.c:795
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4d80)
Location: drivers/iommu/amd_iommu.c:1719
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff819019c5-ffffffff81901a8c: free_pagetable (STB_LOCAL)
ffffffff815c4d80-ffffffff815c4e46: free_pagetable.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198b9f5)
Location: arch/x86/mm/init_64.c:803
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162bb50)
Location: drivers/iommu/amd_iommu.c:1661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff8198b9f5-ffffffff8198babc: free_pagetable (STB_LOCAL)
ffffffff8162bb50-ffffffff8162bc27: free_pagetable.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e8307)
Location: arch/x86/mm/init_64.c:814
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In drivers/iommu/amd_iommu.c (ffffffff816667b0)
Location: drivers/iommu/amd_iommu.c:1664
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff819e8307-ffffffff819e83ab: free_pagetable (STB_LOCAL)
ffffffff816667b0-ffffffff81666887: free_pagetable.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a238f7)
Location: arch/x86/mm/init_64.c:807
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685080)
Location: drivers/iommu/amd_iommu.c:1411
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81a238f7-ffffffff81a2399b: free_pagetable (STB_LOCAL)
ffffffff81685080-ffffffff816850a7: free_pagetable.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a93c25)
Location: arch/x86/mm/init_64.c:874
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bc590)
Location: drivers/iommu/amd_iommu.c:1420
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81a93c25-ffffffff81a93cc9: free_pagetable (STB_LOCAL)
ffffffff816bc590-ffffffff816bc5b9: free_pagetable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acb505)
Location: arch/x86/mm/init_64.c:874
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff816df4f0)
Location: drivers/iommu/amd_iommu.c:1446
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81acb505-ffffffff81acb5a9: free_pagetable (STB_LOCAL)
ffffffff816df4f0-ffffffff816df51a: free_pagetable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc3a0b)
Location: arch/x86/mm/init_64.c:882
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:free_hugepage_table
```
```
In drivers/iommu/amd/iommu.c (ffffffff81799c40)
Location: drivers/iommu/amd/iommu.c:1384
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff81bc3a0b-ffffffff81bc3aad: free_pagetable (STB_LOCAL)
ffffffff81799c40-ffffffff81799c9a: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3c93b)
Location: arch/x86/mm/init_64.c:876
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:free_hugepage_table
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a8370)
Location: drivers/iommu/amd/iommu.c:1474
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff81c3c93b-ffffffff81c3c9d8: free_pagetable (STB_LOCAL)
ffffffff817a8370-ffffffff817a83ca: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2ee17)
Location: arch/x86/mm/init_64.c:974
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff81c2ee17-ffffffff81c2eeb4: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d518)
Location: arch/x86/mm/init_64.c:975
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff81d4d518-ffffffff81d4d5b5: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d222)
Location: arch/x86/mm/init_64.c:975
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:free_hugepage_table
```
**Symbols:**

```
ffffffff81f1d222-ffffffff81f1d2cb: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5390)
Location: arch/x86/mm/init_64.c:976
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff820c5390-ffffffff820c5467: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff821493f0)
Location: arch/x86/mm/init_64.c:976
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff821493f0-ffffffff821494c7: free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222beb0)
Location: arch/x86/mm/init_64.c:976
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
**Symbols:**

```
ffffffff8222beb0-ffffffff8222bf87: free_pagetable (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6a375)
Location: arch/x86/mm/init_64.c:874
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a4f40)
Location: drivers/iommu/amd_iommu.c:1446
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81a6a375-ffffffff81a6a419: free_pagetable (STB_LOCAL)
ffffffff816a4f40-ffffffff816a4f6a: free_pagetable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a26837)
Location: arch/x86/mm/init_64.c:874
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff81682930)
Location: drivers/iommu/amd_iommu.c:1446
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81a26837-ffffffff81a268db: free_pagetable (STB_LOCAL)
ffffffff81682930-ffffffff8168295a: free_pagetable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad6785)
Location: arch/x86/mm/init_64.c:874
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d31b0)
Location: drivers/iommu/amd_iommu.c:1446
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81ad6785-ffffffff81ad6829: free_pagetable (STB_LOCAL)
ffffffff816d31b0-ffffffff816d31da: free_pagetable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void free_pagetable(struct page *page, int order);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae2c45)
Location: arch/x86/mm/init_64.c:874
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ed850)
Location: drivers/iommu/amd_iommu.c:1446
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81ae2c45-ffffffff81ae2ce9: free_pagetable (STB_LOCAL)
ffffffff816ed850-ffffffff816ed87a: free_pagetable.isra.0 (STB_LOCAL)
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
