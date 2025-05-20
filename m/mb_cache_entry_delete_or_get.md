# Function: <code>mb_cache_entry_delete_or_get</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *mb_cache_entry_delete_or_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
**Symbols:**

```
ffffffff81e79acf-ffffffff81e79b01: mb_cache_entry_delete_or_get.cold (STB_LOCAL)
ffffffff814817b0-ffffffff814819b6: mb_cache_entry_delete_or_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_delete_or_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81515020)
Location: fs/mbcache.c:254
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
**Symbols:**

```
ffffffff81515020-ffffffff815150bc: mb_cache_entry_delete_or_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_delete_or_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8154ca20)
Location: fs/mbcache.c:254
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
**Symbols:**

```
ffffffff8154ca20-ffffffff8154cabc: mb_cache_entry_delete_or_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mb_cache_entry *mb_cache_entry_delete_or_get(struct mb_cache *cache, u32 key, u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81582850)
Location: fs/mbcache.c:254
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
**Symbols:**

```
ffffffff81582850-ffffffff815828ec: mb_cache_entry_delete_or_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
