# Function: <code>fsnotify_detach_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250430)
Location: fs/notify/mark.c:131
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
```
**Symbols:**

```
ffffffff81250430-ffffffff812504f2: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278b30)
Location: fs/notify/mark.c:135
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_detach_group_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff81278b30-ffffffff81278bf2: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c760)
Location: fs/notify/mark.c:135
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_detach_group_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff8128c760-ffffffff8128c822: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299970)
Location: fs/notify/mark.c:336
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff81299970-ffffffff812999f8: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bcd20)
Location: fs/notify/mark.c:333
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff812bcd20-ffffffff812bcda8: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5940)
Location: fs/notify/mark.c:340
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812e5940-ffffffff812e59c8: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa550)
Location: fs/notify/mark.c:384
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff812fa550-ffffffff812fa5d8: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131af30)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8131af30-ffffffff8131afc1: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132db20)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8132db20-ffffffff8132dbb2: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367c30)
Location: fs/notify/mark.c:375
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81367c30-ffffffff81367cc2: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374fa0)
Location: fs/notify/mark.c:375
Inline: False
Direct callers:
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81374fa0-ffffffff81375032: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137b960)
Location: fs/notify/mark.c:375
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8137b960-ffffffff8137b9eb: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c8760)
Location: fs/notify/mark.c:399
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff813c8760-ffffffff813c87eb: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144fd50)
Location: fs/notify/mark.c:442
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff8144fd50-ffffffff8144fe05: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814de6a0)
Location: fs/notify/mark.c:442
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff814de6a0-ffffffff814de755: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514ed0)
Location: fs/notify/mark.c:442
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81514ed0-ffffffff81514f85: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815492b0)
Location: fs/notify/mark.c:442
Inline: False
Direct callers:
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff815492b0-ffffffff81549365: fsnotify_detach_mark (STB_GLOBAL)
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
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103ea1b8)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffff8000103ea1b8-ffff8000103ea2c8: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c16c0)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c05c16c0-c05c17b4: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f1270)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
c0000000004f1270-c0000000004f13bc: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029ea44)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffe00029ea44-ffffffe00029eb46: fsnotify_detach_mark (STB_GLOBAL)
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
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81326100)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81326100-ffffffff81326192: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316ca0)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81316ca0-ffffffff81316d32: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323bd0)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81323bd0-ffffffff81323c62: fsnotify_detach_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_detach_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335910)
Location: fs/notify/mark.c:371
Inline: False
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_destroy_mark
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
**Symbols:**

```
ffffffff81335910-ffffffff8133599e: fsnotify_detach_mark (STB_GLOBAL)
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
