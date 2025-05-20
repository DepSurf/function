# Function: <code>squashfs_read_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff81320bc0)
Location: fs/squashfs/block.c:90
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81320bc0-ffffffff813211a7: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff81336a70)
Location: fs/squashfs/block.c:91
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81336a70-ffffffff81337057: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff8134b7a0)
Location: fs/squashfs/block.c:91
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8134b7a0-ffffffff8134bd6f: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff8136fdd0)
Location: fs/squashfs/block.c:91
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8136fdd0-ffffffff813703e8: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff8139e5c0)
Location: fs/squashfs/block.c:91
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8139e5c0-ffffffff8139eba8: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff813b7330)
Location: fs/squashfs/block.c:91
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813b7330-ffffffff813b7934: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff813e1ab0)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813e1ab0-ffffffff813e210c: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff813fbae0)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813fbae0-ffffffff813fc13c: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:142
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81449a70-ffffffff81449a7b: squashfs_read_data.cold (STB_LOCAL)
ffffffff814496e0-ffffffff81449a70: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:142
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81bed3b4-ffffffff81bed3d5: squashfs_read_data.cold (STB_LOCAL)
ffffffff81465e50-ffffffff814661b8: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:142
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81bdf498-ffffffff81bdf4b9: squashfs_read_data.cold (STB_LOCAL)
ffffffff8146b5f0-ffffffff8146b94f: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:141
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81cceeb9-ffffffff81ccef06: squashfs_read_data.cold (STB_LOCAL)
ffffffff814c1e40-ffffffff814c21aa: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:136
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81e81f0e-ffffffff81e81f59: squashfs_read_data.cold (STB_LOCAL)
ffffffff8154c870-ffffffff8154cbf5: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:140
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8207151b-ffffffff82071535: squashfs_read_data.cold (STB_LOCAL)
ffffffff815ec6e0-ffffffff815ecad1: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:263
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff820f11cb-ffffffff820f11e5: squashfs_read_data.cold (STB_LOCAL)
ffffffff81624640-ffffffff81624a2b: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:263
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff821ce473-ffffffff821ce48d: squashfs_read_data.cold (STB_LOCAL)
ffffffff8165d6d0-ffffffff8165dabb: squashfs_read_data (STB_GLOBAL)
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
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffff8000104d97e8)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffff8000104d97e8-ffff8000104d9e14: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (c069af90)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
c069af90-c069b6e4: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (c0000000006140e0)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
c0000000006140e0-c000000000614814: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffe00034e9c8)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffe00034e9c8-ffffffe00034ee64: squashfs_read_data (STB_GLOBAL)
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
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff813f40c0)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813f40c0-ffffffff813f471c: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff813e4b40)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813e4b40-ffffffff813e519c: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff813f1440)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff813f1440-ffffffff813f1a9c: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int squashfs_read_data(struct super_block *sb, u64 index, int length, u64 *next_index, struct squashfs_page_actor *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff81407050)
Location: fs/squashfs/block.c:78
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_read_table
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81407050-ffffffff814076a0: squashfs_read_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
