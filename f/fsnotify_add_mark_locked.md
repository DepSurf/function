# Function: <code>fsnotify_add_mark_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250800)
Location: fs/notify/mark.c:336
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81250800-ffffffff812509b8: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278e90)
Location: fs/notify/mark.c:358
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81278e90-ffffffff8127904d: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128cac0)
Location: fs/notify/mark.c:358
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff8128cac0-ffffffff8128cc72: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299af0)
Location: fs/notify/mark.c:571
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81299af0-ffffffff81299ddd: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bcea0)
Location: fs/notify/mark.c:568
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812bcea0-ffffffff812bd1a3: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5ad0)
Location: fs/notify/mark.c:574
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff812e5ad0-ffffffff812e5dc9: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa6e0)
Location: fs/notify/mark.c:609
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff812fa6e0-ffffffff812fa9bb: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131b0d0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8131b0d0-ffffffff8131b1de: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8132e302-ffffffff8132e33e: fsnotify_add_mark_locked.cold (STB_LOCAL)
ffffffff8132dcc0-ffffffff8132e06f: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367dc0)
Location: fs/notify/mark.c:640
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81367dc0-ffffffff81367f03: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81375130)
Location: fs/notify/mark.c:640
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81375130-ffffffff81375273: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137bae0)
Location: fs/notify/mark.c:638
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8137bae0-ffffffff8137bc1b: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c88e0)
Location: fs/notify/mark.c:667
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff813c88e0-ffffffff813c8a1b: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144ff80)
Location: fs/notify/mark.c:704
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8144ff80-ffffffff814500ca: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814de910)
Location: fs/notify/mark.c:704
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff814de910-ffffffff814dea5a: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81515150)
Location: fs/notify/mark.c:704
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81515150-ffffffff8151529a: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81549530)
Location: fs/notify/mark.c:669
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
```
**Symbols:**

```
ffffffff81549530-ffffffff8154966f: fsnotify_add_mark_locked (STB_GLOBAL)
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
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103ea460)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffff8000103ea460-ffff8000103ea68c: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c18f8)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
c05c18f8-c05c1a64: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f15c0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
c0000000004f15c0-c0000000004f184c: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029ece0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffe00029ece0-ffffffe00029ee5c: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff813268e2-ffffffff8132691e: fsnotify_add_mark_locked.cold (STB_LOCAL)
ffffffff813262a0-ffffffff8132664f: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81317482-ffffffff813174be: fsnotify_add_mark_locked.cold (STB_LOCAL)
ffffffff81316e40-ffffffff813171ef: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff813243b2-ffffffff813243ee: fsnotify_add_mark_locked.cold (STB_LOCAL)
ffffffff81323d70-ffffffff8132411f: fsnotify_add_mark_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_locked(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:636
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - fs/notify/mark.c:fsnotify_add_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81336124-ffffffff81336170: fsnotify_add_mark_locked.cold (STB_LOCAL)
ffffffff81335aa0-ffffffff81335e6b: fsnotify_add_mark_locked (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct fsnotify_group *group</code>
</li>
<li>
<b>Param reordered. </b>
<code>mark, group, inode, mnt, allow_dups</code> ➡️ <code>mark, inode, mnt, allow_dups</code>
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
<b>Param added. </b>
<code>fsnotify_connp_t *connp</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount *mnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__kernel_fsid_t *fsid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int obj_type</code>
</li>
<li>
<b>Param added. </b>
<code>int add_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>int allow_dups</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__kernel_fsid_t *fsid</code>
</li>
</ul>
</details>
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
