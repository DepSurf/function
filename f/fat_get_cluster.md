# Function: <code>fat_get_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff812f5580)
Location: fs/fat/cache.c:224
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_bmap
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff812f5580-ffffffff812f58b5: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81328fa0)
Location: fs/fat/cache.c:224
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81328fa0-ffffffff813292d3: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8133ece0)
Location: fs/fat/cache.c:224
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8133ece0-ffffffff8133f013: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813538a0)
Location: fs/fat/cache.c:224
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813538a0-ffffffff81353baf: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813784c0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813784c0-ffffffff813787cf: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813a6f50)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813a6f50-ffffffff813a72d7: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813bfd40)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813bfd40-ffffffff813c00c7: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813ea540)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813ea540-ffffffff813ea8de: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff814045e0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff814045e0-ffffffff8140497e: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81452530)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81452530-ffffffff81452801: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8146ea10)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8146ea10-ffffffff8146ece1: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81473f40)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81473f40-ffffffff814742db: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81ccf7f8-ffffffff81ccf82b: fat_get_cluster.cold (STB_LOCAL)
ffffffff814cabe0-ffffffff814caf8c: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81e829ce-ffffffff81e82a03: fat_get_cluster.cold (STB_LOCAL)
ffffffff81556bc0-ffffffff8155700a: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff82071cb4-ffffffff82071cde: fat_get_cluster.cold (STB_LOCAL)
ffffffff815f8780-ffffffff815f8b8d: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff820f1949-ffffffff820f1973: fat_get_cluster.cold (STB_LOCAL)
ffffffff81630700-ffffffff81630b0d: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff821cec2b-ffffffff821cec55: fat_get_cluster.cold (STB_LOCAL)
ffffffff81669bb0-ffffffff81669fbd: fat_get_cluster (STB_GLOBAL)
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
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffff8000104e31b0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffff8000104e31b0-ffff8000104e3560: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (c06a22d4)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
c06a22d4-c06a26b8: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (c0000000006202b0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
c0000000006202b0-c000000000620770: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffe000356a00)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffe000356a00-ffffffe000356cfe: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813fcbc0)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813fcbc0-ffffffff813fcf5e: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813ed640)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813ed640-ffffffff813ed9de: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813f9f40)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813f9f40-ffffffff813fa2de: fat_get_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_get_cluster(struct inode *inode, int cluster, int *fclus, int *dclus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8140fb80)
Location: fs/fat/cache.c:225
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_calc_dir_size
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8140fb80-ffffffff8140ff34: fat_get_cluster (STB_GLOBAL)
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
