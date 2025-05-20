# Function: <code>fsnotify_recalc_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 fsnotify_recalc_mask(struct hlist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250400)
Location: fs/notify/mark.c:115
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_recalc_inode_mask
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_recalc_vfsmount_mask
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
```
**Symbols:**

```
ffffffff81250400-ffffffff81250426: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 fsnotify_recalc_mask(struct hlist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278af0)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
  - fs/notify/inode_mark.c:fsnotify_recalc_inode_mask
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_recalc_vfsmount_mask
```
**Symbols:**

```
ffffffff81278af0-ffffffff81278b29: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 fsnotify_recalc_mask(struct hlist_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c720)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
  - fs/notify/inode_mark.c:fsnotify_recalc_inode_mask
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_recalc_vfsmount_mask
```
**Symbols:**

```
ffffffff8128c720-ffffffff8128c759: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff81299cfd)
Location: fs/notify/mark.c:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff81299780-ffffffff812997b6: fsnotify_recalc_mask.part.8 (STB_LOCAL)
ffffffff812997e0-ffffffff812997f7: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff812bd0ad)
Location: fs/notify/mark.c:135
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff812bcc00-ffffffff812bcc36: fsnotify_recalc_mask.part.8 (STB_LOCAL)
ffffffff812bcc60-ffffffff812bcc77: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5cff)
Location: fs/notify/mark.c:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812e5380-ffffffff812e53ba: fsnotify_recalc_mask.part.13 (STB_LOCAL)
ffffffff812e57d0-ffffffff812e57e6: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa390)
Location: fs/notify/mark.c:153
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff812fa390-ffffffff812fa3d7: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131ad90)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8131ad90-ffffffff8131addd: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d980)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8132d980-ffffffff8132d9cd: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367e7f)
Location: fs/notify/mark.c:141
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81367a70-ffffffff81367ac1: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813751ef)
Location: fs/notify/mark.c:141
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81374df0-ffffffff81374e41: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137bb9b)
Location: fs/notify/mark.c:141
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8137b7b0-ffffffff8137b801: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c899b)
Location: fs/notify/mark.c:141
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff813c8560-ffffffff813c85b1: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81450030)
Location: fs/notify/mark.c:185
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8144fb20-ffffffff8144fb83: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814de9c0)
Location: fs/notify/mark.c:185
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff814de440-ffffffff814de4a3: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81515200)
Location: fs/notify/mark.c:185
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81514c70-ffffffff81514cd3: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815495da)
Location: fs/notify/mark.c:185
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81549050-ffffffff815490b3: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9f60)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffff8000103e9f60-ffff8000103e9ff0: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c14d0)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c05c14d0-c05c152c: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f0f30)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/dnotify/dnotify.c:dnotify_recalc_inode_mask
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c0000000004f0f30-c0000000004f0ff0: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029e7f6)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffe00029e7f6-ffffffe00029e88a: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81325f60)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81325f60-ffffffff81325fad: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316b00)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81316b00-ffffffff81316b4d: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323a30)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81323a30-ffffffff81323a7d: fsnotify_recalc_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335770)
Location: fs/notify/mark.c:141
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81335770-ffffffff813357b5: fsnotify_recalc_mask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_mark_connector *conn</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hlist_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
