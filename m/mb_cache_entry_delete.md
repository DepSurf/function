# Function: <code>mb_cache_entry_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812bad70)
Location: fs/mbcache.c:225
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff812bad70-ffffffff812bae71: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812de650)
Location: fs/mbcache.c:226
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff812de650-ffffffff812de751: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8130a740)
Location: fs/mbcache.c:226
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff8130a740-ffffffff8130a893: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8131f870)
Location: fs/mbcache.c:226
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff8131f870-ffffffff8131f9c3: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813470c0)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813470c0-ffffffff81347214: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8135fa90)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff8135fa90-ffffffff8135fbe4: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813a4e20)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813a4e20-ffffffff813a4f74: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813b5b80)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813b5b80-ffffffff813b5cd4: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813bcb60)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813bcb60-ffffffff813bccb4: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81cc7504-ffffffff81cc7536: mb_cache_entry_delete.cold (STB_LOCAL)
ffffffff8140caa0-ffffffff8140cc11: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:240
Inline: False
```
**Symbols:**

```
ffffffff81e79ba4-ffffffff81e79bd6: mb_cache_entry_delete.cold (STB_LOCAL)
ffffffff81482370-ffffffff81482560: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffff800010424f88)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffff800010424f88-ffff8000104251c8: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c05ee5d8)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
c05ee5d8-c05ee83c: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c000000000533e10)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
c000000000533e10-c0000000005340ac: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffe0002c3e60)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffe0002c3e60-ffffffe0002c3fe4: mb_cache_entry_delete (STB_GLOBAL)
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
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81358070)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81358070-ffffffff813581c4: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81348d20)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81348d20-ffffffff81348e74: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81355b40)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff81355b40-ffffffff81355c94: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mb_cache_entry_delete(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813691e0)
Location: fs/mbcache.c:227
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
**Symbols:**

```
ffffffff813691e0-ffffffff81369368: mb_cache_entry_delete (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
