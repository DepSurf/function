# Function: <code>fetch_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152e8f0)
Location: drivers/iommu/amd_iommu.c:1198
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:alloc_new_range
```
**Symbols:**

```
ffffffff8152e8f0-ffffffff8152ea6d: fetch_pte.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81582830)
Location: drivers/iommu/amd_iommu.c:1304
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
```
**Symbols:**

```
ffffffff81582830-ffffffff81582995: fetch_pte.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815aeb20)
Location: drivers/iommu/amd_iommu.c:1394
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
```
**Symbols:**

```
ffffffff815aeb20-ffffffff815aec85: fetch_pte.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4710)
Location: drivers/iommu/amd_iommu.c:1453
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iova_to_phys
```
**Symbols:**

```
ffffffff815c4710-ffffffff815c4881: fetch_pte.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162b560)
Location: drivers/iommu/amd_iommu.c:1394
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iova_to_phys
```
**Symbols:**

```
ffffffff8162b560-ffffffff8162b6ee: fetch_pte.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816661b0)
Location: drivers/iommu/amd_iommu.c:1400
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iova_to_phys
```
**Symbols:**

```
ffffffff816661b0-ffffffff8166633c: fetch_pte.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684a60)
Location: drivers/iommu/amd_iommu.c:1515
Inline: True
```
**Symbols:**

```
ffffffff81684a60-ffffffff81684bf5: fetch_pte.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bbfb0)
Location: drivers/iommu/amd_iommu.c:1530
Inline: True
```
**Symbols:**

```
ffffffff816bbfb0-ffffffff816bc10d: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dee40)
Location: drivers/iommu/amd_iommu.c:1583
Inline: True
```
**Symbols:**

```
ffffffff816dee40-ffffffff816def9e: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 *fetch_pte(struct protection_domain *domain, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795ce0)
Location: drivers/iommu/amd/iommu.c:1553
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
```
**Symbols:**

```
ffffffff81795ce0-ffffffff81795e52: fetch_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 *fetch_pte(struct protection_domain *domain, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4400)
Location: drivers/iommu/amd/iommu.c:1644
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iova_to_phys
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
```
**Symbols:**

```
ffffffff817a4400-ffffffff817a4572: fetch_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 *fetch_pte(struct amd_io_pgtable *pgtable, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c050)
Location: drivers/iommu/amd/io_pgtable.c:316
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_iova_to_phys
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
```
**Symbols:**

```
ffffffff8178c050-ffffffff8178c1b8: fetch_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 *fetch_pte(struct amd_io_pgtable *pgtable, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:316
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_iova_to_phys
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
```
**Symbols:**

```
ffffffff81813370-ffffffff818134c3: fetch_pte (STB_LOCAL)
ffffffff81cfe9d4-ffffffff81cfea7f: fetch_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 *fetch_pte(struct amd_io_pgtable *pgtable, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:290
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_iova_to_phys
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
```
**Symbols:**

```
ffffffff81954360-ffffffff819544ca: fetch_pte (STB_LOCAL)
ffffffff81ec7230-ffffffff81ec7292: fetch_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
u64 *fetch_pte(struct amd_io_pgtable *pgtable, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:290
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_iova_to_phys
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb5d0)
Location: drivers/iommu/amd/io_pgtable_v2.c:204
Inline: True
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_iova_to_phys
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_unmap_pages
```
**Symbols:**

```
ffffffff81aba160-ffffffff81aba2ca: fetch_pte (STB_LOCAL)
ffffffff82097183-ffffffff820971e5: fetch_pte.cold (STB_LOCAL)
ffffffff81abb5d0-ffffffff81abb690: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
u64 *fetch_pte(struct amd_io_pgtable *pgtable, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:290
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_iova_to_phys
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:198
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_iova_to_phys
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_unmap_pages
```
**Symbols:**

```
ffffffff81b06700-ffffffff81b06884: fetch_pte (STB_LOCAL)
ffffffff821180cc-ffffffff82118180: fetch_pte.cold (STB_LOCAL)
ffffffff81b07800-ffffffff81b07905: fetch_pte (STB_LOCAL)
ffffffff82118258-ffffffff8211829c: fetch_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
u64 *fetch_pte(struct amd_io_pgtable *pgtable, long unsigned int address, long unsigned int *page_size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:290
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_read_and_clear_dirty
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_iova_to_phys
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
```
```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:198
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_iova_to_phys
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_unmap_pages
```
**Symbols:**

```
ffffffff81b5a520-ffffffff81b5a6a4: fetch_pte (STB_LOCAL)
ffffffff821f5d99-ffffffff821f5e4d: fetch_pte.cold (STB_LOCAL)
ffffffff81b5b830-ffffffff81b5b935: fetch_pte (STB_LOCAL)
ffffffff821f5f65-ffffffff821f5fa9: fetch_pte.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4890)
Location: drivers/iommu/amd_iommu.c:1583
Inline: True
```
**Symbols:**

```
ffffffff816a4890-ffffffff816a49ee: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682280)
Location: drivers/iommu/amd_iommu.c:1583
Inline: True
```
**Symbols:**

```
ffffffff81682280-ffffffff816823de: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2b00)
Location: drivers/iommu/amd_iommu.c:1583
Inline: True
```
**Symbols:**

```
ffffffff816d2b00-ffffffff816d2c5e: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ed1a0)
Location: drivers/iommu/amd_iommu.c:1583
Inline: True
```
**Symbols:**

```
ffffffff816ed1a0-ffffffff816ed2fe: fetch_pte.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_io_pgtable *pgtable</code>
</li>
<li>
<b>Param removed. </b>
<code>struct protection_domain *domain</code>
</li>
</ul>
</details>
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
