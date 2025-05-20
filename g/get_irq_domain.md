# Function: <code>get_irq_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152d820)
Location: drivers/iommu/amd_iommu.c:3748
Inline: False
```
**Symbols:**

```
ffffffff8152d820-ffffffff8152d86e: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815842d0)
Location: drivers/iommu/amd_iommu.c:3762
Inline: False
```
**Symbols:**

```
ffffffff815842d0-ffffffff8158444a: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b1600)
Location: drivers/iommu/amd_iommu.c:4033
Inline: False
```
**Symbols:**

```
ffffffff815b1600-ffffffff815b177a: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c8030)
Location: drivers/iommu/amd_iommu.c:4171
Inline: False
```
**Symbols:**

```
ffffffff815c8030-ffffffff815c8180: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162e9f0)
Location: drivers/iommu/amd_iommu.c:3964
Inline: False
```
**Symbols:**

```
ffffffff8162e9f0-ffffffff8162eb30: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816696d0)
Location: drivers/iommu/amd_iommu.c:4022
Inline: True
```
**Symbols:**

```
ffffffff816696d0-ffffffff8166980b: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816882f0)
Location: drivers/iommu/amd_iommu.c:4091
Inline: True
```
**Symbols:**

```
ffffffff816882f0-ffffffff816883f8: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bf880)
Location: drivers/iommu/amd_iommu.c:4072
Inline: True
```
**Symbols:**

```
ffffffff816bf880-ffffffff816bf988: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e2a30)
Location: drivers/iommu/amd_iommu.c:4127
Inline: True
```
**Symbols:**

```
ffffffff816e2a30-ffffffff816e2b38: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797460)
Location: drivers/iommu/amd/iommu.c:3552
Inline: True
```
**Symbols:**

```
ffffffff81797460-ffffffff81797544: get_irq_domain (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a8480)
Location: drivers/iommu/amd_iommu.c:4127
Inline: True
```
**Symbols:**

```
ffffffff816a8480-ffffffff816a8588: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685e70)
Location: drivers/iommu/amd_iommu.c:4127
Inline: True
```
**Symbols:**

```
ffffffff81685e70-ffffffff81685f78: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d66f0)
Location: drivers/iommu/amd_iommu.c:4127
Inline: True
```
**Symbols:**

```
ffffffff816d66f0-ffffffff816d67f8: get_irq_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *get_irq_domain(struct irq_alloc_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f0ca0)
Location: drivers/iommu/amd_iommu.c:4127
Inline: True
```
**Symbols:**

```
ffffffff816f0ca0-ffffffff816f0da8: get_irq_domain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
