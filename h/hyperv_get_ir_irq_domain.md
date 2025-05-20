# Function: <code>hyperv_get_ir_irq_domain</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816d02c0)
Location: drivers/iommu/hyperv-iommu.c:182
Inline: False
```
**Symbols:**

```
ffffffff816d02c0-ffffffff816d02db: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816f40e0)
Location: drivers/iommu/hyperv-iommu.c:182
Inline: False
```
**Symbols:**

```
ffffffff816f40e0-ffffffff816f40fb: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac7d0)
Location: drivers/iommu/hyperv-iommu.c:185
Inline: False
```
**Symbols:**

```
ffffffff817ac7d0-ffffffff817ac7eb: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816b98d0)
Location: drivers/iommu/hyperv-iommu.c:182
Inline: False
```
**Symbols:**

```
ffffffff816b98d0-ffffffff816b98eb: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81697510)
Location: drivers/iommu/hyperv-iommu.c:182
Inline: False
```
**Symbols:**

```
ffffffff81697510-ffffffff8169752b: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7da0)
Location: drivers/iommu/hyperv-iommu.c:182
Inline: False
```
**Symbols:**

```
ffffffff816e7da0-ffffffff816e7dbb: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *hyperv_get_ir_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817024a0)
Location: drivers/iommu/hyperv-iommu.c:182
Inline: False
```
**Symbols:**

```
ffffffff817024a0-ffffffff817024bb: hyperv_get_ir_irq_domain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
