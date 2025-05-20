# Function: <code>intcapxt_irqdomain_deactivate</code>

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
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a8cc0)
Location: drivers/iommu/amd/init.c:2098
Inline: False
```
**Symbols:**

```
ffffffff817a8cc0-ffffffff817a8ccb: intcapxt_irqdomain_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178aa40)
Location: drivers/iommu/amd/init.c:2051
Inline: False
```
**Symbols:**

```
ffffffff8178aa40-ffffffff8178aa4b: intcapxt_irqdomain_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811c90)
Location: drivers/iommu/amd/init.c:2036
Inline: False
```
**Symbols:**

```
ffffffff81811c90-ffffffff81811c9b: intcapxt_irqdomain_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952ab0)
Location: drivers/iommu/amd/init.c:2050
Inline: False
```
**Symbols:**

```
ffffffff81952ab0-ffffffff81952abf: intcapxt_irqdomain_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab7f80)
Location: drivers/iommu/amd/init.c:2254
Inline: False
```
**Symbols:**

```
ffffffff81ab7f80-ffffffff81ab7f8f: intcapxt_irqdomain_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b042d0)
Location: drivers/iommu/amd/init.c:2291
Inline: False
```
**Symbols:**

```
ffffffff81b042d0-ffffffff81b042df: intcapxt_irqdomain_deactivate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intcapxt_irqdomain_deactivate(struct irq_domain *domain, struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b57ed0)
Location: drivers/iommu/amd/init.c:2287
Inline: False
```
**Symbols:**

```
ffffffff81b57ed0-ffffffff81b57edf: intcapxt_irqdomain_deactivate (STB_LOCAL)
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
