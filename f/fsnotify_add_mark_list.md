# Function: <code>fsnotify_add_mark_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct hlist_head *head, struct fsnotify_mark *mark, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250710)
Location: fs/notify/mark.c:299
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
```
**Symbols:**

```
ffffffff81250710-ffffffff812507fe: fsnotify_add_mark_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct hlist_head *head, struct fsnotify_mark *mark, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278d90)
Location: fs/notify/mark.c:321
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
```
**Symbols:**

```
ffffffff81278d90-ffffffff81278e8a: fsnotify_add_mark_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct hlist_head *head, struct fsnotify_mark *mark, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c9c0)
Location: fs/notify/mark.c:321
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
```
**Symbols:**

```
ffffffff8128c9c0-ffffffff8128caba: fsnotify_add_mark_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299b8e)
Location: fs/notify/mark.c:504
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bcf3e)
Location: fs/notify/mark.c:501
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5b6b)
Location: fs/notify/mark.c:507
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa75d)
Location: fs/notify/mark.c:547
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:543
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff8131a880-ffffffff8131ab49: fsnotify_add_mark_list (STB_LOCAL)
ffffffff8131b517-ffffffff8131b564: fsnotify_add_mark_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132dd47)
Location: fs/notify/mark.c:543
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:547
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81367470-ffffffff8136775a: fsnotify_add_mark_list (STB_LOCAL)
ffffffff813681be-ffffffff813681f2: fsnotify_add_mark_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:547
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff813747d0-ffffffff81374aba: fsnotify_add_mark_list (STB_LOCAL)
ffffffff81beab82-ffffffff81beabb6: fsnotify_add_mark_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:545
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff8137b180-ffffffff8137b471: fsnotify_add_mark_list (STB_LOCAL)
ffffffff81bdcbae-ffffffff81bdcbe3: fsnotify_add_mark_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:574
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff813c7e10-ffffffff813c81b7: fsnotify_add_mark_list (STB_LOCAL)
ffffffff81cc548a-ffffffff81cc54c6: fsnotify_add_mark_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:609
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff8144f6b0-ffffffff8144f99e: fsnotify_add_mark_list.constprop.0 (STB_LOCAL)
ffffffff81e77ea7-ffffffff81e77ede: fsnotify_add_mark_list.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff814ddf50)
Location: fs/notify/mark.c:609
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff814ddf50-ffffffff814de271: fsnotify_add_mark_list.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff81514780)
Location: fs/notify/mark.c:609
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81514780-ffffffff81514aa4: fsnotify_add_mark_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff81548c50)
Location: fs/notify/mark.c:601
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81548c50-ffffffff81548e87: fsnotify_add_mark_list.isra.0 (STB_LOCAL)
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
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e97a8)
Location: fs/notify/mark.c:543
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffff8000103e97a8-ffff8000103e9b40: fsnotify_add_mark_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0f68)
Location: fs/notify/mark.c:543
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
c05c0f68-c05c1348: fsnotify_add_mark_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f0960)
Location: fs/notify/mark.c:543
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
c0000000004f0960-c0000000004f0e64: fsnotify_add_mark_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsnotify_add_mark_list(struct fsnotify_mark *mark, fsnotify_connp_t *connp, unsigned int type, int allow_dups, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029e0ce)
Location: fs/notify/mark.c:543
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffe00029e0ce-ffffffe00029e40e: fsnotify_add_mark_list (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81326327)
Location: fs/notify/mark.c:543
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316ec7)
Location: fs/notify/mark.c:543
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323df7)
Location: fs/notify/mark.c:543
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335b25)
Location: fs/notify/mark.c:543
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
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
</ul>
