# Function: <code>has_iova_flush_queue</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ba135)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816bad30-ffffffff816bad43: has_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dcf45)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816ddb90-ffffffff816ddba3: has_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81793a45)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff81794850-ffffffff81794863: has_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0595)
Location: drivers/iommu/iova.c:58
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff817c10a0-ffffffff817c10b3: has_iova_flush_queue (STB_GLOBAL)
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
In drivers/iommu/iova.c (ffffffff817a3658)
Location: drivers/iommu/iova.c:76
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (ffffffff8182c88c)
Location: drivers/iommu/iova.c:76
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108ccc4c)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffff8000108ce110-ffff8000108ce140: has_iova_flush_queue (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a2995)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816a35e0-ffffffff816a35f3: has_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680385)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff81680fd0-ffffffff81680fe3: has_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d0c05)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816d1850-ffffffff816d1863: has_iova_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool has_iova_flush_queue(struct iova_domain *iovad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eb365)
Location: drivers/iommu/iova.c:57
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
```
**Symbols:**

```
ffffffff816ebe10-ffffffff816ebe23: has_iova_flush_queue (STB_GLOBAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
