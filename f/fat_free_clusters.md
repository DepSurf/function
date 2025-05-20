# Function: <code>fat_free_clusters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff812f99f0)
Location: fs/fat/fatent.c:550
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_get_block
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff812f99f0-ffffffff812f9d49: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8132d620)
Location: fs/fat/fatent.c:550
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff8132d620-ffffffff8132d97b: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81343360)
Location: fs/fat/fatent.c:550
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81343360-ffffffff813436bb: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81357e10)
Location: fs/fat/fatent.c:550
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81357e10-ffffffff81358174: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8137cad0)
Location: fs/fat/fatent.c:550
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff8137cad0-ffffffff8137ce39: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:550
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff813ac1ea-ffffffff813ac20f: fat_free_clusters.cold.16 (STB_LOCAL)
ffffffff813ab530-ffffffff813ab86f: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:549
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff813c54b2-ffffffff813c54d7: fat_free_clusters.cold.23 (STB_LOCAL)
ffffffff813c4360-ffffffff813c469f: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:549
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff813effcf-ffffffff813efff4: fat_free_clusters.cold (STB_LOCAL)
ffffffff813eec50-ffffffff813eef9a: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81409eba-ffffffff81409edf: fat_free_clusters.cold (STB_LOCAL)
ffffffff81408cc0-ffffffff8140900a: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81457abf-ffffffff81457ae4: fat_free_clusters.cold (STB_LOCAL)
ffffffff81456940-ffffffff81456ca7: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81bed86d-ffffffff81bed892: fat_free_clusters.cold (STB_LOCAL)
ffffffff81472d00-ffffffff81473061: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81bdf96d-ffffffff81bdf996: fat_free_clusters.cold (STB_LOCAL)
ffffffff81478720-ffffffff81478aa3: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:553
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81ccfc18-ffffffff81ccfc8d: fat_free_clusters.cold (STB_LOCAL)
ffffffff814cfb10-ffffffff814cff1f: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:554
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81e82e59-ffffffff81e82ece: fat_free_clusters.cold (STB_LOCAL)
ffffffff8155c5c0-ffffffff8155c992: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:554
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff82071fef-ffffffff8207203b: fat_free_clusters.cold (STB_LOCAL)
ffffffff815fe5b0-ffffffff815fe9ab: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:554
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff820f1c52-ffffffff820f1c9e: fat_free_clusters.cold (STB_LOCAL)
ffffffff81636580-ffffffff8163697b: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:554
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff821cef34-ffffffff821cef80: fat_free_clusters.cold (STB_LOCAL)
ffffffff8166fa70-ffffffff8166fe6b: fat_free_clusters (STB_GLOBAL)
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
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e9460)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffff8000104e9460-ffff8000104e9744: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a7164)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
c06a7164-c06a74a8: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c000000000626eb0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
c000000000626eb0-c000000000627268: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe00035a556)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffe00035a556-ffffffe00035a7f8: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff8140249a-ffffffff814024bf: fat_free_clusters.cold (STB_LOCAL)
ffffffff814012a0-ffffffff814015ea: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff813f2f1a-ffffffff813f2f3f: fat_free_clusters.cold (STB_LOCAL)
ffffffff813f1d20-ffffffff813f206a: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff813ff81a-ffffffff813ff83f: fat_free_clusters.cold (STB_LOCAL)
ffffffff813fe620-ffffffff813fe96a: fat_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_free_clusters(struct inode *inode, int cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:552
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_add_cluster
  - fs/fat/namei_vfat.c:vfat_mkdir
```
**Symbols:**

```
ffffffff81415445-ffffffff8141546a: fat_free_clusters.cold (STB_LOCAL)
ffffffff81414240-ffffffff8141458a: fat_free_clusters (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
