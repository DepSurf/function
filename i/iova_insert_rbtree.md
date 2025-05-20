# Function: <code>iova_insert_rbtree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152d180)
Location: drivers/iommu/iova.c:187
Inline: True
Direct callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff8152d180-ffffffff8152d1d7: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580510)
Location: drivers/iommu/iova.c:199
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
```
**Symbols:**

```
ffffffff81580510-ffffffff81580567: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad0b0)
Location: drivers/iommu/iova.c:199
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
```
**Symbols:**

```
ffffffff815ad0b0-ffffffff815ad107: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c2a10)
Location: drivers/iommu/iova.c:106
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff815c2a10-ffffffff815c2a81: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629570)
Location: drivers/iommu/iova.c:152
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81629570-ffffffff816295e1: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81664290)
Location: drivers/iommu/iova.c:152
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81664290-ffffffff81664301: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682560)
Location: drivers/iommu/iova.c:155
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81682560-ffffffff816825d1: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816bb0db)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816b9d80-ffffffff816b9dfd: iova_insert_rbtree (STB_LOCAL)
ffffffff816bb0db-ffffffff816bb0ee: iova_insert_rbtree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dcb80)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816dcb80-ffffffff816dcbf3: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817937e0)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
**Symbols:**

```
ffffffff817937e0-ffffffff81793853: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c00d0)
Location: drivers/iommu/iova.c:155
Inline: True
Direct callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
**Symbols:**

```
ffffffff817c00d0-ffffffff817c0143: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3250)
Location: drivers/iommu/iova.c:209
Inline: True
Direct callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
**Symbols:**

```
ffffffff817a3250-ffffffff817a32b7: iova_insert_rbtree (STB_LOCAL)
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
In drivers/iommu/iova.c (ffffffff8182cc71)
Location: drivers/iommu/iova.c:206
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
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
In drivers/iommu/iova.c (ffffffff8196df34)
Location: drivers/iommu/iova.c:147
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
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
In drivers/iommu/iova.c (ffffffff81ad8874)
Location: drivers/iommu/iova.c:152
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
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
In drivers/iommu/iova.c (ffffffff81b26969)
Location: drivers/iommu/iova.c:152
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
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
In drivers/iommu/iova.c (ffffffff81b7d5a9)
Location: drivers/iommu/iova.c:153
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108ccb18)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffff8000108ccb18-ffff8000108ccbb4: iova_insert_rbtree (STB_LOCAL)
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
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a25d0)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816a25d0-ffffffff816a2643: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8167ffc0)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff8167ffc0-ffffffff81680033: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d0840)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816d0840-ffffffff816d08b3: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iova_insert_rbtree(struct rb_root *root, struct iova *iova, struct rb_node *start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eadd0)
Location: drivers/iommu/iova.c:154
Inline: True
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff816eadd0-ffffffff816eae43: iova_insert_rbtree (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rb_node *start</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
