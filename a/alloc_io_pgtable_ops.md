# Function: <code>alloc_io_pgtable_ops</code>

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
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff817a27c0)
Location: drivers/iommu/io-pgtable.c:32
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff817a27c0-ffffffff817a2867: alloc_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff8182bab0)
Location: drivers/iommu/io-pgtable.c:33
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8182bab0-ffffffff8182bb86: alloc_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff8196cd70)
Location: drivers/iommu/io-pgtable.c:33
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8196cd70-ffffffff8196ce68: alloc_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff81ad74a0)
Location: drivers/iommu/io-pgtable.c:37
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81ad74a0-ffffffff81ad7598: alloc_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff81b25c80)
Location: drivers/iommu/io-pgtable.c:37
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b25c80-ffffffff81b25d78: alloc_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffffffff81b7ca40)
Location: drivers/iommu/io-pgtable.c:57
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b7ca40-ffffffff81b7cba6: alloc_io_pgtable_ops (STB_GLOBAL)
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
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (ffff8000108cace0)
Location: drivers/iommu/io-pgtable.c:29
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
```
**Symbols:**

```
ffff8000108cace0-ffff8000108cad98: alloc_io_pgtable_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct io_pgtable_ops *alloc_io_pgtable_ops(enum io_pgtable_fmt fmt, struct io_pgtable_cfg *cfg, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable.c (c09bf964)
Location: drivers/iommu/io-pgtable.c:29
Inline: False
Direct callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_attach_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
```
**Symbols:**

```
c09bf964-c09bf9e0: alloc_io_pgtable_ops (STB_GLOBAL)
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
