# Function: <code>fsnotify_destroy_marks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_destroy_marks(struct hlist_head *head, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250600)
Location: fs/notify/mark.c:214
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:__fsnotify_inode_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff81250600-ffffffff8125067e: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_destroy_marks(struct hlist_head *head, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278c70)
Location: fs/notify/mark.c:236
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
  - fs/notify/fsnotify.c:__fsnotify_inode_delete
```
**Symbols:**

```
ffffffff81278c70-ffffffff81278cf2: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_destroy_marks(struct hlist_head *head, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c8a0)
Location: fs/notify/mark.c:236
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
  - fs/notify/fsnotify.c:__fsnotify_inode_delete
```
**Symbols:**

```
ffffffff8128c8a0-ffffffff8128c922: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_destroy_marks(struct fsnotify_mark_connector **connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8129a000)
Location: fs/notify/mark.c:699
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff8129a000-ffffffff8129a0b8: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_destroy_marks(struct fsnotify_mark_connector **connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bd3d0)
Location: fs/notify/mark.c:698
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff812bd3d0-ffffffff812bd488: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_destroy_marks(struct fsnotify_mark_connector **connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5ff0)
Location: fs/notify/mark.c:704
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff812e5ff0-ffffffff812e6107: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fabd0)
Location: fs/notify/mark.c:737
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff812fabd0-ffffffff812facae: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131b410)
Location: fs/notify/mark.c:764
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff8131b410-ffffffff8131b4f2: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132e220)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff8132e220-ffffffff8132e302: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813680c0)
Location: fs/notify/mark.c:769
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff813680c0-ffffffff813681be: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81375430)
Location: fs/notify/mark.c:769
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff81375430-ffffffff8137552e: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137bdd0)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff8137bdd0-ffffffff8137bece: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c8be0)
Location: fs/notify/mark.c:794
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff813c8be0-ffffffff813c8d09: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81450390)
Location: fs/notify/mark.c:831
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff81450390-ffffffff814504f9: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814ded50)
Location: fs/notify/mark.c:831
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff814ded50-ffffffff814deeb9: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815155a0)
Location: fs/notify/mark.c:831
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff815155a0-ffffffff8151573b: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81549960)
Location: fs/notify/mark.c:795
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff81549960-ffffffff81549afb: fsnotify_destroy_marks (STB_GLOBAL)
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
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103ea860)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffff8000103ea860-ffff8000103ea9c4: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c1c10)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
c05c1c10-c05c1d28: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f1ad0)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
c0000000004f1ad0-c0000000004f1cd4: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029efd0)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffe00029efd0-ffffffe00029f118: fsnotify_destroy_marks (STB_GLOBAL)
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
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81326800)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff81326800-ffffffff813268e2: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813173a0)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff813173a0-ffffffff81317482: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813242d0)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff813242d0-ffffffff813243b2: fsnotify_destroy_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_destroy_marks(fsnotify_connp_t *connp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81336020)
Location: fs/notify/mark.c:765
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:__fsnotify_vfsmount_delete
```
**Symbols:**

```
ffffffff81336020-ffffffff81336124: fsnotify_destroy_marks (STB_GLOBAL)
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
<li>
<b>Param removed. </b>
<code>spinlock_t *lock</code>
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
