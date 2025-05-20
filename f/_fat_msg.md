# Function: <code>_fat_msg</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void _fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81e836d8)
Location: fs/fat/misc.c:54
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81e836d8-ffffffff81e83784: _fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81604ac0)
Location: fs/fat/misc.c:54
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81604ac0-ffffffff81604b5f: _fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8163c9d0)
Location: fs/fat/misc.c:54
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8163c9d0-ffffffff8163ca6f: _fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81675f40)
Location: fs/fat/misc.c:54
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_static_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_evict_inode
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81675f40-ffffffff81675fdf: _fat_msg (STB_GLOBAL)
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
