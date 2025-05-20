# Function: <code>hyperv_irq_remapping_activate</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816d02e0)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff816d02e0-ffffffff816d0308: hyperv_irq_remapping_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816f4100)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff816f4100-ffffffff816f4128: hyperv_irq_remapping_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac7f0)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff817ac7f0-ffffffff817ac81b: hyperv_irq_remapping_activate (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816b98f0)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff816b98f0-ffffffff816b9918: hyperv_irq_remapping_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81697530)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff81697530-ffffffff81697558: hyperv_irq_remapping_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7dc0)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff816e7dc0-ffffffff816e7de8: hyperv_irq_remapping_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hyperv_irq_remapping_activate(struct irq_domain *domain, struct irq_data *irq_data, bool reserve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817024c0)
Location: drivers/iommu/hyperv-iommu.c:122
Inline: False
```
**Symbols:**

```
ffffffff817024c0-ffffffff817024e8: hyperv_irq_remapping_activate (STB_LOCAL)
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
