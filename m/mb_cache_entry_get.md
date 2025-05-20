# Function: <code>mb_cache_entry_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, struct block_device *bdev, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8126d050)
Location: fs/mbcache.c:661
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8126d050-ffffffff8126d259: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81298d20)
Location: fs/mbcache.c:195
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81298d20-ffffffff81298d85: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812ad790)
Location: fs/mbcache.c:195
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff812ad790-ffffffff812ad7f5: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812bac20)
Location: fs/mbcache.c:196
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff812bac20-ffffffff812bac85: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812de500)
Location: fs/mbcache.c:197
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff812de500-ffffffff812de565: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8130a2c0)
Location: fs/mbcache.c:197
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8130a2c0-ffffffff8130a324: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8131fd70)
Location: fs/mbcache.c:197
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8131fd70-ffffffff8131fdd3: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81347600)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81347600-ffffffff81347663: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8135f930)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8135f930-ffffffff8135f993: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813a5340)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813a5340-ffffffff813a53a3: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813b60a0)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813b60a0-ffffffff813b6103: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813bcee0)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813bcee0-ffffffff813bcf43: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81cc7536-ffffffff81cc7555: mb_cache_entry_get.cold (STB_LOCAL)
ffffffff8140cc20-ffffffff8140cca9: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:211
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81e79b43-ffffffff81e79b62: mb_cache_entry_get.cold (STB_LOCAL)
ffffffff81481ec0-ffffffff81481f9e: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:222
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8206abc4-ffffffff8206abe3: mb_cache_entry_get.cold (STB_LOCAL)
ffffffff81514f20-ffffffff8151500b: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:222
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff820eab33-ffffffff820eab52: mb_cache_entry_get.cold (STB_LOCAL)
ffffffff8154c920-ffffffff8154ca0b: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:222
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff821c78ae-ffffffff821c78cd: mb_cache_entry_get.cold (STB_LOCAL)
ffffffff81582750-ffffffff8158283b: mb_cache_entry_get (STB_GLOBAL)
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
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffff800010425778)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffff800010425778-ffff800010425894: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c05ee298)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c05ee298-c05ee3e8: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c000000000534710)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c000000000534710-c0000000005347f8: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffe0002c3dc2)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffe0002c3dc2-ffffffe0002c3e60: mb_cache_entry_get (STB_GLOBAL)
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
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81357f10)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81357f10-ffffffff81357f73: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81348bc0)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81348bc0-ffffffff81348c23: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813559e0)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813559e0-ffffffff81355a43: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81369040)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81369040-ffffffff813690ca: mb_cache_entry_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 key</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 value</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t block</code>
</li>
</ul>
</details>
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
