# Function: <code>intcapxt_unmask_irq</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intcapxt_unmask_irq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a8cb0)
Location: drivers/iommu/amd/init.c:2065
Inline: True
```
**Symbols:**

```
ffffffff817a8cb0-ffffffff817a8cbb: intcapxt_unmask_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intcapxt_unmask_irq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178aa30)
Location: drivers/iommu/amd/init.c:2018
Inline: True
```
**Symbols:**

```
ffffffff8178aa30-ffffffff8178aa3b: intcapxt_unmask_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intcapxt_unmask_irq(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2073
Inline: False
```
**Symbols:**

```
ffffffff81812060-ffffffff818120ef: intcapxt_unmask_irq (STB_LOCAL)
ffffffff81cfe83f-ffffffff81cfe85b: intcapxt_unmask_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intcapxt_unmask_irq(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2087
Inline: False
```
**Symbols:**

```
ffffffff81952f40-ffffffff81952fdd: intcapxt_unmask_irq (STB_LOCAL)
ffffffff81ec708b-ffffffff81ec70a7: intcapxt_unmask_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intcapxt_unmask_irq(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2291
Inline: False
```
**Symbols:**

```
ffffffff81ab8810-ffffffff81ab88ad: intcapxt_unmask_irq (STB_LOCAL)
ffffffff820970d3-ffffffff820970ef: intcapxt_unmask_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intcapxt_unmask_irq(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2328
Inline: False
```
**Symbols:**

```
ffffffff81b04b80-ffffffff81b04c1d: intcapxt_unmask_irq (STB_LOCAL)
ffffffff82117ff4-ffffffff82118010: intcapxt_unmask_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intcapxt_unmask_irq(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58570)
Location: drivers/iommu/amd/init.c:2325
Inline: False
```
**Symbols:**

```
ffffffff81b58570-ffffffff81b585e8: intcapxt_unmask_irq (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_data *irqd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_data *data</code>
</li>
</ul>
</details>
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
