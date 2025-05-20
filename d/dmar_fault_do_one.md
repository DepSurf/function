# Function: <code>dmar_fault_do_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81532fdf)
Location: drivers/iommu/dmar.c:1567
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81587e87)
Location: drivers/iommu/dmar.c:1580
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b5547)
Location: drivers/iommu/dmar.c:1581
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cb3bd)
Location: drivers/iommu/dmar.c:1590
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8163218d)
Location: drivers/iommu/dmar.c:1593
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8166f24b)
Location: drivers/iommu/dmar.c:1593
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff8168d7ab)
Location: drivers/iommu/dmar.c:1624
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff816c519a)
Location: drivers/iommu/dmar.c:1613
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff816e80ca)
Location: drivers/iommu/dmar.c:1684
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179ecb5)
Location: drivers/iommu/intel/dmar.c:1800
Inline: True
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
```
**Symbols:**

```
ffffffff8179ecb5-ffffffff8179ed7c: dmar_fault_do_one.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81c0c0e0)
Location: drivers/iommu/intel/dmar.c:1837
Inline: True
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
```
**Symbols:**

```
ffffffff81c0c0e0-ffffffff81c0c1a7: dmar_fault_do_one.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/dmar.c (ffffffff81bfd937)
Location: drivers/iommu/intel/dmar.c:1906
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
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
In drivers/iommu/intel/dmar.c (ffffffff81814d0d)
Location: drivers/iommu/intel/dmar.c:1935
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
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
In drivers/iommu/intel/dmar.c (ffffffff81955f4f)
Location: drivers/iommu/intel/dmar.c:1931
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
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
In drivers/iommu/intel/dmar.c (ffffffff81abcaa0)
Location: drivers/iommu/intel/dmar.c:1920
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b093c8)
Location: drivers/iommu/intel/dmar.c:1943
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5d3e8)
Location: drivers/iommu/intel/dmar.c:1961
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff816adbaa)
Location: drivers/iommu/dmar.c:1684
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff8168b50a)
Location: drivers/iommu/dmar.c:1684
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff816dbd8a)
Location: drivers/iommu/dmar.c:1684
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
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
In drivers/iommu/dmar.c (ffffffff816f635a)
Location: drivers/iommu/dmar.c:1684
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
```
</details>
</li>
</ul>

## Differences
