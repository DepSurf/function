# Function: <code>amd_iommu_flush_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dee0)
Location: drivers/iommu/amd_iommu.c:3271
Inline: False
```
**Symbols:**

```
ffffffff8152dee0-ffffffff8152df3d: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581a30)
Location: drivers/iommu/amd_iommu.c:3289
Inline: False
```
**Symbols:**

```
ffffffff81581a30-ffffffff81581a85: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af3e0)
Location: drivers/iommu/amd_iommu.c:3413
Inline: False
```
**Symbols:**

```
ffffffff815af3e0-ffffffff815af435: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5170)
Location: drivers/iommu/amd_iommu.c:3553
Inline: False
```
**Symbols:**

```
ffffffff815c5170-ffffffff815c51c5: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162bec0)
Location: drivers/iommu/amd_iommu.c:3344
Inline: False
```
**Symbols:**

```
ffffffff8162bec0-ffffffff8162bf15: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816673c0)
Location: drivers/iommu/amd_iommu.c:3368
Inline: False
```
**Symbols:**

```
ffffffff816673c0-ffffffff81667415: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685a70)
Location: drivers/iommu/amd_iommu.c:3433
Inline: False
```
**Symbols:**

```
ffffffff81685a70-ffffffff81685ac5: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bcfb0)
Location: drivers/iommu/amd_iommu.c:3414
Inline: False
```
**Symbols:**

```
ffffffff816bcfb0-ffffffff816bd007: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dff90)
Location: drivers/iommu/amd_iommu.c:3450
Inline: False
```
**Symbols:**

```
ffffffff816dff90-ffffffff816dffe7: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796380)
Location: drivers/iommu/amd/iommu.c:2847
Inline: False
```
**Symbols:**

```
ffffffff81796380-ffffffff817963d7: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4b60)
Location: drivers/iommu/amd/iommu.c:2938
Inline: False
```
**Symbols:**

```
ffffffff817a4b60-ffffffff817a4bb7: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178a510)
Location: drivers/iommu/amd/iommu.c:2354
Inline: False
```
**Symbols:**

```
ffffffff8178a510-ffffffff8178a56a: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81811850)
Location: drivers/iommu/amd/iommu.c:2422
Inline: False
```
**Symbols:**

```
ffffffff81811850-ffffffff818118aa: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81951eb0)
Location: drivers/iommu/amd/iommu.c:2448
Inline: False
```
**Symbols:**

```
ffffffff81951eb0-ffffffff81951f14: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab6f80)
Location: drivers/iommu/amd/iommu.c:2609
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
**Symbols:**

```
ffffffff81ab6f80-ffffffff81ab6fe4: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b032a0)
Location: drivers/iommu/amd/iommu.c:2629
Inline: False
Direct callers:
  - drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages
```
**Symbols:**

```
ffffffff81b032a0-ffffffff81b03304: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, u32 pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b579e0)
Location: drivers/iommu/amd/iommu.c:2716
Inline: False
```
**Symbols:**

```
ffffffff81b579e0-ffffffff81b57a47: amd_iommu_flush_page (STB_GLOBAL)
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
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a59e0)
Location: drivers/iommu/amd_iommu.c:3450
Inline: False
```
**Symbols:**

```
ffffffff816a59e0-ffffffff816a5a37: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816833d0)
Location: drivers/iommu/amd_iommu.c:3450
Inline: False
```
**Symbols:**

```
ffffffff816833d0-ffffffff81683427: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3c50)
Location: drivers/iommu/amd_iommu.c:3450
Inline: False
```
**Symbols:**

```
ffffffff816d3c50-ffffffff816d3ca7: amd_iommu_flush_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int amd_iommu_flush_page(struct iommu_domain *dom, int pasid, u64 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ee350)
Location: drivers/iommu/amd_iommu.c:3450
Inline: False
```
**Symbols:**

```
ffffffff816ee350-ffffffff816ee3a7: amd_iommu_flush_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
