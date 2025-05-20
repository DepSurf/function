# Function: <code>free_iova_rcaches</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580a5b)
Location: drivers/iommu/iova.c:885
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (ffffffff815ad40b)
Location: drivers/iommu/iova.c:885
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (ffffffff815c301b)
Location: drivers/iommu/iova.c:857
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (ffffffff816293e8)
Location: drivers/iommu/iova.c:997
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:997
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1006
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1005
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1007
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_iova_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817936d0)
Location: drivers/iommu/iova.c:1009
Inline: False
Direct callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff817936d0-ffffffff8179377e: free_iova_rcaches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_iova_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817bff90)
Location: drivers/iommu/iova.c:983
Inline: False
Direct callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff817bff90-ffffffff817c003e: free_iova_rcaches (STB_LOCAL)
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1020
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1033
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_iova_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8196db00)
Location: drivers/iommu/iova.c:884
Inline: False
Direct callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff8196db00-ffffffff8196dc26: free_iova_rcaches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_iova_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81ad8530)
Location: drivers/iommu/iova.c:887
Inline: False
Direct callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff81ad8530-ffffffff81ad865f: free_iova_rcaches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_iova_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b26470)
Location: drivers/iommu/iova.c:893
Inline: False
Direct callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff81b26470-ffffffff81b2659f: free_iova_rcaches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_iova_rcaches(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81b7d2a0)
Location: drivers/iommu/iova.c:928
Inline: False
Direct callers:
  - drivers/iommu/iova.c:put_iova_domain
```
**Symbols:**

```
ffffffff81b7d2a0-ffffffff81b7d3b4: free_iova_rcaches (STB_LOCAL)
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1007
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1007
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1007
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1007
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:1007
Inline: True
Inline callers:
  - drivers/iommu/iova.c:put_iova_domain
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
