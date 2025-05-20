# Function: <code>ext4_fc_mark_ineligible</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814568e0)
Location: fs/ext4/fast_commit.c:318
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff814568e0-ffffffff8145691f: ext4_fc_mark_ineligible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c290)
Location: fs/ext4/fast_commit.c:318
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff8145c290-ffffffff8145c2cf: ext4_fc_mark_ineligible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason, handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814afaf0)
Location: fs/ext4/fast_commit.c:309
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff814afaf0-ffffffff814afbd0: ext4_fc_mark_ineligible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason, handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538080)
Location: fs/ext4/fast_commit.c:335
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff81538080-ffffffff81538175: ext4_fc_mark_ineligible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason, handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d62a0)
Location: fs/ext4/fast_commit.c:338
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff815d62a0-ffffffff815d6395: ext4_fc_mark_ineligible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason, handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160de50)
Location: fs/ext4/fast_commit.c:338
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff8160de50-ffffffff8160df45: ext4_fc_mark_ineligible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_mark_ineligible(struct super_block *sb, int reason, handle_t *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81646c10)
Location: fs/ext4/fast_commit.c:338
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__track_dentry_update
  - fs/ext4/fast_commit.c:__track_dentry_update
```
**Symbols:**

```
ffffffff81646c10-ffffffff81646d05: ext4_fc_mark_ineligible (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>handle_t *handle</code>
</li>
</ul>
</details>
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
