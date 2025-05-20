# Function: <code>fsnotify_find_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(struct hlist_head *head, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250a30)
Location: fs/notify/mark.c:413
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_find_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_find_vfsmount_mark
```
**Symbols:**

```
ffffffff81250a30-ffffffff81250a65: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(struct hlist_head *head, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812790c0)
Location: fs/notify/mark.c:436
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_find_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_find_vfsmount_mark
```
**Symbols:**

```
ffffffff812790c0-ffffffff81279103: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(struct hlist_head *head, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128ccf0)
Location: fs/notify/mark.c:436
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_find_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_find_vfsmount_mark
```
**Symbols:**

```
ffffffff8128ccf0-ffffffff8128cd33: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(struct fsnotify_mark_connector **connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299e40)
Location: fs/notify/mark.c:630
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff81299e40-ffffffff81299ec7: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(struct fsnotify_mark_connector **connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bd210)
Location: fs/notify/mark.c:629
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff812bd210-ffffffff812bd297: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(struct fsnotify_mark_connector **connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5e30)
Location: fs/notify/mark.c:635
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812e5e30-ffffffff812e5eb7: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812faa20)
Location: fs/notify/mark.c:669
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff812faa20-ffffffff812faaa0: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131b250)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8131b250-ffffffff8131b2d0: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d8c0)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8132d8c0-ffffffff8132d940: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813679b0)
Location: fs/notify/mark.c:700
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff813679b0-ffffffff81367a2e: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374d10)
Location: fs/notify/mark.c:700
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81374d10-ffffffff81374d8e: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137b6d0)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8137b6d0-ffffffff8137b748: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c8480)
Location: fs/notify/mark.c:725
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff813c8480-ffffffff813c84f8: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144fa20)
Location: fs/notify/mark.c:762
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8144fa20-ffffffff8144fab5: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814de320)
Location: fs/notify/mark.c:762
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff814de320-ffffffff814de3b5: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514b50)
Location: fs/notify/mark.c:762
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81514b50-ffffffff81514be5: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81548f30)
Location: fs/notify/mark.c:726
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81548f30-ffffffff81548fc5: fsnotify_find_mark (STB_GLOBAL)
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
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9e48)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffff8000103e9e48-ffff8000103e9ef4: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c13ac)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c05c13ac-c05c146c: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f0810)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c0000000004f0810-c0000000004f0958: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029e40e)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffe00029e40e-ffffffe00029e502: fsnotify_find_mark (STB_GLOBAL)
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
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81325ea0)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81325ea0-ffffffff81325f20: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316a40)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81316a40-ffffffff81316ac0: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323970)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81323970-ffffffff813239f0: fsnotify_find_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_mark(fsnotify_connp_t *connp, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813356b0)
Location: fs/notify/mark.c:696
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff813356b0-ffffffff8133572c: fsnotify_find_mark (STB_GLOBAL)
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
<code>struct fsnotify_mark_connector **connp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hlist_head *head</code>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fsnotify_mark_connector **connp</code> ➡️ <code>fsnotify_connp_t *connp</code>
</li>
</ul>
</details>
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
