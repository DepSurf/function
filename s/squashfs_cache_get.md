# Function: <code>squashfs_cache_get</code>

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
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813212a0)
Location: fs/squashfs/cache.c:65
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813212a0-ffffffff8132160c: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81337150)
Location: fs/squashfs/cache.c:65
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81337150-ffffffff8133749e: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134bf10)
Location: fs/squashfs/cache.c:65
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff8134bf10-ffffffff8134c253: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370590)
Location: fs/squashfs/cache.c:65
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81370590-ffffffff813708d3: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:65
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff8139f6dc-ffffffff8139f6f3: squashfs_cache_get.cold.4 (STB_LOCAL)
ffffffff8139ee20-ffffffff8139f131: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:65
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813b846c-ffffffff813b8483: squashfs_cache_get.cold.3 (STB_LOCAL)
ffffffff813b7bb0-ffffffff813b7ec1: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813e2c4c-ffffffff813e2c63: squashfs_cache_get.cold (STB_LOCAL)
ffffffff813e2380-ffffffff813e26a6: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813fcc7c-ffffffff813fcc93: squashfs_cache_get.cold (STB_LOCAL)
ffffffff813fc3b0-ffffffff813fc6d6: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff8144a5ec-ffffffff8144a603: squashfs_cache_get.cold (STB_LOCAL)
ffffffff81449d10-ffffffff8144a038: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81bed3d5-ffffffff81bed3ec: squashfs_cache_get.cold (STB_LOCAL)
ffffffff81466430-ffffffff8146672d: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81bdf4b9-ffffffff81bdf4d0: squashfs_cache_get.cold (STB_LOCAL)
ffffffff8146ba00-ffffffff8146bcfd: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff81ccef06-ffffffff81ccef1d: squashfs_cache_get.cold (STB_LOCAL)
ffffffff814c2260-ffffffff814c255a: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff81e81f59-ffffffff81e81f70: squashfs_cache_get.cold (STB_LOCAL)
ffffffff8154ccc0-ffffffff8154d041: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ecbc0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff815ecbc0-ffffffff815ecf5f: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81624b00)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff81624b00-ffffffff81624e9f: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165db90)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
**Symbols:**

```
ffffffff8165db90-ffffffff8165df2f: squashfs_cache_get (STB_GLOBAL)
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
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104da0b0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffff8000104da0b0-ffff8000104da4cc: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c069b87c)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
c069b87c-c069bc5c: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c000000000614b10)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
c000000000614b10-c0000000006150a0: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f092)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffe00034f092-ffffffe00034f49a: squashfs_cache_get (STB_GLOBAL)
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
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813f525c-ffffffff813f5273: squashfs_cache_get.cold (STB_LOCAL)
ffffffff813f4990-ffffffff813f4cb6: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813e5cdc-ffffffff813e5cf3: squashfs_cache_get.cold (STB_LOCAL)
ffffffff813e5410-ffffffff813e5736: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff813f25dc-ffffffff813f25f3: squashfs_cache_get.cold (STB_LOCAL)
ffffffff813f1d10-ffffffff813f2036: squashfs_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct squashfs_cache_entry *squashfs_cache_get(struct super_block *sb, struct squashfs_cache *cache, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (0)
Location: fs/squashfs/cache.c:52
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_get_datablock
  - fs/squashfs/cache.c:squashfs_get_fragment
  - fs/squashfs/cache.c:squashfs_read_metadata
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
**Symbols:**

```
ffffffff814081cc-ffffffff814081e3: squashfs_cache_get.cold (STB_LOCAL)
ffffffff81407910-ffffffff81407c22: squashfs_cache_get (STB_GLOBAL)
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
