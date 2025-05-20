# Function: <code>dma_ops_domain_free</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8153156e)
Location: drivers/iommu/amd_iommu.c:1751
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_ops_domain_free(struct dma_ops_domain *dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81582d10)
Location: drivers/iommu/amd_iommu.c:1646
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81582d10-ffffffff81582d51: dma_ops_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_ops_domain_free(struct dma_ops_domain *dom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af120)
Location: drivers/iommu/amd_iommu.c:1736
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff815af120-ffffffff815af174: dma_ops_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6677)
Location: drivers/iommu/amd_iommu.c:1969
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff815c4ec0-ffffffff815c4f39: dma_ops_domain_free.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162d147)
Location: drivers/iommu/amd_iommu.c:1752
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8162bc30-ffffffff8162bc87: dma_ops_domain_free.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81668d60)
Location: drivers/iommu/amd_iommu.c:1755
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81668830-ffffffff81668887: dma_ops_domain_free.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168728a)
Location: drivers/iommu/amd_iommu.c:1836
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81687160-ffffffff816871b7: dma_ops_domain_free.part.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bea31)
Location: drivers/iommu/amd_iommu.c:1826
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816be910-ffffffff816be96a: dma_ops_domain_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1dde)
Location: drivers/iommu/amd_iommu.c:1890
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816e1ce0-ffffffff816e1d3a: dma_ops_domain_free.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a782e)
Location: drivers/iommu/amd_iommu.c:1890
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816a7730-ffffffff816a778a: dma_ops_domain_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168521e)
Location: drivers/iommu/amd_iommu.c:1890
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81685120-ffffffff8168517a: dma_ops_domain_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5a9e)
Location: drivers/iommu/amd_iommu.c:1890
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816d59a0-ffffffff816d59fa: dma_ops_domain_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ef93e)
Location: drivers/iommu/amd_iommu.c:1890
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816ed880-ffffffff816ed8da: dma_ops_domain_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
