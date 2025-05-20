# Function: <code>amd_iommu_flush_iotlb_all</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667780)
Location: drivers/iommu/amd_iommu.c:3174
Inline: False
```
**Symbols:**

```
ffffffff81667780-ffffffff816677b2: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816869a0)
Location: drivers/iommu/amd_iommu.c:3240
Inline: False
```
**Symbols:**

```
ffffffff816869a0-ffffffff816869d2: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be200)
Location: drivers/iommu/amd_iommu.c:3221
Inline: False
```
**Symbols:**

```
ffffffff816be200-ffffffff816be234: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e15e0)
Location: drivers/iommu/amd_iommu.c:3256
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff816e15e0-ffffffff816e1636: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796d45)
Location: drivers/iommu/amd/iommu.c:2628
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff81796ce0-ffffffff81796d36: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5475)
Location: drivers/iommu/amd/iommu.c:2719
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff817a5410-ffffffff817a5466: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178a735)
Location: drivers/iommu/amd/iommu.c:2149
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff81789e80-ffffffff81789ed9: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81811220)
Location: drivers/iommu/amd/iommu.c:2210
Inline: False
```
**Symbols:**

```
ffffffff81811220-ffffffff81811274: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81950c70)
Location: drivers/iommu/amd/iommu.c:2227
Inline: False
```
**Symbols:**

```
ffffffff81950c70-ffffffff81950d29: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab6040)
Location: drivers/iommu/amd/iommu.c:2376
Inline: False
```
**Symbols:**

```
ffffffff81ab6040-ffffffff81ab60f9: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b019a0)
Location: drivers/iommu/amd/iommu.c:2397
Inline: False
```
**Symbols:**

```
ffffffff81b019a0-ffffffff81b01a90: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b570e0)
Location: drivers/iommu/amd/iommu.c:2566
Inline: False
```
**Symbols:**

```
ffffffff81b570e0-ffffffff81b57136: amd_iommu_flush_iotlb_all (STB_LOCAL)
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
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a7030)
Location: drivers/iommu/amd_iommu.c:3256
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff816a7030-ffffffff816a7086: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684a20)
Location: drivers/iommu/amd_iommu.c:3256
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff81684a20-ffffffff81684a76: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d52a0)
Location: drivers/iommu/amd_iommu.c:3256
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff816d52a0-ffffffff816d52f6: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void amd_iommu_flush_iotlb_all(struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816efbe0)
Location: drivers/iommu/amd_iommu.c:3256
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_iotlb_sync
```
**Symbols:**

```
ffffffff816efbe0-ffffffff816efc36: amd_iommu_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
