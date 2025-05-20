# Function: <code>hugetlbfs_inc_free_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff812f3f90)
Location: fs/hugetlbfs/inode.c:911
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
**Symbols:**

```
ffffffff812f3f90-ffffffff812f3fc0: hugetlbfs_inc_free_inodes.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81327208)
Location: fs/hugetlbfs/inode.c:918
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
**Symbols:**

```
ffffffff813271c0-ffffffff813271f0: hugetlbfs_inc_free_inodes.part.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133cf78)
Location: fs/hugetlbfs/inode.c:916
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
**Symbols:**

```
ffffffff8133cf30-ffffffff8133cf60: hugetlbfs_inc_free_inodes.part.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81351f88)
Location: fs/hugetlbfs/inode.c:962
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
**Symbols:**

```
ffffffff81351f40-ffffffff81351f70: hugetlbfs_inc_free_inodes.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813767b8)
Location: fs/hugetlbfs/inode.c:962
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
**Symbols:**

```
ffffffff81376770-ffffffff813767a0: hugetlbfs_inc_free_inodes.part.18 (STB_LOCAL)
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
In fs/hugetlbfs/inode.c (ffffffff813a598c)
Location: fs/hugetlbfs/inode.c:983
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff813bf07c)
Location: fs/hugetlbfs/inode.c:993
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff813e98bc)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff8140395c)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff8145187c)
Location: fs/hugetlbfs/inode.c:1098
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff8146dd9c)
Location: fs/hugetlbfs/inode.c:1099
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff8147389c)
Location: fs/hugetlbfs/inode.c:1093
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff814ca4ac)
Location: fs/hugetlbfs/inode.c:1094
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff815547fc)
Location: fs/hugetlbfs/inode.c:1145
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff815f62bc)
Location: fs/hugetlbfs/inode.c:1221
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff8162e24c)
Location: fs/hugetlbfs/inode.c:1216
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff81667707)
Location: fs/hugetlbfs/inode.c:1249
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffff8000104e2118)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (c00000000061ec30)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe000355e00)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
</details>
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
In fs/hugetlbfs/inode.c (ffffffff813fbf3c)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff813ec9bc)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff813f92bc)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
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
In fs/hugetlbfs/inode.c (ffffffff8140e89c)
Location: fs/hugetlbfs/inode.c:1019
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
</details>
</li>
</ul>

## Differences
