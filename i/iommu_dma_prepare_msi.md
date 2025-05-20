# Function: <code>iommu_dma_prepare_msi</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81792bd0)
Location: drivers/iommu/dma-iommu.c:1203
Inline: False
```
**Symbols:**

```
ffffffff81792bd0-ffffffff81792c53: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bf5a0)
Location: drivers/iommu/dma-iommu.c:1381
Inline: False
```
**Symbols:**

```
ffffffff817bf5a0-ffffffff817bf623: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a2550)
Location: drivers/iommu/dma-iommu.c:1375
Inline: False
```
**Symbols:**

```
ffffffff817a2550-ffffffff817a2749: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182b840)
Location: drivers/iommu/dma-iommu.c:1393
Inline: False
```
**Symbols:**

```
ffffffff8182b840-ffffffff8182ba39: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196cb00)
Location: drivers/iommu/dma-iommu.c:1550
Inline: False
```
**Symbols:**

```
ffffffff8196cb00-ffffffff8196ccf5: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad7210)
Location: drivers/iommu/dma-iommu.c:1641
Inline: False
```
**Symbols:**

```
ffffffff81ad7210-ffffffff81ad7405: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b25a00)
Location: drivers/iommu/dma-iommu.c:1685
Inline: False
```
**Symbols:**

```
ffffffff81b25a00-ffffffff81b25bf0: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7c790)
Location: drivers/iommu/dma-iommu.c:1806
Inline: False
```
**Symbols:**

```
ffffffff81b7c790-ffffffff81b7c9af: iommu_dma_prepare_msi (STB_GLOBAL)
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
int iommu_dma_prepare_msi(struct msi_desc *desc, phys_addr_t msi_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108caa30)
Location: drivers/iommu/dma-iommu.c:1176
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
```
**Symbols:**

```
ffff8000108caa30-ffff8000108cac54: iommu_dma_prepare_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v2m.c (0)
Location: include/linux/dma-iommu.h:66
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (0)
Location: include/linux/dma-iommu.h:66
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/dma-iommu.h:66
Inline: True
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
