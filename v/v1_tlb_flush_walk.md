# Function: <code>v1_tlb_flush_walk</code>

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
void v1_tlb_flush_walk(long unsigned int iova, size_t size, size_t granule, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178bc60)
Location: drivers/iommu/amd/io_pgtable.c:30
Inline: False
```
**Symbols:**

```
ffffffff8178bc60-ffffffff8178bc6b: v1_tlb_flush_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void v1_tlb_flush_walk(long unsigned int iova, size_t size, size_t granule, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81813250)
Location: drivers/iommu/amd/io_pgtable.c:30
Inline: False
```
**Symbols:**

```
ffffffff81813250-ffffffff8181325b: v1_tlb_flush_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void v1_tlb_flush_walk(long unsigned int iova, size_t size, size_t granule, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954230)
Location: drivers/iommu/amd/io_pgtable.c:30
Inline: False
```
**Symbols:**

```
ffffffff81954230-ffffffff8195423f: v1_tlb_flush_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void v1_tlb_flush_walk(long unsigned int iova, size_t size, size_t granule, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81ab9ff0)
Location: drivers/iommu/amd/io_pgtable.c:30
Inline: False
```
**Symbols:**

```
ffffffff81ab9ff0-ffffffff81ab9fff: v1_tlb_flush_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void v1_tlb_flush_walk(long unsigned int iova, size_t size, size_t granule, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06590)
Location: drivers/iommu/amd/io_pgtable.c:30
Inline: False
```
**Symbols:**

```
ffffffff81b06590-ffffffff81b0659f: v1_tlb_flush_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void v1_tlb_flush_walk(long unsigned int iova, size_t size, size_t granule, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a3a0)
Location: drivers/iommu/amd/io_pgtable.c:30
Inline: False
```
**Symbols:**

```
ffffffff81b5a3a0-ffffffff81b5a3af: v1_tlb_flush_walk (STB_LOCAL)
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
