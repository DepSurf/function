# Function: <code>fsnotify_add_inode_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fsnotify_add_inode_mark(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff8124ffd0)
Location: fs/notify/inode_mark.c:123
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff8124ffd0-ffffffff81250054: fsnotify_add_inode_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fsnotify_add_inode_mark(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff81278730)
Location: fs/notify/inode_mark.c:123
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81278730-ffffffff812787b4: fsnotify_add_inode_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fsnotify_add_inode_mark(struct fsnotify_mark *mark, struct fsnotify_group *group, struct inode *inode, int allow_dups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff8128c410)
Location: fs/notify/inode_mark.c:123
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff8128c410-ffffffff8128c498: fsnotify_add_inode_mark (STB_GLOBAL)
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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81159272)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811597f0)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/audit_tree.c (ffffffff8115a70d)
Location: include/linux/fsnotify_backend.h:407
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81166216)
Location: include/linux/fsnotify_backend.h:439
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81166760)
Location: include/linux/fsnotify_backend.h:439
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81172dec)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81173309)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117ec9a)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8117f179)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81192165)
Location: include/linux/fsnotify_backend.h:482
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8119268b)
Location: include/linux/fsnotify_backend.h:482
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118f2f5)
Location: include/linux/fsnotify_backend.h:531
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8118f7fb)
Location: include/linux/fsnotify_backend.h:531
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8119020d)
Location: include/linux/fsnotify_backend.h:537
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8119073b)
Location: include/linux/fsnotify_backend.h:537
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b90ed)
Location: include/linux/fsnotify_backend.h:537
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811b961b)
Location: include/linux/fsnotify_backend.h:537
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811ec11a)
Location: include/linux/fsnotify_backend.h:699
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811ec6fc)
Location: include/linux/fsnotify_backend.h:699
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
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
In kernel/audit_watch.c (ffffffff8123257a)
Location: include/linux/fsnotify_backend.h:776
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81232bdc)
Location: include/linux/fsnotify_backend.h:776
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
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
In kernel/audit_watch.c (ffffffff81249220)
Location: include/linux/fsnotify_backend.h:776
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8124985c)
Location: include/linux/fsnotify_backend.h:776
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
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
In kernel/audit_watch.c (ffffffff812630dc)
Location: include/linux/fsnotify_backend.h:772
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81263775)
Location: include/linux/fsnotify_backend.h:772
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffff8000101f3b94)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffff8000101f4114)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0434020)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (c04344e8)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c000000000268a2c)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (c0000000002691b0)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffe000166f66)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffe000167428)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811772ba)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81177799)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8116a45a)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8116a939)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117508a)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81175569)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118296a)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81182e49)
Location: include/linux/fsnotify_backend.h:455
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
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
</ul>
