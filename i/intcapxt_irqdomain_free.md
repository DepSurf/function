# Function: <code>intcapxt_irqdomain_free</code>

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
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9370)
Location: drivers/iommu/amd/init.c:2129
Inline: False
```
**Symbols:**

```
ffffffff817a9370-ffffffff817a9380: intcapxt_irqdomain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b060)
Location: drivers/iommu/amd/init.c:2082
Inline: False
```
**Symbols:**

```
ffffffff8178b060-ffffffff8178b070: intcapxt_irqdomain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811e30)
Location: drivers/iommu/amd/init.c:2066
Inline: False
```
**Symbols:**

```
ffffffff81811e30-ffffffff81811e40: intcapxt_irqdomain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952ca0)
Location: drivers/iommu/amd/init.c:2080
Inline: False
```
**Symbols:**

```
ffffffff81952ca0-ffffffff81952cba: intcapxt_irqdomain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab8550)
Location: drivers/iommu/amd/init.c:2284
Inline: False
```
**Symbols:**

```
ffffffff81ab8550-ffffffff81ab856a: intcapxt_irqdomain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b048a0)
Location: drivers/iommu/amd/init.c:2321
Inline: False
```
**Symbols:**

```
ffffffff81b048a0-ffffffff81b048ba: intcapxt_irqdomain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intcapxt_irqdomain_free(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58490)
Location: drivers/iommu/amd/init.c:2318
Inline: False
```
**Symbols:**

```
ffffffff81b58490-ffffffff81b584aa: intcapxt_irqdomain_free (STB_LOCAL)
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
