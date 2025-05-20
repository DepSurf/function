# Function: <code>ext4_group_desc_csum_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812bacb0)
Location: fs/ext4/super.c:2100
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812bacb0-ffffffff812bacf1: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e9bd0)
Location: fs/ext4/super.c:2219
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812e9bd0-ffffffff812e9c10: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ff940)
Location: fs/ext4/super.c:2244
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812ff940-ffffffff812ff980: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81334720)
Location: fs/ext4/super.c:2302
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81334720-ffffffff8133476b: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81358c30)
Location: fs/ext4/super.c:2305
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81358c30-ffffffff81358c7a: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813875a0)
Location: fs/ext4/super.c:2346
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813875a0-ffffffff813875ea: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a00e0)
Location: fs/ext4/super.c:2408
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff813a00e0-ffffffff813a012a: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ca430)
Location: fs/ext4/super.c:2451
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813ca430-ffffffff813ca480: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e37e0)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813e37e0-ffffffff813e3830: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81430c40)
Location: fs/ext4/super.c:2623
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81430c40-ffffffff81430c93: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81449a10)
Location: fs/ext4/super.c:2828
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81449a10-ffffffff81449a63: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144f390)
Location: fs/ext4/super.c:2854
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff8144f390-ffffffff8144f3e3: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a2f10)
Location: fs/ext4/super.c:2840
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff814a2f10-ffffffff814a2f63: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152a3b0)
Location: fs/ext4/super.c:3219
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff8152a3b0-ffffffff8152a41c: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c8d60)
Location: fs/ext4/super.c:3208
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff815c8d60-ffffffff815c8dcc: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81600b20)
Location: fs/ext4/super.c:3262
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81600b20-ffffffff81600b8c: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81639870)
Location: fs/ext4/super.c:3268
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81639870-ffffffff816398dc: ext4_group_desc_csum_verify (STB_GLOBAL)
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
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bcda0)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffff8000104bcda0-ffff8000104bce3c: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c068040c)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
c068040c-c06804d0: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f2d70)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
c0000000005f2d70-c0000000005f2df4: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000338aae)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffe000338aae-ffffffe000338b1a: ext4_group_desc_csum_verify (STB_GLOBAL)
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
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dbdc0)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813dbdc0-ffffffff813dbe10: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cc840)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813cc840-ffffffff813cc890: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d9260)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813d9260-ffffffff813d92b0: ext4_group_desc_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ee560)
Location: fs/ext4/super.c:2469
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813ee560-ffffffff813ee5b0: ext4_group_desc_csum_verify (STB_GLOBAL)
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
