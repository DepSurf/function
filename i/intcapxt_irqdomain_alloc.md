# Function: <code>intcapxt_irqdomain_alloc</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9380)
Location: drivers/iommu/amd/init.c:2105
Inline: False
```
**Symbols:**

```
ffffffff817a9380-ffffffff817a940b: intcapxt_irqdomain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b070)
Location: drivers/iommu/amd/init.c:2058
Inline: False
```
**Symbols:**

```
ffffffff8178b070-ffffffff8178b0fb: intcapxt_irqdomain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811e40)
Location: drivers/iommu/amd/init.c:2042
Inline: False
```
**Symbols:**

```
ffffffff81811e40-ffffffff81811ecb: intcapxt_irqdomain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952cc0)
Location: drivers/iommu/amd/init.c:2056
Inline: False
```
**Symbols:**

```
ffffffff81952cc0-ffffffff81952d57: intcapxt_irqdomain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab8580)
Location: drivers/iommu/amd/init.c:2260
Inline: False
```
**Symbols:**

```
ffffffff81ab8580-ffffffff81ab8617: intcapxt_irqdomain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b048d0)
Location: drivers/iommu/amd/init.c:2297
Inline: False
```
**Symbols:**

```
ffffffff81b048d0-ffffffff81b04967: intcapxt_irqdomain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intcapxt_irqdomain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b584c0)
Location: drivers/iommu/amd/init.c:2293
Inline: False
```
**Symbols:**

```
ffffffff81b584c0-ffffffff81b5855e: intcapxt_irqdomain_alloc (STB_LOCAL)
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
