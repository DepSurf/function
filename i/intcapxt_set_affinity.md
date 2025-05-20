# Function: <code>intcapxt_set_affinity</code>

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
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9630)
Location: drivers/iommu/amd/init.c:2135
Inline: True
```
**Symbols:**

```
ffffffff817a9630-ffffffff817a9670: intcapxt_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b1c0)
Location: drivers/iommu/amd/init.c:2088
Inline: True
```
**Symbols:**

```
ffffffff8178b1c0-ffffffff8178b200: intcapxt_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811ce0)
Location: drivers/iommu/amd/init.c:2104
Inline: False
```
**Symbols:**

```
ffffffff81811ce0-ffffffff81811d0b: intcapxt_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952b10)
Location: drivers/iommu/amd/init.c:2118
Inline: False
```
**Symbols:**

```
ffffffff81952b10-ffffffff81952b45: intcapxt_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab8000)
Location: drivers/iommu/amd/init.c:2322
Inline: False
```
**Symbols:**

```
ffffffff81ab8000-ffffffff81ab8035: intcapxt_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b04350)
Location: drivers/iommu/amd/init.c:2359
Inline: False
```
**Symbols:**

```
ffffffff81b04350-ffffffff81b04385: intcapxt_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intcapxt_set_affinity(struct irq_data *irqd, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b57f30)
Location: drivers/iommu/amd/init.c:2348
Inline: False
```
**Symbols:**

```
ffffffff81b57f30-ffffffff81b57f65: intcapxt_set_affinity (STB_LOCAL)
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
