# Function: <code>remove_iova</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182c3b0)
Location: drivers/iommu/iova.c:412
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
```
**Symbols:**

```
ffffffff8182c3b0-ffffffff8182c433: remove_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8196d700)
Location: drivers/iommu/iova.c:353
Inline: False
Direct callers:
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
```
**Symbols:**

```
ffffffff8196d700-ffffffff8196d79f: remove_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81ad7fb0)
Location: drivers/iommu/iova.c:358
Inline: False
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
```
**Symbols:**

```
ffffffff81ad7fb0-ffffffff81ad804f: remove_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b25ef0)
Location: drivers/iommu/iova.c:358
Inline: False
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
```
**Symbols:**

```
ffffffff81b25ef0-ffffffff81b25f8f: remove_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_iova(struct iova_domain *iovad, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b7cd20)
Location: drivers/iommu/iova.c:359
Inline: False
Direct callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:__free_iova
```
**Symbols:**

```
ffffffff81b7cd20-ffffffff81b7cdbf: remove_iova (STB_LOCAL)
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
