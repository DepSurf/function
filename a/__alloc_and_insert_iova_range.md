# Function: <code>__alloc_and_insert_iova_range</code>

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
In drivers/iommu/iova.c (ffffffff8152ce65)
Location: drivers/iommu/iova.c:101
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff81580215)
Location: drivers/iommu/iova.c:113
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff815acda5)
Location: drivers/iommu/iova.c:113
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff815c2ad7)
Location: drivers/iommu/iova.c:142
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff81629634)
Location: drivers/iommu/iova.c:178
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff8166435a)
Location: drivers/iommu/iova.c:178
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff816828ea)
Location: drivers/iommu/iova.c:181
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff816ba01a)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff816dce2a)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81793860)
Location: drivers/iommu/iova.c:180
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81793860-ffffffff81793989: __alloc_and_insert_iova_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c02e0)
Location: drivers/iommu/iova.c:181
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff817c02e0-ffffffff817c0465: __alloc_and_insert_iova_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a33d0)
Location: drivers/iommu/iova.c:235
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff817a33d0-ffffffff817a3599: __alloc_and_insert_iova_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:232
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff8182c590-ffffffff8182c7c2: __alloc_and_insert_iova_range (STB_LOCAL)
ffffffff81d0207d-ffffffff81d0209d: __alloc_and_insert_iova_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:173
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff8196d890-ffffffff8196daf2: __alloc_and_insert_iova_range (STB_LOCAL)
ffffffff81eca587-ffffffff81eca5a6: __alloc_and_insert_iova_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:178
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81ad8180-ffffffff81ad83e0: __alloc_and_insert_iova_range (STB_LOCAL)
ffffffff82098101-ffffffff82098121: __alloc_and_insert_iova_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:178
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81b260c0-ffffffff81b26320: __alloc_and_insert_iova_range (STB_LOCAL)
ffffffff821190f0-ffffffff82119110: __alloc_and_insert_iova_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __alloc_and_insert_iova_range(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, struct iova *new, bool size_aligned);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:179
Inline: False
Direct callers:
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81b7cef0-ffffffff81b7d150: __alloc_and_insert_iova_range (STB_LOCAL)
ffffffff821f70cc-ffffffff821f70ec: __alloc_and_insert_iova_range.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cdd2c)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
</details>
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
In drivers/iommu/iova.c (ffffffff816a287a)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff8168026a)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff816d0aea)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
In drivers/iommu/iova.c (ffffffff816eb24a)
Location: drivers/iommu/iova.c:180
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
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
