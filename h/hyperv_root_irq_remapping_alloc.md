# Function: <code>hyperv_root_irq_remapping_alloc</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817a48c0)
Location: drivers/iommu/hyperv-iommu.c:269
Inline: True
```
**Symbols:**

```
ffffffff817a48c0-ffffffff817a4991: hyperv_root_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff8182e0d0)
Location: drivers/iommu/hyperv-iommu.c:269
Inline: True
```
**Symbols:**

```
ffffffff8182e0d0-ffffffff8182e1a1: hyperv_root_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff8196ec90)
Location: drivers/iommu/hyperv-iommu.c:269
Inline: False
```
**Symbols:**

```
ffffffff8196ec90-ffffffff8196ed7a: hyperv_root_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9680)
Location: drivers/iommu/hyperv-iommu.c:272
Inline: False
```
**Symbols:**

```
ffffffff81ad9680-ffffffff81ad976a: hyperv_root_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27800)
Location: drivers/iommu/hyperv-iommu.c:272
Inline: False
```
**Symbols:**

```
ffffffff81b27800-ffffffff81b278ea: hyperv_root_irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hyperv_root_irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e690)
Location: drivers/iommu/hyperv-iommu.c:272
Inline: False
```
**Symbols:**

```
ffffffff81b7e690-ffffffff81b7e7a9: hyperv_root_irq_remapping_alloc (STB_LOCAL)
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
