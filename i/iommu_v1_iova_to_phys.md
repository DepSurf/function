# Function: <code>iommu_v1_iova_to_phys</code>

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
phys_addr_t iommu_v1_iova_to_phys(struct io_pgtable_ops *ops, long unsigned int iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c1c0)
Location: drivers/iommu/amd/io_pgtable.c:490
Inline: False
```
**Symbols:**

```
ffffffff8178c1c0-ffffffff8178c25d: iommu_v1_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t iommu_v1_iova_to_phys(struct io_pgtable_ops *ops, long unsigned int iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff818134d0)
Location: drivers/iommu/amd/io_pgtable.c:490
Inline: False
```
**Symbols:**

```
ffffffff818134d0-ffffffff8181355f: iommu_v1_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t iommu_v1_iova_to_phys(struct io_pgtable_ops *ops, long unsigned int iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff819544d0)
Location: drivers/iommu/amd/io_pgtable.c:464
Inline: False
```
**Symbols:**

```
ffffffff819544d0-ffffffff8195456b: iommu_v1_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t iommu_v1_iova_to_phys(struct io_pgtable_ops *ops, long unsigned int iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba2e0)
Location: drivers/iommu/amd/io_pgtable.c:472
Inline: False
```
**Symbols:**

```
ffffffff81aba2e0-ffffffff81aba37b: iommu_v1_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t iommu_v1_iova_to_phys(struct io_pgtable_ops *ops, long unsigned int iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b068a0)
Location: drivers/iommu/amd/io_pgtable.c:472
Inline: False
```
**Symbols:**

```
ffffffff81b068a0-ffffffff81b0693b: iommu_v1_iova_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t iommu_v1_iova_to_phys(struct io_pgtable_ops *ops, long unsigned int iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a6c0)
Location: drivers/iommu/amd/io_pgtable.c:473
Inline: False
```
**Symbols:**

```
ffffffff81b5a6c0-ffffffff81b5a75b: iommu_v1_iova_to_phys (STB_LOCAL)
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
