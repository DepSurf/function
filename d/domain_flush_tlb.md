# Function: <code>domain_flush_tlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81530ef3)
Location: drivers/iommu/amd_iommu.c:1077
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81582ffc)
Location: drivers/iommu/amd_iommu.c:1173
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__queue_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b032c)
Location: drivers/iommu/amd_iommu.c:1262
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__queue_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5565)
Location: drivers/iommu/amd_iommu.c:1321
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb
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
Location: drivers/iommu/amd_iommu.c:1262
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
In drivers/iommu/amd_iommu.c (ffffffff816677df)
Location: drivers/iommu/amd_iommu.c:1268
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
In drivers/iommu/amd_iommu.c (ffffffff816869ff)
Location: drivers/iommu/amd_iommu.c:1283
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
In drivers/iommu/amd_iommu.c (ffffffff816be260)
Location: drivers/iommu/amd_iommu.c:1282
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
In drivers/iommu/amd_iommu.c (ffffffff816e168c)
Location: drivers/iommu/amd_iommu.c:1304
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
In drivers/iommu/amd_iommu.c (ffffffff816a70dc)
Location: drivers/iommu/amd_iommu.c:1304
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
In drivers/iommu/amd_iommu.c (ffffffff81684acc)
Location: drivers/iommu/amd_iommu.c:1304
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
In drivers/iommu/amd_iommu.c (ffffffff816d534c)
Location: drivers/iommu/amd_iommu.c:1304
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
In drivers/iommu/amd_iommu.c (ffffffff816efc8c)
Location: drivers/iommu/amd_iommu.c:1304
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iova_domain_flush_tlb
```
</details>
</li>
</ul>

## Differences
