# Function: <code>squashfs_read_table</code>

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
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81321b60)
Location: fs/squashfs/cache.c:416
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff81321b60-ffffffff81321c79: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813379f0)
Location: fs/squashfs/cache.c:416
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813379f0-ffffffff81337b09: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134c700)
Location: fs/squashfs/cache.c:416
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff8134c700-ffffffff8134c81a: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370d80)
Location: fs/squashfs/cache.c:416
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff81370d80-ffffffff81370e9a: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8139f5c0)
Location: fs/squashfs/cache.c:419
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff8139f5c0-ffffffff8139f6dc: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813b8350)
Location: fs/squashfs/cache.c:419
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813b8350-ffffffff813b846c: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e2b30)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813e2b30-ffffffff813e2c4c: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813fcb60)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813fcb60-ffffffff813fcc7c: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8144a4d0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff8144a4d0-ffffffff8144a5ec: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81466bc0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff81466bc0-ffffffff81466cdc: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8146c2d0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff8146c2d0-ffffffff8146c3ea: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff814c2b30)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff814c2b30-ffffffff814c2c4a: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8154d650)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff8154d650-ffffffff8154d772: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ed610)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff815ed610-ffffffff815ed732: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff816255d0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff816255d0-ffffffff816256f2: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165e6e0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff8165e6e0-ffffffff8165e802: squashfs_read_table (STB_GLOBAL)
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
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104daad0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffff8000104daad0-ffff8000104dac14: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c069c140)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
c069c140-c069c260: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (c0000000006157f0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
c0000000006157f0-c0000000006159c4: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f9da)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffe00034f9da-ffffffe00034fadc: squashfs_read_table (STB_GLOBAL)
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
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f5140)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813f5140-ffffffff813f525c: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e5bc0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813e5bc0-ffffffff813e5cdc: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f24c0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff813f24c0-ffffffff813f25dc: squashfs_read_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *squashfs_read_table(struct super_block *sb, u64 block, int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff814080b0)
Location: fs/squashfs/cache.c:406
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_read_inode_lookup_table
  - fs/squashfs/fragment.c:squashfs_read_fragment_index_table
  - fs/squashfs/id.c:squashfs_read_id_index_table
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
  - fs/squashfs/xattr_id.c:squashfs_read_xattr_id_table
```
**Symbols:**

```
ffffffff814080b0-ffffffff814081cc: squashfs_read_table (STB_GLOBAL)
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
