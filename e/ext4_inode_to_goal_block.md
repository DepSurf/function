# Function: <code>ext4_inode_to_goal_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81290310)
Location: fs/ext4/balloc.c:847
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81290310-ffffffff812903e7: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bd830)
Location: fs/ext4/balloc.c:853
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812bd830-ffffffff812bd903: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2e80)
Location: fs/ext4/balloc.c:853
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812d2e80-ffffffff812d2f53: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e4490)
Location: fs/ext4/balloc.c:853
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812e4490-ffffffff812e4563: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308ec0)
Location: fs/ext4/balloc.c:853
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81308ec0-ffffffff81308f9f: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81336df0)
Location: fs/ext4/balloc.c:862
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81336df0-ffffffff81336ece: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134e070)
Location: fs/ext4/balloc.c:862
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8134e070-ffffffff8134e14e: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376a20)
Location: fs/ext4/balloc.c:862
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81376a20-ffffffff81376af3: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138ec90)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8138ec90-ffffffff8138ed63: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813da240)
Location: fs/ext4/balloc.c:872
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813da240-ffffffff813da313: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813ebf10)
Location: fs/ext4/balloc.c:898
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813ebf10-ffffffff813ebff0: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f2440)
Location: fs/ext4/balloc.c:898
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813f2440-ffffffff813f251b: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:904
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81cc8cc5-ffffffff81cc8cee: ext4_inode_to_goal_block.cold (STB_LOCAL)
ffffffff81444410-ffffffff81444500: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:905
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81e7b9fc-ffffffff81e7ba25: ext4_inode_to_goal_block.cold (STB_LOCAL)
ffffffff814c02f0-ffffffff814c03ef: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:905
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8206c165-ffffffff8206c18e: ext4_inode_to_goal_block.cold (STB_LOCAL)
ffffffff81558340-ffffffff8155843f: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:947
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff820ebff0-ffffffff820ec019: ext4_inode_to_goal_block.cold (STB_LOCAL)
ffffffff81590190-ffffffff8159028b: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:962
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff821c926b-ffffffff821c9294: ext4_inode_to_goal_block.cold (STB_LOCAL)
ffffffff815c8ed0-ffffffff815c8fcb: ext4_inode_to_goal_block (STB_GLOBAL)
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
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff8000104611f8)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffff8000104611f8-ffff8000104612dc: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0621894)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
c0621894-c062197c: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057d910)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
c00000000057d910-c00000000057da2c: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002f04a8)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffe0002f04a8-ffffffe0002f0568: ext4_inode_to_goal_block (STB_GLOBAL)
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
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81387270)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81387270-ffffffff81387343: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81377d00)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81377d00-ffffffff81377dd3: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384d40)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81384d40-ffffffff81384e13: ext4_inode_to_goal_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ext4_fsblk_t ext4_inode_to_goal_block(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813988c0)
Location: fs/ext4/balloc.c:870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_find_goal
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813988c0-ffffffff81398993: ext4_inode_to_goal_block (STB_GLOBAL)
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
