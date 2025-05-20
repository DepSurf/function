# Function: <code>fat_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81322ea4)
Location: fs/fat/misc.c:46
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/misc.c:__fat_fs_error
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81322ea4-ffffffff81322f24: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81357bdd)
Location: fs/fat/misc.c:46
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81357bdd-ffffffff81357c5d: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8136e0da)
Location: fs/fat/misc.c:46
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8136e0da-ffffffff8136e15a: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8135ce62)
Location: fs/fat/misc.c:46
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8135ce62-ffffffff8135cee2: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81381b62)
Location: fs/fat/misc.c:46
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81381b62-ffffffff81381be2: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813b06d8)
Location: fs/fat/misc.c:46
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813b06d8-ffffffff813b075a: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813c9d38)
Location: fs/fat/misc.c:47
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813c9d38-ffffffff813c9dba: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f48b8)
Location: fs/fat/misc.c:48
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813f48b8-ffffffff813f493a: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8140e788)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8140e788-ffffffff8140e80a: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8145c578)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:uni16_to_x8
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
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8145c578-ffffffff8145c5fa: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81bedd27)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:uni16_to_x8
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
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81bedd27-ffffffff81bedda9: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81bdfe31)
Location: fs/fat/misc.c:48
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
ffffffff81bdfe31-ffffffff81bdfeb3: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81cd04c1)
Location: fs/fat/misc.c:48
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
ffffffff81cd04c1-ffffffff81cd0543: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffff8000104ef40c)
Location: fs/fat/misc.c:48
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffff8000104ef40c-ffff8000104ef4a8: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c06acee4)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c06acee4-c06acf64: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c00000000062e6a4)
Location: fs/fat/misc.c:48
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c00000000062e6a4-c00000000062e748: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffe00035f3d2)
Location: fs/fat/misc.c:48
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffe00035f3d2-ffffffe00035f43a: fat_msg (STB_GLOBAL)
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
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81406d68)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81406d68-ffffffff81406dea: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f77e8)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813f77e8-ffffffff813f786a: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814040e8)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff814040e8-ffffffff8140416a: fat_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fat_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81419d4b)
Location: fs/fat/misc.c:48
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat__get_entry
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
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
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
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81419d4b-ffffffff81419dcd: fat_msg (STB_GLOBAL)
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
