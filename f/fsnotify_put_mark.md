# Function: <code>fsnotify_put_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250280)
Location: fs/notify/mark.c:104
Inline: True
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_mark_destroy
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
```
**Symbols:**

```
ffffffff81250280-ffffffff812502ab: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278a80)
Location: fs/notify/mark.c:108
Inline: True
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_mark_destroy_list
  - fs/notify/mark.c:fsnotify_detach_group_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff81278a80-ffffffff81278aab: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c6b0)
Location: fs/notify/mark.c:108
Inline: True
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_mark_destroy_list
  - fs/notify/mark.c:fsnotify_detach_group_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff8128c6b0-ffffffff8128c6db: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299610)
Location: fs/notify/mark.c:207
Inline: True
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff81299610-ffffffff8129977c: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bc980)
Location: fs/notify/mark.c:197
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_get_mark_safe
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff812bc980-ffffffff812bcaf2: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5520)
Location: fs/notify/mark.c:196
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812e5520-ffffffff812e56f9: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa150)
Location: fs/notify/mark.c:239
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff812fa150-ffffffff812fa2e7: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131ab50)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8131ab50-ffffffff8131ace8: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d6c0)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8132d6c0-ffffffff8132d858: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367760)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81367760-ffffffff81367917: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374ac0)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81374ac0-ffffffff81374c77: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137b480)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8137b480-ffffffff8137b637: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c81c0)
Location: fs/notify/mark.c:251
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff813c81c0-ffffffff813c83d3: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f320)
Location: fs/notify/mark.c:293
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8144f320-ffffffff8144f518: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814ddb90)
Location: fs/notify/mark.c:293
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff814ddb90-ffffffff814ddd88: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514370)
Location: fs/notify/mark.c:293
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81514370-ffffffff815145bb: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81548840)
Location: fs/notify/mark.c:293
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81548840-ffffffff81548a8b: fsnotify_put_mark (STB_GLOBAL)
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
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9b40)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffff8000103e9b40-ffff8000103e9d70: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0c24)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c05c0c24-c05c0df4: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f0280)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c0000000004f0280-c0000000004f0574: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029e502)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffe00029e502-ffffffe00029e6f8: fsnotify_put_mark (STB_GLOBAL)
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
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81325ca0)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81325ca0-ffffffff81325e38: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316840)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81316840-ffffffff813169d8: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323770)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81323770-ffffffff81323908: fsnotify_put_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_put_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335420)
Location: fs/notify/mark.c:227
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81335420-ffffffff813355c0: fsnotify_put_mark (STB_GLOBAL)
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
