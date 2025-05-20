# Function: <code>__arm_lpae_map</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __arm_lpae_map(struct arm_lpae_io_pgtable *data, long unsigned int iova, phys_addr_t paddr, size_t size, arm_lpae_iopte prot, int lvl, arm_lpae_iopte *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cc4f8)
Location: drivers/iommu/io-pgtable-arm.c:382
Inline: False
Direct callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_map
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
**Symbols:**

```
ffff8000108cc4f8-ffff8000108cc730: __arm_lpae_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __arm_lpae_map(struct arm_lpae_io_pgtable *data, long unsigned int iova, phys_addr_t paddr, size_t size, arm_lpae_iopte prot, int lvl, arm_lpae_iopte *ptep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgtable-arm.c (c09c0d30)
Location: drivers/iommu/io-pgtable-arm.c:382
Inline: False
Direct callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_map
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
**Symbols:**

```
c09c0d30-c09c1070: __arm_lpae_map (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
