# Function: <code>interleave_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int interleave_nodes(struct mempolicy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811dfc20)
Location: mm/mempolicy.c:1673
Inline: False
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:alloc_pages_vma
```
**Symbols:**

```
ffffffff811dfc20-ffffffff811dfca5: interleave_nodes (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff811feabc)
Location: mm/mempolicy.c:1705
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff812102fc)
Location: mm/mempolicy.c:1699
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff8121aef2)
Location: mm/mempolicy.c:1624
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff81236112)
Location: mm/mempolicy.c:1681
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff812590ea)
Location: mm/mempolicy.c:1738
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff8126d4ea)
Location: mm/mempolicy.c:1778
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff81288951)
Location: mm/mempolicy.c:1824
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff812984c1)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ccc91)
Location: mm/mempolicy.c:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dae71)
Location: mm/mempolicy.c:1898
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff812e26d1)
Location: mm/mempolicy.c:1912
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff81329967)
Location: mm/mempolicy.c:1808
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff81399501)
Location: mm/mempolicy.c:1877
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int interleave_nodes(struct mempolicy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81415160)
Location: mm/mempolicy.c:1892
Inline: False
Direct callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
**Symbols:**

```
ffffffff81415160-ffffffff814151e4: interleave_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int interleave_nodes(struct mempolicy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81448740)
Location: mm/mempolicy.c:1903
Inline: False
Direct callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
**Symbols:**

```
ffffffff81448740-ffffffff814487b8: interleave_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int interleave_nodes(struct mempolicy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81481fa0)
Location: mm/mempolicy.c:1829
Inline: False
Direct callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:mempolicy_slab_node
```
**Symbols:**

```
ffffffff81481fa0-ffffffff8148201c: interleave_nodes (STB_LOCAL)
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
In mm/mempolicy.c (ffff8000103384c0)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000411a10)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
</details>
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
In mm/mempolicy.c (ffffffff81290aa1)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff81282721)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff8128e8b1)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
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
In mm/mempolicy.c (ffffffff8129e7b1)
Location: mm/mempolicy.c:1826
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
