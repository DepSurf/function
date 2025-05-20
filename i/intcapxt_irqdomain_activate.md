# Function: <code>intcapxt_irqdomain_activate</code>

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
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a92e0)
Location: drivers/iommu/amd/init.c:2075
Inline: False
```
**Symbols:**

```
ffffffff817a92e0-ffffffff817a9364: intcapxt_irqdomain_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178afe0)
Location: drivers/iommu/amd/init.c:2028
Inline: False
```
**Symbols:**

```
ffffffff8178afe0-ffffffff8178b05a: intcapxt_irqdomain_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811c80)
Location: drivers/iommu/amd/init.c:2030
Inline: False
```
**Symbols:**

```
ffffffff81811c80-ffffffff81811c8d: intcapxt_irqdomain_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952a90)
Location: drivers/iommu/amd/init.c:2044
Inline: False
```
**Symbols:**

```
ffffffff81952a90-ffffffff81952aa1: intcapxt_irqdomain_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab7f50)
Location: drivers/iommu/amd/init.c:2248
Inline: False
```
**Symbols:**

```
ffffffff81ab7f50-ffffffff81ab7f61: intcapxt_irqdomain_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b042a0)
Location: drivers/iommu/amd/init.c:2285
Inline: False
```
**Symbols:**

```
ffffffff81b042a0-ffffffff81b042b1: intcapxt_irqdomain_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intcapxt_irqdomain_activate(struct irq_domain *domain, struct irq_data *irqd, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b57ea0)
Location: drivers/iommu/amd/init.c:2281
Inline: False
```
**Symbols:**

```
ffffffff81b57ea0-ffffffff81b57eb1: intcapxt_irqdomain_activate (STB_LOCAL)
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
