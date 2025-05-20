# Function: <code>mb_cache_entry_find_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache_entry *prev, struct block_device *bdev, unsigned int key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8126cd30)
Location: fs/mbcache.c:824
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8126cd30-ffffffff8126cda5: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81298e50)
Location: fs/mbcache.c:182
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81298e50-ffffffff81298e63: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812ad8c0)
Location: fs/mbcache.c:182
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812ad8c0-ffffffff812ad8d3: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812bad50)
Location: fs/mbcache.c:183
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812bad50-ffffffff812bad63: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812de630)
Location: fs/mbcache.c:184
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812de630-ffffffff812de643: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8130a3f0)
Location: fs/mbcache.c:184
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8130a3f0-ffffffff8130a403: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8131fea0)
Location: fs/mbcache.c:184
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8131fea0-ffffffff8131feb3: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81347740)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81347740-ffffffff81347753: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8135fa70)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8135fa70-ffffffff8135fa83: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813a5470)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff813a5470-ffffffff813a548c: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813b61d0)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff813b61d0-ffffffff813b61ec: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813bd010)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff813bd010-ffffffff813bd02c: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8140cd90)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff8140cd90-ffffffff8140cdac: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff814820e0)
Location: fs/mbcache.c:198
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff814820e0-ffffffff81482108: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81515240)
Location: fs/mbcache.c:209
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff81515240-ffffffff8151525d: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8154cc40)
Location: fs/mbcache.c:209
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff8154cc40-ffffffff8154cc5d: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81582a70)
Location: fs/mbcache.c:209
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
**Symbols:**

```
ffffffff81582a70-ffffffff81582a8d: mb_cache_entry_find_next (STB_GLOBAL)
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
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffff800010425a48)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffff800010425a48-ffff800010425a80: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c05ee5b8)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c05ee5b8-c05ee5d8: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c0000000005349c0)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c0000000005349c0-c0000000005349d8: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffe0002c434e)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffe0002c434e-ffffffe0002c4382: mb_cache_entry_find_next (STB_GLOBAL)
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
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81358050)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81358050-ffffffff81358063: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81348d00)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81348d00-ffffffff81348d13: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81355b20)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81355b20-ffffffff81355b33: mb_cache_entry_find_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_find_next(struct mb_cache *cache, struct mb_cache_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813691c0)
Location: fs/mbcache.c:185
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813691c0-ffffffff813691d3: mb_cache_entry_find_next (STB_GLOBAL)
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
<code>struct mb_cache *cache</code>
</li>
<li>
<b>Param added. </b>
<code>struct mb_cache_entry *entry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mb_cache_entry *prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int key</code>
</li>
</ul>
</details>
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
