# Function: <code>fsnotify_add_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812509c0)
Location: fs/notify/mark.c:399
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
**Symbols:**

```
ffffffff812509c0-ffffffff81250a24: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81279050)
Location: fs/notify/mark.c:422
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
**Symbols:**

```
ffffffff81279050-ffffffff812790b4: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128cc80)
Location: fs/notify/mark.c:422
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
```
**Symbols:**

```
ffffffff8128cc80-ffffffff8128cce4: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299de0)
Location: fs/notify/mark.c:614
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
```
**Symbols:**

```
ffffffff81299de0-ffffffff81299e38: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bd1b0)
Location: fs/notify/mark.c:613
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
```
**Symbols:**

```
ffffffff812bd1b0-ffffffff812bd208: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, struct inode *inode, struct vfsmount *mnt, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5dd0)
Location: fs/notify/mark.c:618
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
```
**Symbols:**

```
ffffffff812e5dd0-ffffffff812e5e28: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa9c0)
Location: fs/notify/mark.c:652
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff812fa9c0-ffffffff812faa18: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131b1e0)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff8131b1e0-ffffffff8131b246: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132e070)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff8132e070-ffffffff8132e0d6: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367f10)
Location: fs/notify/mark.c:683
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff81367f10-ffffffff81367f76: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81375280)
Location: fs/notify/mark.c:683
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff81375280-ffffffff813752e6: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137bc20)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff8137bc20-ffffffff8137bc86: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c8a20)
Location: fs/notify/mark.c:708
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff813c8a20-ffffffff813c8a86: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814500d0)
Location: fs/notify/mark.c:744
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff814500d0-ffffffff81450185: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814dea70)
Location: fs/notify/mark.c:744
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff814dea70-ffffffff814deb25: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815152b0)
Location: fs/notify/mark.c:744
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff815152b0-ffffffff81515365: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int obj_type, int add_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81549680)
Location: fs/notify/mark.c:709
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff81549680-ffffffff8154972a: fsnotify_add_mark (STB_GLOBAL)
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
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103ea690)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffff8000103ea690-ffff8000103ea710: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c1a64)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
c05c1a64-c05c1ad0: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f1850)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
c0000000004f1850-c0000000004f18e4: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029ee5c)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffe00029ee5c-ffffffe00029eeca: fsnotify_add_mark (STB_GLOBAL)
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
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81326650)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff81326650-ffffffff813266b6: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813171f0)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff813171f0-ffffffff81317256: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81324120)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff81324120-ffffffff81324186: fsnotify_add_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fsnotify_add_mark(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335e70)
Location: fs/notify/mark.c:679
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
**Symbols:**

```
ffffffff81335e70-ffffffff81335ed6: fsnotify_add_mark (STB_GLOBAL)
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
