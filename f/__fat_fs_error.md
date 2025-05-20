# Function: <code>__fat_fs_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81322f24)
Location: fs/fat/misc.c:19
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_bmap
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81322f24-ffffffff81323001: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81357c5d)
Location: fs/fat/misc.c:19
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81357c5d-ffffffff81357d3a: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8136e15a)
Location: fs/fat/misc.c:19
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8136e15a-ffffffff8136e237: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8135cee2)
Location: fs/fat/misc.c:19
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8135cee2-ffffffff8135cfbf: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81381be2)
Location: fs/fat/misc.c:19
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81381be2-ffffffff81381cbf: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813b075a)
Location: fs/fat/misc.c:19
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813b075a-ffffffff813b083d: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813c9dba)
Location: fs/fat/misc.c:20
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813c9dba-ffffffff813c9e9d: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f493a)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813f493a-ffffffff813f4a1e: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8140e80a)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8140e80a-ffffffff8140e8ee: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8145c5fa)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8145c5fa-ffffffff8145c6de: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81bedda9)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81bedda9-ffffffff81bede8d: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81bdfeb3)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81bdfeb3-ffffffff81bdff97: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81cd0543)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81cd0543-ffffffff81cd0627: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81e83784)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81e83784-ffffffff81e838a2: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81604b70)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81604b70-ffffffff81604ca3: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8163ca80)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8163ca80-ffffffff8163cbb3: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81675ff0)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81675ff0-ffffffff81676123: __fat_fs_error (STB_GLOBAL)
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
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffff8000104ef4a8)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffff8000104ef4a8-ffff8000104ef5a8: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c06acf64)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
c06acf64-c06ad048: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c00000000062e748)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
c00000000062e748-c00000000062e854: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffe00035f43a)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffe00035f43a-ffffffe00035f4fe: __fat_fs_error (STB_GLOBAL)
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
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81406dea)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81406dea-ffffffff81406ece: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f786a)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813f786a-ffffffff813f794e: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8140416a)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8140416a-ffffffff8140424e: __fat_fs_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __fat_fs_error(struct super_block *sb, int report, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81419dcd)
Location: fs/fat/misc.c:21
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_mapped_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_access_init
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/misc.c:fat_chain_add
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81419dcd-ffffffff81419eb1: __fat_fs_error (STB_GLOBAL)
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
