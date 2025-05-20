# Function: <code>dma_ops_domain_flush_tlb</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_ops_domain_flush_tlb(struct dma_ops_domain *dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5550)
Location: drivers/iommu/amd_iommu.c:1846
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:queue_flush_timeout
```
**Symbols:**

```
ffffffff815c5550-ffffffff815c558b: dma_ops_domain_flush_tlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c2a6)
Location: drivers/iommu/amd_iommu.c:1733
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816677c5)
Location: drivers/iommu/amd_iommu.c:1736
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816869e5)
Location: drivers/iommu/amd_iommu.c:1817
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be245)
Location: drivers/iommu/amd_iommu.c:1807
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1655)
Location: drivers/iommu/amd_iommu.c:1867
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a70a5)
Location: drivers/iommu/amd_iommu.c:1867
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684a95)
Location: drivers/iommu/amd_iommu.c:1867
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5315)
Location: drivers/iommu/amd_iommu.c:1867
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816efc55)
Location: drivers/iommu/amd_iommu.c:1867
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
