# Function: <code>irq_remapping_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81531b70)
Location: drivers/iommu/amd_iommu.c:3833
Inline: False
```
**Symbols:**

```
ffffffff81531b70-ffffffff81531f25: irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81585cf0)
Location: drivers/iommu/amd_iommu.c:3848
Inline: False
```
**Symbols:**

```
ffffffff81585cf0-ffffffff81586095: irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b30c0)
Location: drivers/iommu/amd_iommu.c:4137
Inline: False
```
**Symbols:**

```
ffffffff815b30c0-ffffffff815b355d: irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c8890)
Location: drivers/iommu/amd_iommu.c:4275
Inline: False
```
**Symbols:**

```
ffffffff815c8890-ffffffff815c8d48: irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162f200)
Location: drivers/iommu/amd_iommu.c:4068
Inline: False
```
**Symbols:**

```
ffffffff8162f200-ffffffff8162f74e: irq_remapping_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4126
Inline: False
```
**Symbols:**

```
ffffffff816699f0-ffffffff81669f3a: irq_remapping_alloc (STB_LOCAL)
ffffffff8166b5c5-ffffffff8166b5d1: irq_remapping_alloc.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4195
Inline: False
```
**Symbols:**

```
ffffffff816885c0-ffffffff81688b0a: irq_remapping_alloc (STB_LOCAL)
ffffffff81689e19-ffffffff81689e25: irq_remapping_alloc.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4176
Inline: False
```
**Symbols:**

```
ffffffff816bfb70-ffffffff816c00c9: irq_remapping_alloc (STB_LOCAL)
ffffffff816c1405-ffffffff816c1424: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4231
Inline: False
```
**Symbols:**

```
ffffffff816e2d20-ffffffff816e30f9: irq_remapping_alloc (STB_LOCAL)
ffffffff816e4366-ffffffff816e4382: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3656
Inline: False
```
**Symbols:**

```
ffffffff817985d0-ffffffff817988e8: irq_remapping_alloc (STB_LOCAL)
ffffffff8179a84b-ffffffff8179a867: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3685
Inline: False
```
**Symbols:**

```
ffffffff817a6c60-ffffffff817a712f: irq_remapping_alloc (STB_LOCAL)
ffffffff81c0b715-ffffffff81c0b731: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3051
Inline: False
```
**Symbols:**

```
ffffffff817886f0-ffffffff81788bc0: irq_remapping_alloc (STB_LOCAL)
ffffffff81bfd1b0-ffffffff81bfd1cc: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3119
Inline: False
```
**Symbols:**

```
ffffffff81810020-ffffffff81810500: irq_remapping_alloc (STB_LOCAL)
ffffffff81cfe248-ffffffff81cfe29c: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3145
Inline: False
```
**Symbols:**

```
ffffffff819504d0-ffffffff819509c2: irq_remapping_alloc (STB_LOCAL)
ffffffff81ec6aad-ffffffff81ec6af9: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3300
Inline: False
```
**Symbols:**

```
ffffffff81ab5ad0-ffffffff81ab6027: irq_remapping_alloc (STB_LOCAL)
ffffffff82096f01-ffffffff82096f31: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3338
Inline: False
```
**Symbols:**

```
ffffffff81b01fa0-ffffffff81b024f4: irq_remapping_alloc (STB_LOCAL)
ffffffff82117de7-ffffffff82117e17: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b55910)
Location: drivers/iommu/amd/iommu.c:3389
Inline: False
```
**Symbols:**

```
ffffffff81b55910-ffffffff81b55f39: irq_remapping_alloc (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4231
Inline: False
```
**Symbols:**

```
ffffffff816a8770-ffffffff816a8b49: irq_remapping_alloc (STB_LOCAL)
ffffffff816a9e46-ffffffff816a9e62: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4231
Inline: False
```
**Symbols:**

```
ffffffff81686160-ffffffff81686539: irq_remapping_alloc (STB_LOCAL)
ffffffff816877a6-ffffffff816877c2: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4231
Inline: False
```
**Symbols:**

```
ffffffff816d69e0-ffffffff816d6db9: irq_remapping_alloc (STB_LOCAL)
ffffffff816d8026-ffffffff816d8042: irq_remapping_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int irq_remapping_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:4231
Inline: False
```
**Symbols:**

```
ffffffff816f0f90-ffffffff816f1369: irq_remapping_alloc (STB_LOCAL)
ffffffff816f25d6-ffffffff816f25f2: irq_remapping_alloc.cold (STB_LOCAL)
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
