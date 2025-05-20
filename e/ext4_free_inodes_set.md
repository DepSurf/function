# Function: <code>ext4_free_inodes_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7d40)
Location: fs/ext4/super.c:263
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812b7d40-ffffffff812b7d63: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e6a40)
Location: fs/ext4/super.c:292
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812e6a40-ffffffff812e6a63: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc5f0)
Location: fs/ext4/super.c:294
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812fc5f0-ffffffff812fc613: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331240)
Location: fs/ext4/super.c:296
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81331240-ffffffff81331263: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355700)
Location: fs/ext4/super.c:296
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81355700-ffffffff81355723: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81383b30)
Location: fs/ext4/super.c:296
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81383b30-ffffffff81383b53: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139c610)
Location: fs/ext4/super.c:319
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8139c610-ffffffff8139c633: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6860)
Location: fs/ext4/super.c:320
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813c6860-ffffffff813c6883: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dfc20)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813dfc20-ffffffff813dfc43: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142c4e0)
Location: fs/ext4/super.c:295
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8142c4e0-ffffffff8142c503: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81445300)
Location: fs/ext4/super.c:384
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81445300-ffffffff81445323: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144ac20)
Location: fs/ext4/super.c:384
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8144ac20-ffffffff8144ac43: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149eb30)
Location: fs/ext4/super.c:381
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8149eb30-ffffffff8149eb53: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81525230)
Location: fs/ext4/super.c:400
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81525230-ffffffff8152525f: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c27d0)
Location: fs/ext4/super.c:394
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815c27d0-ffffffff815c27ff: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f9f50)
Location: fs/ext4/super.c:394
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815f9f50-ffffffff815f9f7f: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632b50)
Location: fs/ext4/super.c:402
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81632b50-ffffffff81632b7f: ext4_free_inodes_set (STB_GLOBAL)
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
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8b70)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffff8000104b8b70-ffff8000104b8bc0: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067c238)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c067c238-c067c268: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005edc70)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c0000000005edc70-c0000000005edc98: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033554e)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffe00033554e-ffffffe000335594: ext4_free_inodes_set (STB_GLOBAL)
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
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8200)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813d8200-ffffffff813d8223: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8c80)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813c8c80-ffffffff813c8ca3: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5690)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813d5690-ffffffff813d56b3: ext4_free_inodes_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_free_inodes_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ea910)
Location: fs/ext4/super.c:315
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813ea910-ffffffff813ea933: ext4_free_inodes_set (STB_GLOBAL)
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
