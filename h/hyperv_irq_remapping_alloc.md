# Function: <code>hyperv_irq_remapping_alloc</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816d03e8)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff816d03b0-ffffffff816d046a: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff816d0482-ffffffff816d048e: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816f4208)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff816f41d0-ffffffff816f428a: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff816f42a2-ffffffff816f42ae: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac8f8)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff817ac8c0-ffffffff817ac97a: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff817ac992-ffffffff817ac99e: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817c14f4)
Location: drivers/iommu/hyperv-iommu.c:64
Inline: True
```
**Symbols:**

```
ffffffff817c14c0-ffffffff817c156d: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff81c0d86f-ffffffff81c0d87b: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817a4a54)
Location: drivers/iommu/hyperv-iommu.c:65
Inline: True
```
**Symbols:**

```
ffffffff817a4a20-ffffffff817a4acd: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff81bffbde-ffffffff81bffbea: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff8182e264)
Location: drivers/iommu/hyperv-iommu.c:65
Inline: True
```
**Symbols:**

```
ffffffff8182e230-ffffffff8182e2dd: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff81d02157-ffffffff81d02163: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (0)
Location: drivers/iommu/hyperv-iommu.c:65
Inline: False
```
**Symbols:**

```
ffffffff8196ee00-ffffffff8196eebe: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff81eca626-ffffffff81eca632: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9a30)
Location: drivers/iommu/hyperv-iommu.c:65
Inline: False
```
**Symbols:**

```
ffffffff81ad9a30-ffffffff81ad9b41: hyperv_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27bb0)
Location: drivers/iommu/hyperv-iommu.c:65
Inline: False
```
**Symbols:**

```
ffffffff81b27bb0-ffffffff81b27cc1: hyperv_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7ea70)
Location: drivers/iommu/hyperv-iommu.c:65
Inline: False
```
**Symbols:**

```
ffffffff81b7ea70-ffffffff81b7eb81: hyperv_irq_remapping_alloc (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816b99f8)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff816b99c0-ffffffff816b9a7a: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff816b9a92-ffffffff816b9a9e: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81697638)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff81697600-ffffffff816976ba: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff816976d2-ffffffff816976de: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7ec8)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff816e7e90-ffffffff816e7f4a: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff816e7f62-ffffffff816e7f6e: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hyperv_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817025c8)
Location: drivers/iommu/hyperv-iommu.c:68
Inline: True
```
**Symbols:**

```
ffffffff81702590-ffffffff8170264a: hyperv_irq_remapping_alloc (STB_LOCAL)
ffffffff81702662-ffffffff8170266e: hyperv_irq_remapping_alloc.cold (STB_LOCAL)
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
