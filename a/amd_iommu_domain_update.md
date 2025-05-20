# Function: <code>amd_iommu_domain_update</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_iommu_domain_update(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178a7d0)
Location: drivers/iommu/amd/iommu.c:1765
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
```
**Symbols:**

```
ffffffff8178a7d0-ffffffff8178a82c: amd_iommu_domain_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_iommu_domain_update(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81811ab0)
Location: drivers/iommu/amd/iommu.c:1809
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
**Symbols:**

```
ffffffff81811ab0-ffffffff81811b07: amd_iommu_domain_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_iommu_domain_update(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81952850)
Location: drivers/iommu/amd/iommu.c:1831
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
**Symbols:**

```
ffffffff81952850-ffffffff819528f7: amd_iommu_domain_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_iommu_domain_update(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab7a90)
Location: drivers/iommu/amd/iommu.c:1955
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_free_pgtable
```
**Symbols:**

```
ffffffff81ab7a90-ffffffff81ab7b37: amd_iommu_domain_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_iommu_domain_update(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b03ce0)
Location: drivers/iommu/amd/iommu.c:1980
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_free_pgtable
```
**Symbols:**

```
ffffffff81b03ce0-ffffffff81b03daf: amd_iommu_domain_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_update(struct protection_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b575a5)
Location: drivers/iommu/amd/iommu.c:2028
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
Direct callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_free_pgtable
```
**Symbols:**

```
ffffffff81b57970-ffffffff81b579cb: amd_iommu_domain_update (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
