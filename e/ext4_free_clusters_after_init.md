# Function: <code>ext4_free_clusters_after_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f9f0)
Location: fs/ext4/balloc.c:250
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff8128f9f0-ffffffff8128fc51: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bcf30)
Location: fs/ext4/balloc.c:253
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff812bcf30-ffffffff812bd18e: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2580)
Location: fs/ext4/balloc.c:253
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff812d2580-ffffffff812d27de: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e3c00)
Location: fs/ext4/balloc.c:253
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff812e3c00-ffffffff812e3e51: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813085f0)
Location: fs/ext4/balloc.c:254
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813085f0-ffffffff81308841: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81336510)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81336510-ffffffff81336772: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d790)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff8134d790-ffffffff8134d9f2: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376170)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81376170-ffffffff813763d2: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138e3e0)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff8138e3e0-ffffffff8138e642: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d9b40)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813d9b40-ffffffff813d9b9f: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb7f0)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813eb7f0-ffffffff813eb84f: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f1d30)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813f1d30-ffffffff813f1d8f: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81cc8c26-ffffffff81cc8c41: ext4_free_clusters_after_init.cold (STB_LOCAL)
ffffffff81443d30-ffffffff81443db5: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81e7b95d-ffffffff81e7b978: ext4_free_clusters_after_init.cold (STB_LOCAL)
ffffffff814bfc10-ffffffff814bfc9f: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff8206c0ee-ffffffff8206c109: ext4_free_clusters_after_init.cold (STB_LOCAL)
ffffffff81557be0-ffffffff81557c6f: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:240
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff820ebf79-ffffffff820ebf94: ext4_free_clusters_after_init.cold (STB_LOCAL)
ffffffff8158f930-ffffffff8158f9bf: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:239
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff821c9250-ffffffff821c926b: ext4_free_clusters_after_init.cold (STB_LOCAL)
ffffffff815c8e30-ffffffff815c8ebf: ext4_free_clusters_after_init (STB_GLOBAL)
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
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff800010460600)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffff800010460600-ffff800010460898: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0620de4)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
c0620de4-c062103c: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057cb90)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
c00000000057cb90-c00000000057cedc: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002efb6c)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffe0002efb6c-ffffffe0002efd96: ext4_free_clusters_after_init (STB_GLOBAL)
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
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813869c0)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813869c0-ffffffff81386c22: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81377450)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81377450-ffffffff813776b2: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384490)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81384490-ffffffff813846f2: ext4_free_clusters_after_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int ext4_free_clusters_after_init(struct super_block *sb, ext4_group_t block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81398010)
Location: fs/ext4/balloc.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81398010-ffffffff81398272: ext4_free_clusters_after_init (STB_GLOBAL)
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
