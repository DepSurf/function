# Function: <code>fsnotify_find_inode_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_inode_mark(struct fsnotify_group *group, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff8124ff40)
Location: fs/notify/inode_mark.c:79
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
```
**Symbols:**

```
ffffffff8124ff40-ffffffff8124ff89: fsnotify_find_inode_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_inode_mark(struct fsnotify_group *group, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff812786a0)
Location: fs/notify/inode_mark.c:79
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
```
**Symbols:**

```
ffffffff812786a0-ffffffff812786ea: fsnotify_find_inode_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_inode_mark(struct fsnotify_group *group, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff8128c380)
Location: fs/notify/inode_mark.c:79
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
```
**Symbols:**

```
ffffffff8128c380-ffffffff8128c3ca: fsnotify_find_inode_mark (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
