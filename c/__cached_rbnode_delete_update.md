# Function: <code>__cached_rbnode_delete_update</code>

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
In drivers/iommu/iova.c (ffffffff8152d35c)
Location: drivers/iommu/iova.c:69
Inline: True
Inline callers:
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:split_and_remove_iova
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
In drivers/iommu/iova.c (ffffffff81580d31)
Location: drivers/iommu/iova.c:81
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
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
In drivers/iommu/iova.c (ffffffff815ad8f1)
Location: drivers/iommu/iova.c:81
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
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
In drivers/iommu/iova.c (ffffffff815c3561)
Location: drivers/iommu/iova.c:82
Inline: True
Inline callers:
  - drivers/iommu/iova.c:split_and_remove_iova
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629170)
Location: drivers/iommu/iova.c:136
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff81629170-ffffffff816291d0: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81663e80)
Location: drivers/iommu/iova.c:136
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff81663e80-ffffffff81663ee7: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682470)
Location: drivers/iommu/iova.c:137
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff81682470-ffffffff816824df: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816b9c80)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff816b9c80-ffffffff816b9ce8: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dca80)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff816dca80-ffffffff816dcae8: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81793660)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff81793660-ffffffff817936c8: __cached_rbnode_delete_update (STB_LOCAL)
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
In drivers/iommu/iova.c (ffffffff817c06f8)
Location: drivers/iommu/iova.c:136
Inline: True
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
In drivers/iommu/iova.c (ffffffff817a3858)
Location: drivers/iommu/iova.c:153
Inline: True
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
In drivers/iommu/iova.c (ffffffff8182c3c4)
Location: drivers/iommu/iova.c:150
Inline: True
Inline callers:
  - drivers/iommu/iova.c:remove_iova
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
In drivers/iommu/iova.c (ffffffff8196d718)
Location: drivers/iommu/iova.c:90
Inline: True
Inline callers:
  - drivers/iommu/iova.c:remove_iova
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
In drivers/iommu/iova.c (ffffffff81ad7fc8)
Location: drivers/iommu/iova.c:95
Inline: True
Inline callers:
  - drivers/iommu/iova.c:remove_iova
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
In drivers/iommu/iova.c (ffffffff81b25f08)
Location: drivers/iommu/iova.c:95
Inline: True
Inline callers:
  - drivers/iommu/iova.c:remove_iova
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
In drivers/iommu/iova.c (ffffffff81b7cd38)
Location: drivers/iommu/iova.c:96
Inline: True
Inline callers:
  - drivers/iommu/iova.c:remove_iova
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cca20)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffff8000108cca20-ffff8000108ccab0: __cached_rbnode_delete_update (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a24d0)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff816a24d0-ffffffff816a2538: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8167fec0)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff8167fec0-ffffffff8167ff28: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d0740)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff816d0740-ffffffff816d07a8: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cached_rbnode_delete_update(struct iova_domain *iovad, struct iova *free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eacd0)
Location: drivers/iommu/iova.c:135
Inline: False
Direct callers:
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
```
**Symbols:**

```
ffffffff816eacd0-ffffffff816ead38: __cached_rbnode_delete_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
