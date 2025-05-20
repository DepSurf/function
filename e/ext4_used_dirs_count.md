# Function: <code>ext4_used_dirs_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7c20)
Location: fs/ext4/super.c:215
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_count_dirs
```
**Symbols:**

```
ffffffff812b7c20-ffffffff812b7c47: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812edbbb)
Location: fs/ext4/super.c:244
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812e6920-ffffffff812e6947: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81303b57)
Location: fs/ext4/super.c:246
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812fc4d0-ffffffff812fc4f7: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81338285)
Location: fs/ext4/super.c:248
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81331120-ffffffff81331145: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135c765)
Location: fs/ext4/super.c:248
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813555e0-ffffffff81355605: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8138b1a0)
Location: fs/ext4/super.c:248
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81383a10-ffffffff81383a35: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a3414)
Location: fs/ext4/super.c:271
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8139c4f0-ffffffff8139c515: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce0b6)
Location: fs/ext4/super.c:272
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813c6740-ffffffff813c6765: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e7b5b)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813dfb00-ffffffff813dfb25: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81430c06)
Location: fs/ext4/super.c:247
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8142c3c0-ffffffff8142c3e5: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814499cb)
Location: fs/ext4/super.c:336
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff814451e0-ffffffff81445205: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144f34b)
Location: fs/ext4/super.c:336
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8144ab00-ffffffff8144ab25: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a2ecc)
Location: fs/ext4/super.c:333
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8149ea10-ffffffff8149ea35: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152a350)
Location: fs/ext4/super.c:352
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81525110-ffffffff8152513f: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c8cf0)
Location: fs/ext4/super.c:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815c2650-ffffffff815c267f: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81600ab1)
Location: fs/ext4/super.c:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815f9dd0-ffffffff815f9dff: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81639801)
Location: fs/ext4/super.c:354
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff816329d0-ffffffff816329ff: ext4_used_dirs_count (STB_GLOBAL)
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
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104c052c)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffff8000104b89a0-ffff8000104b89e4: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0683c9c)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c067c124-c067c154: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f6dc4)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c0000000005edb30-c0000000005edb64: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033c400)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffe0003353ac-ffffffe0003353f4: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e013b)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813d80e0-ffffffff813d8105: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d0bbb)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813c8b60-ffffffff813c8b85: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dd4b4)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813d5570-ffffffff813d5595: ext4_used_dirs_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_used_dirs_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813f28d5)
Location: fs/ext4/super.c:267
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813ea7f0-ffffffff813ea815: ext4_used_dirs_count (STB_GLOBAL)
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
