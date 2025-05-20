# Function: <code>free_io_pgtable_ops</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff817a2870)
Location: drivers/iommu/io-pgtable.c:62
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff817a2870-ffffffff817a28bf: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff8182bb90)
Location: drivers/iommu/io-pgtable.c:63
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff8182bb90-ffffffff8182bbf6: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff8196ce70)
Location: drivers/iommu/io-pgtable.c:63
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff8196ce70-ffffffff8196ceea: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff81ad75b0)
Location: drivers/iommu/io-pgtable.c:67
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81ad75b0-ffffffff81ad762a: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff81b25d90)
Location: drivers/iommu/io-pgtable.c:67
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81b25d90-ffffffff81b25e0a: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff81b7cbc0)
Location: drivers/iommu/io-pgtable.c:90
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff81b7cbc0-ffffffff81b7cc3a: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffff8000108cad98)
Location: drivers/iommu/io-pgtable.c:59
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_free
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
```
**Symbols:**

```
ffff8000108cad98-ffff8000108cadec: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_io_pgtable_ops(struct io_pgtable_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (c09bf9e0)
Location: drivers/iommu/io-pgtable.c:59
Inline: False
Direct callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_free
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
```
**Symbols:**

```
c09bf9e0-c09bfa2c: free_io_pgtable_ops (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
