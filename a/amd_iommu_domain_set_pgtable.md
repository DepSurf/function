# Function: <code>amd_iommu_domain_set_pgtable</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4dea)
Location: drivers/iommu/amd/iommu.c:173
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:increase_address_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain *domain, u64 *root, int mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178bee5)
Location: drivers/iommu/amd/io_pgtable.c:160
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8178caf0-ffffffff8178cb21: amd_iommu_domain_set_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain *domain, u64 *root, int mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff818137c5)
Location: drivers/iommu/amd/io_pgtable.c:160
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff818141c0-ffffffff818141f1: amd_iommu_domain_set_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain *domain, u64 *root, int mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff819547ae)
Location: drivers/iommu/amd/io_pgtable.c:134
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81954ff0-ffffffff8195502d: amd_iommu_domain_set_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain *domain, u64 *root, int mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba5fe)
Location: drivers/iommu/amd/io_pgtable.c:134
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81abaf30-ffffffff81abaf6d: amd_iommu_domain_set_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain *domain, u64 *root, int mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06bf1)
Location: drivers/iommu/amd/io_pgtable.c:134
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b07640-ffffffff81b0767d: amd_iommu_domain_set_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain *domain, u64 *root, int mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5abd1)
Location: drivers/iommu/amd/io_pgtable.c:134
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b5b650-ffffffff81b5b682: amd_iommu_domain_set_pgtable (STB_GLOBAL)
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
