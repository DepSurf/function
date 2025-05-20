# Function: <code>sync_dirty_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81246920)
Location: fs/buffer.c:3153
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81246920-ffffffff81246935: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f880)
Location: fs/buffer.c:3212
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8126f880-ffffffff8126f895: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81282a80)
Location: fs/buffer.c:3253
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81282a80-ffffffff81282a95: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81290170)
Location: fs/buffer.c:3240
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81290170-ffffffff81290185: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b2e80)
Location: fs/buffer.c:3208
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff812b2e80-ffffffff812b2e95: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812dad70)
Location: fs/buffer.c:3179
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff812dad70-ffffffff812dad85: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812f0250)
Location: fs/buffer.c:3191
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff812f0250-ffffffff812f0265: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81311b20)
Location: fs/buffer.c:3198
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81311b20-ffffffff81311b35: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81324b40)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81324b40-ffffffff81324b55: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135d950)
Location: fs/buffer.c:3185
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8135d950-ffffffff8135d965: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136b540)
Location: fs/buffer.c:3166
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8136b540-ffffffff8136b555: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371de0)
Location: fs/buffer.c:3187
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81371de0-ffffffff81371df5: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0e00)
Location: fs/buffer.c:3166
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff813c0e00-ffffffff813c0e15: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81447aa0)
Location: fs/buffer.c:3151
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff81447aa0-ffffffff81447abd: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d65f0)
Location: fs/buffer.c:2756
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff814d65f0-ffffffff814d660d: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150cb60)
Location: fs/buffer.c:2894
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8150cb60-ffffffff8150cb7d: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815417d0)
Location: fs/buffer.c:2854
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff815417d0-ffffffff815417ed: sync_dirty_buffer (STB_GLOBAL)
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
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103de158)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffff8000103de158-ffff8000103de188: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b74dc)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
c05b74dc-c05b74fc: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e3e00)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
c0000000004e3e00-c0000000004e3e18: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000295f3e)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffe000295f3e-ffffffe000295f6e: sync_dirty_buffer (STB_GLOBAL)
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
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131d120)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8131d120-ffffffff8131d135: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130dcc0)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8130dcc0-ffffffff8130dcd5: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131abf0)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8131abf0-ffffffff8131ac05: sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c8a0)
Location: fs/buffer.c:3175
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_write_inode
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/dir.c:__fat_remove_entries
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
```
**Symbols:**

```
ffffffff8132c8a0-ffffffff8132c8b5: sync_dirty_buffer (STB_GLOBAL)
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
