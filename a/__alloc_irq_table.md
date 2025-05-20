# Function: <code>__alloc_irq_table</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667a9e)
Location: drivers/iommu/amd_iommu.c:3627
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685fbe)
Location: drivers/iommu/amd_iommu.c:3692
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bd71e)
Location: drivers/iommu/amd_iommu.c:3673
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e07b6)
Location: drivers/iommu/amd_iommu.c:3709
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_remap_table *__alloc_irq_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795bc0)
Location: drivers/iommu/amd/iommu.c:3125
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81795bc0-ffffffff81795c56: __alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_remap_table *__alloc_irq_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a42e0)
Location: drivers/iommu/amd/iommu.c:3216
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff817a42e0-ffffffff817a4376: __alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81788426)
Location: drivers/iommu/amd/iommu.c:2582
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180fd6d)
Location: drivers/iommu/amd/iommu.c:2650
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194f04a)
Location: drivers/iommu/amd/iommu.c:2676
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab4199)
Location: drivers/iommu/amd/iommu.c:2844
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_remap_table *__alloc_irq_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81affba0)
Location: drivers/iommu/amd/iommu.c:2890
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81affba0-ffffffff81affc4d: __alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_remap_table *__alloc_irq_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b530b0)
Location: drivers/iommu/amd/iommu.c:2929
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81b530b0-ffffffff81b5318c: __alloc_irq_table (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6206)
Location: drivers/iommu/amd_iommu.c:3709
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683bf6)
Location: drivers/iommu/amd_iommu.c:3709
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d4476)
Location: drivers/iommu/amd_iommu.c:3709
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eeb76)
Location: drivers/iommu/amd_iommu.c:3709
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
