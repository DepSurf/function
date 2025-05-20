# Function: <code>update_domain</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152fc10)
Location: drivers/iommu/amd_iommu.c:2264
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:__map_single
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:__map_single
```
**Symbols:**

```
ffffffff8152fc10-ffffffff8152fc87: update_domain.part.19 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff815835ba)
Location: drivers/iommu/amd_iommu.c:2253
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81583450-ffffffff815834de: update_domain.part.16 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff815b08ca)
Location: drivers/iommu/amd_iommu.c:2346
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff815b0760-ffffffff815b07ee: update_domain.part.15 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff815c6d66)
Location: drivers/iommu/amd_iommu.c:2507
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff815c6770-ffffffff815c6805: update_domain.part.31 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff8162db36)
Location: drivers/iommu/amd_iommu.c:2288
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff8162d510-ffffffff8162d5a5: update_domain.part.29 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff8166879d)
Location: drivers/iommu/amd_iommu.c:2298
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81667fd0-ffffffff81668067: update_domain.part.32 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff8168639d)
Location: drivers/iommu/amd_iommu.c:2374
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81686230-ffffffff816862c7: update_domain.part.25 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816bdc5f)
Location: drivers/iommu/amd_iommu.c:2355
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816bdaf0-ffffffff816bdb87: update_domain.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0ce0)
Location: drivers/iommu/amd_iommu.c:2383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816e0ce0-ffffffff816e0d73: update_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798cd0)
Location: drivers/iommu/amd/iommu.c:2235
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
```
**Symbols:**

```
ffffffff81798cd0-ffffffff81798d71: update_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a7550)
Location: drivers/iommu/amd/iommu.c:2327
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
```
**Symbols:**

```
ffffffff817a7550-ffffffff817a75f1: update_domain (STB_LOCAL)
```
</details>
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
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6730)
Location: drivers/iommu/amd_iommu.c:2383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816a6730-ffffffff816a67c3: update_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684120)
Location: drivers/iommu/amd_iommu.c:2383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff81684120-ffffffff816841b3: update_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d49a0)
Location: drivers/iommu/amd_iommu.c:2383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816d49a0-ffffffff816d4a33: update_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_domain(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ef0a0)
Location: drivers/iommu/amd_iommu.c:2383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
**Symbols:**

```
ffffffff816ef0a0-ffffffff816ef133: update_domain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
