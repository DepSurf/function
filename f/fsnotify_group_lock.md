# Function: <code>fsnotify_group_lock</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ecdcd)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
```
```
In fs/notify/mark.c (ffffffff8145040a)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff814507b5)
Location: include/linux/fsnotify_backend.h:264
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81450e7c)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451d75)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456525)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8123335d)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
```
```
In fs/notify/mark.c (ffffffff814dedca)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff814df025)
Location: include/linux/fsnotify_backend.h:264
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814df8ec)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0af5)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e54f9)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8124a00d)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
```
```
In fs/notify/mark.c (ffffffff8151560a)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff815158a5)
Location: include/linux/fsnotify_backend.h:264
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81516177)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff815173a5)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bfb6)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81263f1d)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:tag_chunk
```
```
In fs/notify/mark.c (ffffffff815499ca)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/mark.c:fsnotify_add_mark
```
```
In fs/notify/fdinfo.c (ffffffff81549c65)
Location: include/linux/fsnotify_backend.h:264
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a526)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_flush
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b785)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff815505b9)
Location: include/linux/fsnotify_backend.h:264
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
